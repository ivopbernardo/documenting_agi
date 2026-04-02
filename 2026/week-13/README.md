# Week 13, 2026 — Mar 23–29

> **Key Takeaway:** Sora's shutdown is the week's most important business model lesson: $1M/day in compute costs against $2.1M in total lifetime revenue is not a product, it's a demonstration. The Disney deal died one hour before the public announcement. Meanwhile, Sakana's AI Scientist passed peer review at Nature — autonomous AI completing the full research cycle is no longer hypothetical. And a supply chain attack on litellm shows that the AI developer toolchain is now an active attack surface.

---

## 📰 News

- **OpenAI shuts down Sora video app** — Closed March 24, six months after launch, one week after shipping new editing features. Reason confirmed by WSJ: unsustainable compute costs (~$1M/day), collapsing user base, pressure to free chips ahead of a possible IPO. Disney's $1B partnership deal died with it — Disney found out one hour before the public announcement. Sora total lifetime in-app revenue: $2.1M. *(Mar 2026)*
- **Cursor's "Composer 2" built on Moonshot AI's Kimi k2.5** — Launched as "frontier-level coding intelligence" without disclosing it was built on Kimi k2.5, a Chinese open-source model backed by Alibaba. Disclosure failure surfaced publicly; raises questions about model provenance transparency in developer tools. *(Mar 2026)*
- **LiteLLM supply chain attack** — Malicious file embedded in litellm==1.82.8 auto-executes a credential-stealing script on Python startup. Payload collects SSH keys, AWS/GCP/Azure credentials, environment variables, crypto wallets, shell history — exfiltrated encrypted to attacker server. Critical security disclosure for AI developers using the package. *(Mar 2026)*
- **Meta AI shopping features at Shoptalk 2026** — AI-powered shopping for Instagram and Facebook; expanded affiliate partnerships with Amazon, eBay, and Temu for creators. *(Mar 2026)*

---

## 🚀 Model / Product Launches

- **Mistral Voxtral TTS** — Open-source text-to-speech model. 9 languages (including Portuguese), voice cloning from under 5 seconds of audio, runs on edge devices as small as a smartwatch. Strong edge deployment story. *(Mar 2026)*

---

## 📄 Research Papers

- **Sakana AI "AI Scientist" published in Nature** — Autonomous research tool handling the full cycle from hypothesis to peer-reviewed paper. At ICLR 2025 controlled experiment: submitted three AI-generated papers; one was accepted by reviewers who knew some submissions might be AI-generated. Publication in Nature after peer review is the landmark: AI-generated research is now in the scientific record. *(Mar 2026)*

---

## 💻 Repos & Code

- **LiteLLM supply chain attack disclosure** — [GitHub issue](https://github.com/BerriAI/litellm) for litellm==1.82.8. AI developers using this package should audit immediately.

---

## 🎥 Videos

*(none this week)*

---

## 💬 Opinion & Analysis

- Sora's shutdown is the first major AI product failure at scale in this archive, and the unit economics make it instructive: $1M/day compute vs $2.1M lifetime revenue is a 99.8% loss ratio. The product was technically impressive (W40 2025 launch, W48 improvements) but never found a revenue model. Generative video is real; a sustainable consumer generative video business is much harder. Runway (W50 2025) and the remaining players now compete in a field with one fewer major entrant.
- The Cursor/Kimi k2.5 non-disclosure is a transparency failure that matters beyond the specific incident. Developers and enterprises choosing AI coding tools are implicitly making decisions about which model supply chains they trust, which jurisdictions they operate in, and what data their code is processed by. "Frontier-level coding intelligence" built on a Chinese model without disclosure is a provenance and governance problem, not just a PR problem.
- The litellm supply chain attack is the clearest realisation yet of the W47 2025 Claude cyberattack vector: the AI developer toolchain is an active, high-value attack surface. litellm is used by thousands of AI developers for model routing — a single malicious package version can harvest credentials from every project that upgrades. The W43 2025 clipboard injection warning was browser-level; this is deeper.
- Sakana's AI Scientist passing Nature peer review is a more significant milestone than the ICLR controlled experiment. Nature peer review is not a push-button process — it involves multiple rounds of expert scrutiny. An AI-generated paper surviving that process, even one, means the scientific community's quality filters are not yet reliably detecting AI authorship. That has implications for research integrity far beyond any single paper.
- Voxtral TTS running voice cloning from 5 seconds of audio on a smartwatch is the convergence of two trends: Mistral's edge deployment strategy (W48 2025) and ElevenLabs' foundational voice position (W05 2026). The barriers to synthetic voice are now near-zero in terms of hardware requirements. The deepfake audio concerns that flagged xAI's Grok in W02 apply at smartwatch scale.

---

**Source:** [The Data Journey — Week 13, 2026](https://thedatajourney.substack.com) by Ivo Bernardo
