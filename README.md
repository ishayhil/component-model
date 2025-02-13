# Component Model design and specification

This repository describes the high-level [goals], [use cases], [design choices]
and [FAQ] of the component model as well as a more-detailed [explainer], [IDL],
[binary format] and [ABI] covering the initial Minimum Viable Product (MVP)
release.

In the future, this repository will additionally contain a [formal spec],
reference interpreter and test suite.

## Milestones

The Component Model is being incrementally developed and stabilized as part of
the overall [WASI preview process]. The current contents of this repo reflect
the "Preview 2" milestone. The "Preview 3" milestone will be primarily
concerned with the addition of [async support].

## Contributing

All Component Model work is done as part of the [W3C WebAssembly Community Group].
To contribute to any of these repositories, see the Community Group's
[Contributing Guidelines].


[goals]: design/high-level/Goals.md
[use cases]: design/high-level/UseCases.md
[design choices]: design/high-level/Choices.md
[FAQ]: design/high-level/FAQ.md
[explainer]: design/mvp/Explainer.md
[IDL]: design/mvp/WIT.md
[binary format]: design/mvp/Binary.md
[ABI]: design/mvp/CanonicalABI.md
[formal spec]: spec/
[W3C WebAssembly Community Group]: https://www.w3.org/community/webassembly/
[Contributing Guidelines]: https://webassembly.org/community/contributing/
[WASI preview process]: https://github.com/WebAssembly/meetings/blob/main/wasi/2023/presentations/2023-02-09-gohman-wasi-roadmap.pdf
[Async Support]: https://docs.google.com/presentation/d/1MNVOZ8hdofO3tI0szg_i-Yoy0N2QPU2C--LzVuoGSlE/edit?usp=share_link
