# Quantization report (CIFAR-10)
Date: 2025-10-27 18:11:44

## Results
| model | top1 (%) | correct | total | avg_ms/img | path |
|---|---:|---:|---:|---:|---|
| float32 | 95.90 | 959 | 1000 | 11.78 | checkpoints/effnet_b3_cifar10_alb.onnx |
| int8 | 8.10 | 81 | 1000 | 38.80 | checkpoints/effnet_b3_cifar10_alb_int8.onnx |
