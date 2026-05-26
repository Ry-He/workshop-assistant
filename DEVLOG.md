## DEVLOG

### 5/26/2026 - Milestone 1 Complete
- Environment: Pop!_OS 24.04, Python 3.12.3, PyTorch 2.11.0+cu128
- Pretrained YOLOv8n running live on webcam via OpenCV
- Inference: ~4.5ms at 480x640 on RTX 4070 (nano model, COCO classes)
- Note: skipped CUDA toolkit install — PyTorch bundles its own runtime, no issues
- Next: tool class definition, data collection strategy