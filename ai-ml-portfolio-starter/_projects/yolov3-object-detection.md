---
title: "Real-time Object Detection with YOLOv3"
excerpt: "Custom dataset, 92% mAP on held-out set; Deployed with ONNX Runtime for CPU inference."
permalink: /projects/yolov3-object-detection/
header:
  overlay_image: /assets/img/og-image.png
  overlay_filter: 0.35
badges:
  - label: "Computer Vision"
  - label: "YOLOv3"
  - label: "PyTorch"
links:
  - label: "Code"
    url: "https://github.com/yourusername/yolov3-project"
  - label: "Demo"
    url: "#"
---

**Problem:** Detect objects in [domain] with real-time constraints.  
**Data:** ~10k labeled images; train/val/test split 70/15/15.  
**Model:** YOLOv3 with transfer learning from COCO.  
**Results:** 92% mAP@0.5; 18ms per frame on RTX 3060; CPU inference via ONNX Runtime.  
**Impact:** Reduced manual QA time by 40% in pilot setting.
