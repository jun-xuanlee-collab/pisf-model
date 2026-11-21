# PISF inspection model

The detection model used by the PISF Junior Vision Inspection System (https://pisf-demo-app-2026.netlify.app/).

The model (`model.onnx`, 22,504,309 bytes, YOLOv8s with fp16 weights) is stored here as three consecutive parts of
about 7.5 MB, because the jsDelivr CDN serves GitHub files only up to 20 MB each. Join them in order to get the model:

    cat model-11e111d0392a.part0.bin model-11e111d0392a.part1.bin model-11e111d0392a.part2.bin > model.onnx

SHA-256 of the joined file: `11e111d0392a2db0797ddfa898dc5a2d439277a2195d458589c4c3b18d6eaaa0` (see `manifest.json`).

The files are named after their content and never change, so they are safe to cache forever. The app checks the
SHA-256 of every download before using it, and falls back to its own copy if this one is unavailable.
