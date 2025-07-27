
# Static (Assertion) vs Dynamic (Discovery) Taxonomies in Toxic Speech

## Assertion-Based Categories: The Static Approach

Traditional content moderation often relies on **asserted, fixed categories** (e.g. *hate speech*, *harassment*). These are top-down definitions created by platform policies or legal frameworks.

- **Concept drift**: As language and context evolve, these fixed definitions become outdated. For example, adversaries may create new slurs to evade detection.
- **Policy maintenance**: Requires manual and frequent updates to keep pace with real-world changes.
- **Example-based rules**: Definitions often rely on example cases rather than comprehensive frameworks, leading to inconsistent enforcement.

## Discovery-Based Categories: Data-Driven Approaches

**Discovery-based approaches** use machine learning, especially unsupervised methods, to identify emerging patterns in toxic speech without predefined labels.

- **Clustering and topic modeling**: Finds natural groupings in data. For example, toxic behavior in *StarCraft II* revealed a 10th category ("friendly fire") that was not initially included.
- **Adaptive lexicons**: Embedding-based techniques dynamically update hate-speech dictionaries to include new variants.
- **Prompt-based moderation**: Platforms like LinkedIn use question-answering models with updated prompts for flexible content categorization.

## Case Studies and Industry Trends

- **StarCraft II Ethnography**: Discovered nuanced categories of toxicity through interviews and behavior analysis.
- **LinkedIn QA System**: Uses binary prompts to detect evolving hate speech and spam.
- **OpenAI & Jigsaw**: Combine LLMs and self-supervised techniques for dynamic policy enforcement.
- **Community blocklists**: User-generated term lists serve as informal discovery systems.

## Governance Implications

- **Dynamic monitoring**: Regular clustering to surface emerging harmful trends.
- **Modular policies**: Break content rules into evolving sub-categories.
- **Hybrid systems**: Combine top-down assertions with bottom-up discovery.
- **Transparency and trust**: Document and explain policy changes.

## Summary

Static, assertion-based models are brittle and struggle to evolve. Discovery-based models, grounded in actual data and behavior, offer a more accurate and adaptable representation of toxic speech online. Effective governance should embrace both, updating policies based on ongoing analysis.

---

*Sources include: studies on toxic speech detection, content moderation evolution, and platform policy analysis from academic and industry research (2023–2025).*

AI conversation that led to this document:
https://chatgpt.com/share/6885c36e-5f44-8008-9d54-7a673a8e997f