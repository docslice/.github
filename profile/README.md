<h1 align="center">DocSlice</h1>

<p align="center">
  <b>Document parsing API: PDF, DOCX and scans to JSON, Markdown or HTML with one REST call.</b><br>
  Hosted in the EU (Frankfurt). Free plan, no credit card.
</p>

<p align="center">
  <a href="https://api.docslice.app/app#signup">Create a free account</a> ·
  <a href="https://docslice.app/docs/">Documentation</a> ·
  <a href="https://docslice.app">Website</a>
</p>

---

### Try it in one call

```bash
curl -s https://api.docslice.app/v1/convert \
  -H "Authorization: Bearer $DOCSLICE_API_KEY" \
  -F "file=@invoice.pdf" \
  -F "format=json"
```

Send a JSON Schema and you get back only the fields you asked for, typed and validated.

### What it does

- **Formats in:** PDF, DOCX, RTF, TXT, CSV and images (scans are read with automatic OCR)
- **Formats out:** JSON, Markdown, HTML
- **Schema extraction:** your own JSON Schema, with types and descriptions
- **Tables and key-value pairs:** multi-column tables, headers and metadata kept
- **Async jobs and webhooks:** for batches and large files

### Repositories

| Repository | What you get |
|---|---|
| [docslice-examples](https://github.com/docslice/docslice-examples) | Ready-to-run examples in cURL, Python, Node.js and PHP, with sample files |
| [invoice-to-csv](https://github.com/docslice/invoice-to-csv) | A folder of invoices (PDF, DOCX, scans) turned into CSV with a JSON Schema |
| [webhook-starter](https://github.com/docslice/webhook-starter) | A dependency-free webhook receiver: secret path, idempotent, confirms each job with the API |
| [docslice-openapi](https://github.com/docslice/docslice-openapi) | OpenAPI 3.1 spec and a Postman collection |

### Free plan

500 welcome pages that never expire, plus 50 pages every month. All output formats and the full API.
A **Pro** plan with 5,000 pages per month is coming soon.

### Your documents

Files are deleted right after processing, async results are erased after 24 hours, and documents are never used to train AI models. Details in the [privacy policy](https://docslice.app/privacy.html).

---

<p align="center">
  Questions or ideas? Open an issue in any repository or write to <a href="mailto:hello@docslice.app">hello@docslice.app</a>.
</p>
