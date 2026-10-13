# Generate DOCX — Example

## Copy-paste

```python
from docx import Document
doc = Document()
doc.add_heading("Report", 0)
doc.add_paragraph("Content here")
doc.save("report.docx")
```

## Expected Output

- File: `report.docx`
- No API keys needed
- Local only
