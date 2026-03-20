# Reproducibility Notes

## Environment

- Framework: TensorFlow 2.x
- Training hardware: GPU (Colab / local)
- Edge simulation: Colab CPU reconfigured to 1.5 GHz clock, 4 threads
  (mimics Raspberry Pi 4B Broadcom BCM2711)

## Reproducibility

All training code available in the primary research repository:
https://github.com/EvansKonadu/AI-Powered-Pneumonia-Detection-in-Low-Resource-Settings

## Quantisation Details

Xception (Mendeley):
- Method: Post-Training Parameter Quantisation (PT-PQ), INT8
- Calibration: ~520 representative samples
- Result: Accuracy improved 96.96% → 97.12% (regularisation effect)

EfficientNetB4 (NIH):
- Method: Hybrid Dynamic Range, INT8 weights / FP32 activations
- Result: 91% size reduction, 5.16pp accuracy trade-off

## Datasets

Neither dataset is redistributed here. Access via original sources:
- Mendeley: DOI 10.17632/rscbjbr9sj.3
- NIH: https://nihcc.app.box.com/v/ChestXray-NIHCC
