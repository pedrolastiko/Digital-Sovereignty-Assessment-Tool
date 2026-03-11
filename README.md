# Digital Sovereignty Assessment Tool

A self-assessment questionnaire for digital sovereignty, designed to run **100% locally in the browser**.

## 🎯 Purpose

The tool helps evaluate an organization's digital sovereignty maturity across multiple dimensions (cloud, data, identity, infrastructure, compliance, etc.), then provides a score and summary.

## ✅ Use Cases

- Internal assessment workshops.
- Sensitive contexts (security, compliance, enterprise architecture, data sovereignty).
- Demonstrations where you must ensure that no information leaves the user's device.

## ⚠️ Good Practices

- Run the tool on a trusted workstation.
- Avoid untrusted browser extensions in sensitive contexts.
- Clear browser storage after use if required.

## 📚 Additional Resources

### Certifications

- **AIGP — Artificial Intelligence Governance Professional (IAPP)**: https://iapp.org/certify/aigp

### Declarations & Commitments

- **Montreal Declaration for a Responsible Development of Artificial Intelligence — Citizen signatories**: https://montrealdeclaration-responsibleai.com/i-sign-the-declaration/citizen-signatories/?page_size=100

### Research Articles

- **ScienceDirect article (S2666389923002416)**: https://www.sciencedirect.com/science/article/pii/S2666389923002416

## 🔒 Security & Privacy (Core Principle)

This project is intentionally built for local use to protect sensitive information:

- **No backend required**.
- **No external network calls are needed** to complete the questionnaire.
- **No data is sent to external servers**.
- Responses are stored only in the user's browser (local storage), on the user's machine.

In short: your data stays under your control, in your own environment.



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

## 📦 HTML File (Ready to Use)

The runnable HTML file is available directly in the repository:

- `index.html`

You can open it directly in a browser, or serve it locally with:

```bash
python3 -m http.server 8000
```

Then visit: `http://localhost:8000`

## 📄 License

This project is distributed under the MIT License. See `LICENSE`.
