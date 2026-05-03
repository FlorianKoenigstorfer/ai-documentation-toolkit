# AI Act Documentation Toolkit

A practical toolkit for documenting Artificial Intelligence (AI) applications under the EU AI Act and in regulated industries more broadly. The repository contains an audit-validated documentation guideline, a cover sheet template, and the five peer-reviewed papers behind them.

The work addresses a gap that organisations face when adopting AI in regulated environments: traditional software documentation does not capture the data, design decisions, governance, and integration concerns that auditors, regulators, and practitioners need in order to verify that an AI system is fair, accountable, transparent, and compliant. The papers in this repository trace that problem from interviews with practitioners through to a concrete, validated guideline that compliance officers, AI developers, and auditors can use today.

## Author

**Florian Königstorfer** — [Google Scholar profile](https://scholar.google.com/citations?user=naV-pgoAAAAJ&hl=en&oi=ao)

Of these papers:
.) One was authored only by Florian Königstorfer.
.) Two were authored by Florian Königstorfer and Stefan Thalmann.
.) One was authored by Florian Königstorfer, Felix Krieger and Stefan Thalmann.
.) one was authored by Florian Königstorfer, Armin Haberl, Dominik Kowald, Tony Ross-Hellauer and Stefan Thalmann.

## Contents

### Templates

- **`Guideline_Template.xlsx`** — The validated AI documentation guideline. Contains 106 questions across four sections: Application Domain (24), Data (46), Design Decisions (27), and IT/AI Governance (9).
- **`Cover_Sheet_Template.pdf`** — A short cover sheet that introduces the AI application, its risk classification under the EU AI Act, the data it processes, and the goal of the documentation. Designed to sit on top of a completed guideline.

### Papers

1. **Software documentation is not enough! Requirements for the documentation of AI** (2021)
   *Digital Policy, Regulation and Governance*
   An interview study with 16 senior practitioners that identifies five concrete requirements for AI documentation: description of the application domain, description of the training data, description of design decisions, understandability for knowledgeable third parties, and a workable balance between effort and benefit.

2. **AI Documentation: A path to accountability** (2022)
   *Journal of Responsible Technology*
   An interview study showing how the risk level of an AI use case and the level of AI adoption together shape how organisations document AI. Introduces four practitioner archetypes (cautious non-adopters, relaxed adopters, prepared adopters, unexcited non-adopters) and explains why missing documentation guidelines are themselves an adoption barrier.

3. **A Comprehensive Review of Techniques for Documenting Artificial Intelligence** (2024)
   A structured literature review of 38 papers across information systems, medicine, and fair/accountable/transparent AI venues. Maps existing documentation methods against regulatory and industry requirements and identifies three open research directions: comprehensive guideline design, documenting evolving AI (pre-trained, retrained, generative), and automatic documentation.

4. **Bridging AI Development and Compliance: Design Principles for the Documentation of AI** (2024)
   *ECIS 2024*
   The design science study that develops and validates the documentation guideline included in this repository, plus four design principles: (1) flexibility to adapt to specific contexts, (2) re-use of existing evidence, (3) clear documentation processes, and (4) linking the documentation to system evidence.

5. **Black Box or Open Science? A Study On Reproducibility In AI Development Papers** (2024)
   *HICSS 2024*
   An assessment of 51 AI development papers across information systems, computer science, and medicine using an extended reproducibility framework. Finds that most reviewed papers fall short on reproducibility because of insufficient documentation of training data, source code, and AI models.

## How the papers connect

The five papers form a coherent research arc:

- Papers 1 and 2 establish, through interviews with practitioners, what AI documentation actually needs to contain and why current practice falls short.
- Paper 3 surveys the existing documentation techniques and shows that no single method covers the full set of requirements.
- Paper 4 builds and evaluates a guideline that does, plus the design principles behind it.
- Paper 5 demonstrates, through an empirical review of published AI research, that the documentation problem extends well beyond industry into the scientific literature itself.

## Using the guideline

The guideline in `Guideline_Template.xlsx` is intended to be used together with the cover sheet. A typical workflow:

1. Fill in the cover sheet to capture the basic facts about the AI application, its risk classification under the EU AI Act, the data it processes, and the intended audience for the documentation.
2. Work through the four sections of the guideline. Not every question applies to every use case — the design principles in Paper 4 explicitly support adapting the guideline to context, re-using existing audit evidence (e.g., cloud platform certifications, certifications for upstream components), and linking answers to system evidence (logs, code, training artefacts) wherever possible.
3. Treat documentation as part of the development process rather than something written at the end. Paper 4 found that retroactive documentation is a frequent source of error and gaps.

The guideline has been validated by an AI auditor at a large international audit firm and applied in two industry use cases (audit and pharmaceutical quality control).

## Related work

For background on where AI is applied across the core business areas of commercial banks, see the companion repository [Applications-of-Artificial-Intelligence-in-commercial-banks-A-research-agenda-for-behavioral-finance](https://github.com/FlorianKoenigstorfer/Applications-of-Artificial-Intelligence-in-commercial-banks-A-research-agenda-for-behavioral-finance).

## References

Königstorfer, F., & Thalmann, S. (2022). AI Documentation: A path to accountability. Journal of Responsible Technology, 11, 100043.

Königstorfer, F., & Thalmann, S. (2021). Software documentation is not enough! Requirements for the documentation of AI. Digital Policy, Regulation and Governance, 23(5), 475-488.

Königstorfer, F. (2024). A comprehensive review of techniques for documenting artificial intelligence. Digital Policy, Regulation and Governance, 26(5), 545-559.

Königstorfer, F., Haberl, A., Kowald, D., Ross-Hellauer, T., & Thalmann, S. (2024). Black box or open science? A study on reproducibility in AI development papers. In Proceedings of The Hawaii International Conference on System Sciences, HICSS (Vol. 24).

Koenigstorfer, F., Krieger, F. F. A., & Thalmann, S. (2024). Bridging AI Development and Compliance: Design Principles for the Documentation of AI.


If you use the guideline, the cover sheet, or any of the papers in academic work, please cite the corresponding publication. BibTeX entries can be retrieved from the [Google Scholar profile](https://scholar.google.com/citations?user=naV-pgoAAAAJ&hl=en&oi=ao) linked above or from the publishers' websites.

## Licence

The PDFs in this repository are subject to the copyright of their respective publishers (Emerald, Elsevier, AIS, IEEE/HICSS). They are included here in the form permitted by each publisher's author self-archiving policy. Please consult the original publication for licensing terms before redistributing.

## Contact

For questions about the research or the templates, please open an issue on this repository or reach out via E-Mail to florian.koenigstorfer.fr@gmail.com .
