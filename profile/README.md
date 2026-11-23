# Composite Decomposition 👋

**Systems thinking in CS, software, and AI engineering. Building understanding by showcasing concepts in action.**

Composite Decomposition is an open-source engineering organization focused on how constituent parts relate to the whole—and how context gives meaning to complexity.

In an era where generating isolated fragments of code is trivial, the real differentiator is architectural clarity. When systems or concepts are broken apart blindly, vital relationships are severed, leading to fragile abstractions and one-sided solutions. Here, we dissect hard technical problems, expose hidden dependencies, and build open specifications and concrete Proofs of Concept that bring the pieces back together at a higher, enriched level.

---

### Featured Project: Intentional Links

Standard link checkers validate transport syntax (`HTTP 200 OK`), not semantics—leaving technical documentation vulnerable to silent **content drift** when external pages redirect or change topic.

**[intentional-links](https://github.com/Composite-Decomposition/intentional-links)** is an open, language-agnostic specification designed as a strictly backward-compatible extension of the [Robust Links Specification](https://robustlinks.org/spec/).

By introducing two declarative HTML attributes (`data-intention` and `data-action`), the specification enables asynchronous, build-time evaluators to verify that a live target page still satisfies the author's original semantic intent. When drift occurs, compliant evaluators deterministically heal the DOM using Web Archive snapshots.

Rather than housing a single executable tool, the `intentional-links` repository serves as the canonical hub for the standard itself—hosting RFCs, documenting architectural edge cases, and registering community-built evaluators across different ecosystems (CLI tools, GitHub Actions, and Static Site Generator plugins).

---

### Collaborating & Contributing

We strongly advocate for the creation of sustainable open-source software and components. Our community actively encourages a diverse range of perspectives, feedback, and collaborative proposals that resonate with our overarching mission.

---

### Further Explorations

The mental models and architectural breakdowns behind these projects are also published through long-form essays and visual walkthroughs:

* **YouTube:** [@composite-decomposition](https://www.youtube.com/@composite-decomposition)
* **Blog:** [https://blog.ErvinVarga.com](https://blog.ErvinVarga.com)
