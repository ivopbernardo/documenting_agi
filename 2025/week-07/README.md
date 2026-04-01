# Week 7, 2025 — Feb 10–14

> **Key Takeaway:** The reasoning model race accelerated with o3-mini, but the real story was about *less being more*: LIMO showed frontier reasoning can emerge from 817 training samples, and the Anthropic Economic Index confirmed coding tasks dominate real-world AI usage. OpenAI framed all of this under an "Intelligence Age" narrative while quietly pushing policy responsibility onto governments.

---

## 📰 News

- **Paris AI Summit: 5 key takeaways** — Global gathering of leaders, policymakers, and researchers. Themes: AI governance/ethics regulation, global AI race geopolitics, AI in creative fields, sustainability/energy concerns, and workforce displacement/reskilling. *(Feb 2025)*
- **Anthropic Economic Index launched** — First major data-driven report on AI adoption by industry. Top findings: coding/software tasks are the #1 use case; Finance and Healthcare lead in investment; Manufacturing adopts AI for process optimization. *(Feb 2025)*
- **"Is AI Making Us Dumber?" debate** — TechCrunch piece argues overreliance on AI may erode critical thinking, problem-solving, and creativity. Ivo's note: visible in university settings — AI amplifies both resourcefulness and laziness. *(Feb 2025)*
- **OpenAI frames "The Intelligence Age"** — During o3-mini launch, OpenAI positioned reasoning models as the foundation of the Intelligence Age, while implicitly leaving regulation and economic disruption to policymakers. *(Feb 2025)*

---

## 🚀 Model / Product Launches

- **[OpenAI o3-mini](https://openai.com/o3-mini)** — Compact reasoning model targeting DeepSeek's capabilities. Balances speed and accuracy; aimed at enterprise applications. Designed to close performance gaps in specialized reasoning at efficient compute cost. *(Feb 2025)*

---

## 📄 Research Papers

- **[LIMO: Less is More for Reasoning](https://github.com/GAIR-NLP/LIMO)** — Ye, Huang, Xiao, Chern, Xia, Liu. Key finding: sophisticated reasoning can emerge from just 817 carefully curated training samples. Achieves 57.1% on AIME and 94.8% on MATH benchmarks. Outperforms models trained on 100× more data on out-of-distribution tasks. Introduces the *Less-Is-More Reasoning Hypothesis*: pre-training knowledge + minimal precise examples > massive supervised datasets. Challenges the assumption that SFT leads to memorization over generalization. *(Feb 2025)*

---

## 💻 Repos & Code

- **[GAIR-NLP/LIMO](https://github.com/GAIR-NLP/LIMO)** — Code and data for the LIMO reasoning paper. 817-sample training set that beats 100× larger datasets on math reasoning benchmarks.

---

## 🎥 Videos

- **[Jensen Huang interviewed by Cleo Abram](https://www.youtube.com/watch?v=toHuABiAECs)** — NVIDIA CEO on: generative AI's impact on productivity, hardware optimization for AI workloads, enterprise AI adoption at scale, and responsible AI development. *(Feb 2025)*

---

## 💬 Opinion & Analysis

- LIMO's result is arguably more significant than another benchmark win — it suggests the bottleneck for reasoning may be *data quality*, not scale. If true, the compute arms race assumptions need revisiting.
- The Anthropic Economic Index has an inherent selection bias (Claude users only), but it's a start — more cross-model usage reports are needed for the field to understand real adoption patterns.
- OpenAI's "Intelligence Age" framing is a strategic narrative move: claim the epoch, define the terms, defer the hard questions on regulation.

---

**Source:** [The Data Journey — Week 7, 2025](https://thedatajourney.substack.com) by Ivo Bernardo
