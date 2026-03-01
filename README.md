# Digital Sovereignty Assessment Tool

A self-assessment questionnaire for digital sovereignty, designed to run **100% locally in the browser**.

## 🔒 Security & Privacy (Core Principle)

This project is intentionally built for local use to protect sensitive information:

- **No backend required**.
- **No external network calls are needed** to complete the questionnaire.
- **No data is sent to external servers**.
- Responses are stored only in the user's browser (local storage), on the user's machine.

In short: your data stays under your control, in your own environment.

## 🎯 Purpose

The tool helps evaluate an organization's digital sovereignty maturity across multiple dimensions (cloud, data, identity, infrastructure, compliance, etc.), then provides a score and summary.

## 🧱 Tech Stack

- HTML
- CSS
- JavaScript (vanilla)
- Single-page static app (`index.html`)

## ▶️ Run Locally

### Option 1 — Open directly

1. Clone the repository.
2. Open `index.html` in your browser.

### Option 2 — Use a local server (recommended for team usage)

From the project root:

```bash
python3 -m http.server 8000
```

Then open: `http://localhost:8000`

## ✅ Recommended Use Cases

- Internal assessment workshops.
- Sensitive contexts (security, compliance, enterprise architecture, data sovereignty).
- Demonstrations where you must ensure that no information leaves the user's device.

## ⚠️ Good Practices

- Run the tool on a trusted workstation.
- Avoid untrusted browser extensions in sensitive contexts.
- Clear browser storage after use if required.

## 📄 License

This project is distributed under the MIT License. See `LICENSE`.
