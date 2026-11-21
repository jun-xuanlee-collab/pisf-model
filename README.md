# PISF inspection model

The detection model used by the PISF Junior Vision Inspection System (https://pisf-demo-app-2026.netlify.app/).

- `model-11e111d0392a.onnx` — YOLOv8s, weights stored in fp16 (22.5 MB), input `images` float32 [1,3,960,960], output `output0` float32 [1,8,18900]
- SHA-256: `11e111d0392a2db0797ddfa898dc5a2d439277a2195d458589c4c3b18d6eaaa0`

Files are named after their content hash and never change, so they are safe to cache forever. The app checks the SHA-256 of every download before using it, and falls back to its own copy if this one is unavailable.
