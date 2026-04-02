# Week 46, 2025 — Nov 10–16

> **Key Takeaway:** AI has entered an industrial build-out phase defined by capex intensity, infrastructure control, and vertical integration — Anthropic's $50B datacenter plan, SoftBank rotating out of Nvidia into OpenAI stakes, OpenAI shipping GPT-5.1. Simultaneously, the copyright front opened a new flank in Europe (German court rules against OpenAI), and one of AI's founding figures is spinning out of Meta to bet that LLMs have hit their ceiling. The sector is racing to own the full stack before costs spiral, regulators catch up, or new paradigms emerge.

---

## 📰 News

- **German court rules against OpenAI in copyright case** — Munich regional court found ChatGPT infringed copyright by reproducing German song lyrics; both memorization and output constitute rights exploitation. Forces model builders toward cleaner licensing and stronger anti-memorization techniques. Raises output liability questions in Europe distinct from the US piracy cases. *(Nov 2025)*
- **SoftBank exits Nvidia, pivots to OpenAI and infra bets** — Sold entire ~$5.8B Nvidia stake; proceeds directed toward OpenAI-centric investments and the "Stargate" infrastructure push. Shift from picking GPU winners to owning downstream AI economics. If replicated, more capital chases model/platform stakes rather than infrastructure plays. *(Nov 2025)*
- **Yann LeCun poised to leave Meta to build a world-models startup** — Meta's chief AI scientist reportedly preparing a startup focused on "world models" — systems that learn physical and causal dynamics through simulation, video, or multimodal data. LeCun's stated view: LLMs have reached their limits; next breakthroughs require genuine environmental understanding, not scaled pattern prediction. *(Nov 2025)*
- **Cursor raises $2.3B** — IDE-native AI coding assistant closes another massive round. One of the fastest-growing SaaS startups in history. Signals investor conviction that IDE-native agents are a primary enterprise AI wedge. *(Nov 2025)*
- **Anthropic announces $50B US datacenter plan with Fluidstack** — Multi-site builds in Texas and New York, starting as early as 2026. Designed to secure long-term chip access and reduce external cloud dependency. Anthropic positioning itself as both model developer and infrastructure operator — mirroring hyperscaler strategies. *(Nov 2025)*
- **OpenAI "how it works" interpretability model** — Experimental model aimed at making internals easier to understand. Not state-of-the-art capability; a transparency play to study behavior, errors, and trust in neural networks. *(Nov 2025)*

---

## 🚀 Model / Product Launches

- **OpenAI GPT-5.1** — Adaptive reasoning (less "thinking" spent on easy tasks), 24-hour prompt caching, improved coding, new `apply_patch` and shell tools. Cursor and Warp highlighted as early partners. *(Nov 2025)*

---

## 📄 Research Papers

*(none cited this week)*

---

## 💻 Repos & Code

*(none cited this week)*

---

## 🎥 Videos

*(none this week)*

---

## 💬 Opinion & Analysis

- The German copyright ruling is structurally different from the US cases. US litigation has mostly been about training data piracy; the Munich ruling targets the output itself — what the model reproduces matters, not just what it was trained on. If upheld on appeal, it changes the risk calculus for deploying models in Europe regardless of training data provenance.
- SoftBank's Nvidia exit is a contrarian signal worth watching. SoftBank was one of the most aggressive GPU bulls; rotating that capital into OpenAI application-layer bets implies they think the infrastructure appreciation phase is over and the value capture is moving upstream. That's a meaningful market read from a large-capital actor.
- Yann LeCun leaving Meta (if confirmed) is a legitimacy event for the "beyond LLMs" research direction. His "world models" thesis has been a minority view in the industry — most capex is still flowing into transformer scaling. A well-funded LeCun startup would force the question of whether there are viable alternative paths to general AI.
- Cursor's $2.3B raise reflects the same thesis as the a16z spending data (W40): the highest-value AI application layer is the one closest to where developers produce output. IDE integration means the AI touches code at every stage of creation, not just at query time.
- Anthropic building its own datacenters mirrors the trajectory of every hyperscaler — at sufficient scale, owning infrastructure is cheaper and more strategically defensible than renting it. The question is whether Anthropic can sustain the capital intensity required. Their $70B 2028 projection (W45) is the underwriting assumption for the $50B build.
- GPT-5.1's adaptive reasoning is a meaningful architectural signal: instead of spending maximum compute on every query, the model scales effort to task difficulty. This directly addresses the cost problem of frontier reasoning models and makes them more deployable at consumer price points.

---

**Source:** [The Data Journey — Week 46, 2025](https://thedatajourney.substack.com) by Ivo Bernardo
