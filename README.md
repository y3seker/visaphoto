# 35×45 — Schengen visa photo cropper

Drop one or more portraits; the page finds the face, crops each to 35 × 45 mm
(chin → crown 32–36 mm), optionally replaces the background, and lays the photos
out on a print sheet (10×15, 4×6″, 13×18, 15×20, A5, A4, Letter) as 300 DPI JPGs.

Everything runs in the browser (MediaPipe face landmarker + selfie segmenter);
no photo is uploaded anywhere. UI in Turkish, English and German.

Run locally:

```bash
python3 -m http.server 8765
```
