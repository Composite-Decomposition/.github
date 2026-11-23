# Welcome to this Organization 👋

**Composite Decomposition** is an open-source organization exploring hard concepts in
computer science, software engineering, and AI engineering — decomposing them along
their tensions, then recomposing them with their relationships intact.

In the era of AI, generating isolated code fragments or quick answers is trivial. The
differentiator is systems thinking: understanding how parts relate to the whole, and
how context gives meaning to complexity.

Great engineering is the economic balancing of tension between external forces, a
unified whole, and its constituent parts. A concept that remains an undivided block is
too rigid to reuse or grasp deeply. But broken apart blindly, it loses the relationships
that make it work, and the result is one-sided and misleading.

We call this **composite decomposition**: a Hegelian movement of thought in four steps.

• **The One-Sided Concept** — begin with a difficult idea that is commonly misunderstood
  because pertinent relationships have been dropped from mainstream explanations.
  
• **Mental Pictures** — build intuition through clear abstractions and analogies; see
  the shape of the problem before touching implementation.
  
• **Dissection Through Tension** — apply opposing positive and negative forces,
  questioning and testing, to split the concept into its constituent parts and expose
  hidden dependencies.
  
• **The Enriched Return** — recompose the pieces at a higher level, either by placing
  the original concept in a deeply enriched context or by applying it in a profoundly
  new way.

We don't publish shallow tutorials or concrete how-tos. Every deep dive is grounded in
practice and paired with open-source proofs of concept built in the open.

---

## Featured Project: Intentional Links

Standard link checkers validate transport status (`HTTP 200 OK`), not semantics. That
leaves technical documentation vulnerable to silent **content drift**, where an external
page redirects to a generic landing page or changes topic while still returning 200.

**[Intentional Links](https://github.com/Composite-Decomposition/intentional-links)** is
an open, language-agnostic specification, designed as a backward-compatible extension of
the [Robust Links](https://robustlinks.org/spec/) specification. No existing markup is
invalidated.

Two declarative HTML attributes enable build-time evaluators to verify that a live target
still satisfies the author's original semantic intent:

• `data-intention` states what the target resource must actually convey.

• `data-action` (`keep-live`, `unlink`, `switch-to-snapshot`, `switch-to-robust`)
  determines how a compliant evaluator repairs the anchor when drift is detected.

Detection itself is implementation-defined: embeddings, LLM adjudication, structural
checks, or heuristics. The specification standardizes the contract and the remediation
protocol, not the oracle.

The repository is deliberately not a single executable tool. It is the canonical hub for
the standard: RFCs, architectural edge cases, and a registry of community-built
evaluators across ecosystems (CLI tools, GitHub Actions, static site generator plugins).

---

### Collaborating & Contributing

We advocate for sustainable open-source software and welcome a range of perspectives.

• **Specification questions and design proposals:** open an issue 
  in [intentional-links](https://github.com/Composite-Decomposition/intentional-links).
  
• **Implementations:** evaluators in any language or ecosystem are welcome; open an issue
  to have yours registered.
  
• **Corrections and prior art:** if you know of earlier work we should be citing, please
  tell us. See the Related Work section of the spec.

---

## Further Explorations

Long-form essays and visual walkthroughs behind these projects:

* **YouTube:** [@composite-decomposition](https://www.youtube.com/@composite-decomposition)
* **Blog:** [https://blog.ErvinVarga.com](https://blog.ErvinVarga.com)
