# OCR PDF — Example

## Copy-paste

```bash
# Extract text from scanned PDF
pdftoppm -r 300 input.pdf page && tesseract page-1.png output
```

## Expected Output

- Text extracted to stdout
- Requires: `tesseract`, `poppler-utils`
