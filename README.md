# ScriptureFlow API 🌊
[![Sponsor](https://img.shields.io/badge/Sponsor-ScriptureFlow-blue?logo=github-sponsors&style=flat)](https://github.com/sponsors/Exnav29)

**ScriptureFlow** is a modern, open-source platform for accessing the Holy Scriptures through a simple and reliable JSON API.  
It builds upon the pioneering [Bible-API](https://github.com/wldeh/bible-api) by [Henok Woldesenbet](https://github.com/wldeh), honoring his foundational work while introducing a refreshed vision for performance, multilingual access, and AI-ready integration.

> “The Word became flesh and dwelt among us.” — John 1:14  
> ScriptureFlow brings the Word into today’s digital world — accessible, structured, and free.

---

## 🙏 Credits & Origins

This project would not exist without the groundwork of **Henok Woldesenbet** and his original **Bible-API**.  
Full credit is given for his early contributions that made Scripture data freely accessible to developers worldwide.

ScriptureFlow carries that legacy forward — expanding, modernizing, and maintaining it as a living, community-driven project.

---

## 🌍 Vision

To make the Word of God **universally accessible** in every language and format — empowering developers, ministries, and educators to integrate Scripture seamlessly into digital experiences.

---
## ❤️ Support ScriptureFlow

ScriptureFlow exists to make Scripture accessible in every language — especially those that are underrepresented in digital tools and online resources.

We believe that preserving, sharing, and digitizing Scripture in African and indigenous languages is an act of cultural stewardship and faith.

If this mission resonates with you and you would like to help sustain ongoing development, new translation onboarding, and hosting costs, please consider supporting the project:

👉 **GitHub Sponsors:** https://github.com/sponsors/Exnav29

Your support helps:

- Keep ScriptureFlow free for everyone
- Maintain and expand translations (including Twi, Ewe, Ga, Dagbani, and more)
- Ensure African languages continue to live, grow, and remain present in digital spaces
- Support open access Bible study tools for churches, researchers, educators, and developers

Thank you for being part of this mission. 💙

 ---

## 🚀 What’s New in ScriptureFlow

| Feature | Description |
|----------|-------------|
| **Modernized Architecture** | Initial refactor underway to simplify endpoint structure and improve caching. |
| **AI-Ready JSON Schema** | Future updates will introduce an AI-ready JSON schema for natural-language processing and semantic search. |
| **Multilingual Expansion** | Roadmap includes expanded multilingual support, with emphasis on underrepresented translations. |
| **CDN-Optimized Access** | Delivered globally via jsDelivr CDN; future versions will add structured versioning for releases. |
| **Community Maintenance** | Actively maintained and open for collaboration. |

---

## 🧩 Change Log & Progress Tracker

This section documents the ongoing development and evolution of **ScriptureFlow** — ensuring transparency and helping contributors follow project milestones.

| Status | Feature / Improvement | Description | Date |
|:-------:|------------------------|--------------|:----:|
| ✅ | **Fork Established** | ScriptureFlow created as an actively maintained continuation of the original Bible-API by Henok Woldesenbet. | Nov 2025 |
| ✅ | **Repository Rebrand** | Updated branding, README, and documentation to reflect new project direction. | Nov 2025 |
| 🛠️ | **Architecture Refactor (Phase 1)** | Simplifying endpoint structure for consistency and performance. | In Progress |
| 🛠️ | **JSON Schema Review** | Designing AI/NLP-ready data model for verse and chapter metadata. | In Progress |
| 🔜 | **Multilingual Expansion** | Adding support for new translations, including underrepresented languages. | Planned |
| 🔜 | **Version Tagging & Releases** | Implementing semantic versioning for future API stability. | Planned |
| 🔜 | **Audio Bible Integration** | Exploring inclusion of high-quality audio verse files via CDN. | Planned |
| 🔜 | **Mobile SDKs** | Early-stage planning for SDKs for Android and iOS. | Planned |

---

📅 **Next Milestone:**  
Release **v0.2.0** — featuring improved directory structure, standardized JSON output, and expanded test coverage.

🧠 **Future Direction:**  
Integration of AI-powered verse clustering, semantic search, and multilingual indexing using modern LLM pipelines.

---

## ⚡ Quick Start

No authentication or API key required. Just call the endpoint:

```bash
https://cdn.jsdelivr.net/gh/scriptureflow/bibles/en-kjv/books/john/chapters/3/verses/16.json
```

### Parameters

- **version** – Bible version (e.g., `en-kjv`, `en-asv`)
- **book** – Book name (e.g., `john`, `genesis`)
- **chapter** – Chapter number
- **verse** – Verse number *(optional for full chapter)*

---

## 📚 Example Usage

### JavaScript
fetch("https://cdn.jsdelivr.net/gh/scriptureflow/bibles/en-asv/books/genesis/chapters/1/verses/1.json")
  .then(res => res.json())
  .then(data => console.log(data.text));

### Python
import requests
r = requests.get("https://cdn.jsdelivr.net/gh/scriptureflow/bibles/en-asv/books/john/chapters/3/verses/16.json")
print(r.json()["text"])

## 💡 Roadmap

- ✅ Core API refactor  
- 🔄 Add multilingual indexing  
- 🧠 AI search + verse clustering  
- 🎧 Audio Bible integration  
- 📱 Mobile SDKs (iOS + Android)

---

## 🤝 Contributing

Contributions are welcome! Whether you’re adding new translations, improving code, or enhancing documentation, open an issue or submit a pull request.

---

## ⚖️ License

Licensed under the [MIT License](LICENSE).  
Original work © Henok Woldesenbet.  
Enhancements and refactor © 2025 Johnathan Lightfoot / ScriptureFlow Project.

---

Crafted with 💙 by the **ScriptureFlow Team** —  
*Where the Word Moves Freely.*

---

---

*ScriptureFlow is maintained by the community and supported by individuals and ministries who believe in open, accessible Scripture for all people. Thank you for helping this work continue.*
