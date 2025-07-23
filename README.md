# AIWIP – AI Web Interface Protocol

**AIWIP** is an open standard for making websites and digital content machine-readable by AI agents like ChatGPT, Copilot, Claude, and Perplexity.

## 🌐 What Is AIWIP?

AIWIP defines a lightweight, structured interface between public websites and large language models. By exposing key information such as business summaries, services, FAQs, and contact details in JSON format, websites can become more visible, understandable, and interactive to AI systems.

## ❓ Why It Matters

Search engines crawled websites for decades using unstructured content. But AI agents now summarise, recommend, and even *act on behalf* of users. AIWIP enables a future where:

- Websites can speak directly to AI in a predictable, machine-readable format.
- Businesses become discoverable and interactive via AI tools.
- Developers can build AI-aware experiences that consume public content cleanly and fairly.

## 📦 Schema Modules (v0.1)

AIWIP v0.1 will include the following modules:

| Schema File | Purpose |
|-------------|---------|
| `aiwip-summary.json` | Website-level TL;DR summary, key facts, purpose |
| `aiwip-services.json` | Structured list of services/products |
| `aiwip-faq.json` | Frequently asked questions with answers |
| (Planned) `aiwip-contact.json` | Operating hours, support options, location, etc. |
| (Planned) `aiwip-articles.json` | Summarised content, guides, case studies |

These will be published under permissive open license for public use and extension.

## 🧪 Example

```json
// https://yourdomain.com/aiwip-summary.json
{
  "aiwip-version": "0.1",
  "name": "Workflation",
  "description": "We help businesses automate workflows using RPA and AI.",
  "location": "Global",
  "services": ["Excel automation", "Chatbot integration", "Web scraping"],
  "website": "https://workflation.com"
}
```

## License

The AIWIP Specification is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

