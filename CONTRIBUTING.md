# Contributing

Contributions to the **Sri Amit Ray Compassion AI Architecture™ (CAIA™)** and the 25 Human-Centered Compassionate AI (HC-CAI) algorithm documents it governs are welcome — corrections, clearer explanations, additional worked examples, real-world case studies, or reference implementations.

## Guidelines

1. Each algorithm's document lives in `docs/algorithms/` and follows a consistent structure: intro and placement within the Compassion AI Architecture (CAIA™), project goals, mathematical model, algorithmic implementation, repository structure, installation/usage, applications, datasets, testing protocols, limitations, standards and governance mapping, misuse and dual-use safeguards, ethical principles, and references. Algorithms 04 (PRPA), 05 (HFOA), and 06 (RIM) predate this template and intentionally omit the CAIA/SDG/Standards/Misuse sections — do not retrofit them with invented layer, SDG, or governance claims.
2. Keep all 25 files in the same flat `docs/algorithms/` folder — the "Related Algorithms" cross-links between files depend on this and will break if files are moved into per-algorithm subfolders without updating every link.
3. Preserve the CAIA™ layer/score framing in each file's introduction and "Place in the CAIA" section — it should match the architecture summarized in `docs/architecture/Sri-Amit-Ray-CAIA-Overview.md`. If you change a layer assignment, update `Sri-Amit-Ray-CAIA-Overview.md` (and the root `README.md` layer table) in the same pull request.
4. If you add or change an "Advancing the UN Sustainable Development Goals" section, update `docs/architecture/Sri-Amit-Ray-CAIA-SDG-Mapping.md` to match in the same pull request.
5. If you add or change an "Ethical and Design Principles" / "Ethical Dimension" section, update `docs/architecture/Sri-Amit-Ray-CAIA-Principles.md` to match in the same pull request.
6. If you add or change a "Standards and Governance Mapping" or "Misuse and Dual-Use Safeguards" section, update `docs/architecture/Sri-Amit-Ray-CAIA-Governance.md` to match in the same pull request.
7. Cite sources for any new claims. Do not add unsupported claims to the Applications, Real-World Use Cases, or Standards sections.
8. Only add a file to `papers/` if it is a real, verified paper — replace its `TBD` row in `papers/README.md` rather than adding placeholder links elsewhere.
9. Open a pull request describing which algorithm(s) or document(s) you changed and why.

## Reporting Issues

Open an issue describing the document, the section, and the specific problem (factual error, broken link, unclear explanation, etc.).
