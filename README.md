### About
This documentation is about creating **Classifications & Tags** and **Glossary & Terms** in **Openmetadata** with **REST API**.
It outlines:
- The APIs used for metadata creation
- The file structure followed for organizing classification and glossary definitions

---

### APIs Used

| Purpose | Method | Endpoint |
|------|--------|---------|
| Create classification | POST | `/api/v1/classifications` |
| Create tag | POST | `/api/v1/tags` |
| Create glossary | POST | `/api/v1/glossaries` |
| Create multiple glossary terms | POST | `/api/v1/glossaryTerms/createMany` |

---

### File Structure 

```bash
├── classifications/
│   ├── sensitivity.json
│   ├── pii.json
│   └── data_quality.json
│
├── glossaries/
│   ├── telecom_data.json
│   ├── inventory.json
│   └── billing.json
│
├── push_classifications.py
├── push_glossaries.py
```