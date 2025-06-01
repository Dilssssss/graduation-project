# graduation-project
all files containing app code for final project 

# Matcha 

Welcome to **Matcha**, a mobile app that helps users discover dupes

## Testing This Project

Before diving in

All test assets are located inside the `barcodes+images/` folder, which contains:

- `barcodes/` — 4 sample barcode images
- `ocr image/` — photos of product packaging for OCR testing
- `ai makeup image/` — Pinterest-style makeup looks for AI analysis

---

### Barcode Scanning

Use the images in the `barcodes/` folder to test the **barcode scanning** feature.

- Upload the barcode images through the app or scan them directly using a physical iOS device.
- These barcodes correspond to 4 real products manually linked to the internal ingredient database.
- Due to API and data access limits, barcode support is currently limited to these 4 items.

---

### OCR Image Recognition

In the `ocr image/` folder, you’ll find photos of product packaging.

- Upload one of these into the app to test **image-based product recognition** using Apple’s Vision framework.
- The app extracts text from the packaging and matches it against the product database using token similarity.

---

### AI Makeup Look Detection

Use the `ai makeup image/` folder to explore the **AI look detection** feature.

- Upload any of these inspiration images to trigger colour analysis and product matching.
- The app identifies dominant lip colours and suggests similar shades from the product dataset.
- You can also upload your own selfies or looks for custom suggestions.

 **Note:** The AI look detector is an early prototype. It performs reasonably well with some colours, but struggles with undertones, gradients, or complex lighting. Accuracy is limited by the current dataset and colour detection method, so results can vary widely.

---

## Limitations

- The product database is **manually curated** (due to limited access to major retailer APIs).
- AI makeup detection is experimental and still being refined.
- The current version runs on **iOS only**.
- Some features rely on the provided demo data and may not work as expected with unrelated images.

---

