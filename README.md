# 🌿 Shamba Scan AI

Swahili-native crop disease detection — upload a leaf photo, get a diagnosis and treatment steps in Swahili, grounded in the PlantVillage dataset.

Upload a photo of a diseased plant leaf → AI diagnosis in Swahili → treatment guidance → prevention.

## Research Basis
- Mohanty et al. (2016) — *"Using Deep Learning for Image-Based Plant Disease Detection"* arXiv:1604.03169
  - PlantVillage dataset: 54,306 images, 14 crops, 26 diseases. 99.35% accuracy on held-out test set.
- Dolatabadian (2025) — Image-based crop disease detection using machine learning. *Plant Pathology*, Wiley.
- Springer Nature (2026) — Comprehensive AI plant disease review including African crop systems.

## Why East Africa
Kenya loses an estimated **14.1% of annual crop yield** to disease — matching the global average but hitting harder
because extension officers are scarce (1 per 3,000+ farmers in some counties). Smartphone penetration
crossed 50% in Kenya in 2024. This closes the gap.

## Novelty
No prior deployable Swahili-language crop disease detection app exists in Kenya or East Africa.
Existing tools (PlantVillage app, Nuru app) are English-only and require app installation.
This is Swahili-first, mobile-optimized, and zero-install.

## Stack
- Gemini Vision (gemini-2.0-flash) — multimodal image analysis
- Streamlit — zero-install mobile-first deployment
- MIT License · DEMO data clearly labeled

## Disclaimer
Educational demonstration. Not a substitute for professional agricultural extension advice.
For certified diagnosis: contact your local KALRO office.

---
*© 2026 Gabriel Mahia / AI Kung Fu LLC · [gabrielmahia.github.io](https://gabrielmahia.github.io)*

## IP & Collaboration

MIT licensed. Feedback via GitHub Issues only — pull requests are not accepted. Full policy: [docs/architecture/IP_POLICY.md](docs/architecture/IP_POLICY.md). Security reports: see [SECURITY.md](SECURITY.md).
