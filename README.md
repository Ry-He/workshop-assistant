# Workshop Assistant

Real-time computer vision system for detecting, tracking, and querying 
workshop tools by camera. Ask "where's the angle grinder?" and get an answer.

## Current Phase: CV & Tracking
- Real-time object detection and tracking from fixed camera feeds
- Custom-trained YOLOv11 model fine-tuned on workshop tool classes
- Natural language query interface via local LLM
- Runs fully locally; Jetson deployment planned

## Later Phases
- Smart tool rack integration
- Smart vise
- DIY robot arm  
- Unified agentic control layer

## Stack
PyTorch · YOLOv11 (Ultralytics) · OpenCV · Ollama