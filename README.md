# ***"Computer science is no more about computers than astronomy is about telescopes."*** *Edsger W. Dijkstra*



## ∑ ***▸ Projects, ideas, experiments***

This is my corner on GitHub and here you will find what I build, models, notes, attempts, errors, and everything I need in order to understand better how information works, which is the topic that fascinates me the most.

Much of what is presented here can be summarized by C.A.R. Hoare’s maxim: **"The most important property of a program is whether it accomplishes the intention of its user"**

## ∀ ***▸ Areas of interest***

I move across formal languages, computability, complexity, formal semantics, parallel models of computation, and everything that has a structure rigid enough to be taken apart and put back together, and I am also interested in how information behaves when you look at it through the eyes of physics, energy, limits of computation, dynamics, systems that evolve, and another aspect that matters to me is epistemology, analytic philosophy, and the philosophy of language because it helps to understand the world and to see how formal models connect to meaning and where they stop doing so.



## 𝄞 ***▸ A personal note***

I have been playing music for as long as I can remember, I loved Walter Piston’s beautiful book, and I have always thought that harmonic structures work like formal systems and if you think about it they are not that different from a language or from a model of computation.




## λ ***▸ My projects here on GitHub***

I do not use public repositories very often but whatever is worth putting online is here and this is where you will find the things that I think deserve to be shared, even if they are small, partial, experimental or simply useful to me while I try to understand better what I am working on.


## **▸▸ Md2Arxive** - Markdown to LaTeX Transpiler

**A practical bridge between compiler theory and production code.**

A Markdown-to-LaTeX transpiler written in OCaml, designed to transform academic writing into arXiv-ready submissions. More than a tool, it's a **didactic project** that demonstrates how formal semantics (denotational, axiomatic, operational) apply to real-world compilation.

**What makes it stand out:**
- Formal contracts (`@requires`, `@ensures`, `@invariant`) throughout the codebase
- Hand-written DFA lexer and explicit-state parser
- Global semantic validation (orphan citations, ORCID format, table consistency)
- Comprehensive error recovery with non-fatal diagnostics
- Three formal semantics documented in companion PDFs

A small but complete compiler pipeline showing AST, lexing, parsing, semantic validation, and code generation on an understandable domain.


## **▸▸ Docxwatermarker: Educational case study in rigorous Python engineering**

Replace images inside .docx templates byte-for-byte, preserving layout for per-recipient document personalization (confidentiality stamps, draft markers, watermarks for traceability).

Bridges formal methods with production code: shipped with complete axiomatic + operational semantic specifications, each translated to English and Italian. Code ↔ spec bidirectionally synchronized via annotations (test-verified).

Written in spare time as a case study in rigorous engineering with zero XML manipulation, immutable API, reproducible builds, mypy strict, design-by-contract preconditions/postconditions.

Educational framework for rigorous software engineering, embedded in a practical tool.

Features:
- Formal Semantics: axiomatic (Hoare triples, total correctness) + operational
- Specification Cross-Reference Pattern: code ↔ spec bidirectional sync via annotations
- Immutable API (MappingProxyType, factory patterns, chaining)
- Reproducible byte-identical builds (DOS-min timestamps)
- Marker detection via PNG tEXt metadata (zero-config)
- Structured JSON-serializable errors
- mypy strict + ruff + 300+ test assertions
- 4 formal PDFs (EN + IT): axiomatic semantics, operational semantics, study guide
- Design-by-contract (require/ensure split)
- Hoare logic + operational semantics + total correctness proofs



## ⊘ ***▸ Licenses ▸***

Everything you find here is released under **free** licenses



## ***▸ Acknowledgements for ideas***

The theoretical content, proofs, and implementation described in these files are the authors' original work. Where present, all scientific claims and conceptual contributions are solely attributable to the authors. AI‑assisted tools were used only for non‑creative support tasks such as bibliographic cross‑checking and citation verification; advanced debugging assistance; compilation and consistency checks; language revision of non‑native English prose; and rephrasing of inline code comments for clarity, without altering technical content or algorithmic intent. Some portions of the text were translated by the authors themselves, and certain English passages were intentionally left in their original, author‑written form without AI revision. No AI tool contributed to the mathematical results, the algorithmic design, the ideas, or the scientific claims where present.

This statement applies to all repositories under this account, unless otherwise indicated.




