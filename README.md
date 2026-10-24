<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Wentao Tong — Computer vision, Python infrastructure, and local AI" width="100%">
</picture>

<p align="center">
  <strong>17 merged PRs</strong> &nbsp; / &nbsp; <strong>10 upstream projects</strong> &nbsp; / &nbsp; <strong>4 with 10k+ stars</strong>
</p>

I build practical tools for **computer vision**, **local AI**, and **Python developers**. My open-source work focuses on performance, reliable data handling, and regression tests that protect real workflows.

Graduate student at **Zhejiang University of Science and Technology**, Hangzhou.

[Merged work](https://github.com/search?q=author%3Atongwentao+is%3Apr+is%3Amerged&type=pullrequests) · [My projects](https://github.com/tongwentao?tab=repositories) · [Contribution history](https://github.com/search?q=author%3Atongwentao+is%3Apr&type=pullrequests)

## Accepted upstream

Selected contributions merged into established open-source projects. Each link leads to the accepted change.

| Project | Selected work |
| :--- | :--- |
| **[Labelme](https://github.com/wkentaro/labelme)** · 5 merged | **Image performance & annotation workflows.** [Avoid full-image copying and hashing](https://github.com/wkentaro/labelme/pull/2741), [reject oversized images before pixel decoding](https://github.com/wkentaro/labelme/pull/2750), and [double-click Shapes to edit Labels](https://github.com/wkentaro/labelme/pull/2744). |
| **[Kornia](https://github.com/kornia/kornia)** · 3 merged | **Type compatibility & actionable errors.** [Accept integer-valued colormaps while preserving floating dtype behavior](https://github.com/kornia/kornia/pull/6172); explain [unsupported Dissolving versions](https://github.com/kornia/kornia/pull/6202) and [VisualPrompter configurations](https://github.com/kornia/kornia/pull/6211). |
| **[Supervision](https://github.com/roboflow/supervision)** | **Dataset export reliability.** [Raise an error when an image cannot be written](https://github.com/roboflow/supervision/pull/2772), rather than returning as though export succeeded. |
| **[fsspec](https://github.com/fsspec/filesystem_spec)** · 2 merged | **Filesystem compatibility.** [Accept standard binary update-mode aliases](https://github.com/fsspec/filesystem_spec/pull/2347) and [correct the FUSE CLI foreground option](https://github.com/fsspec/filesystem_spec/pull/2352). |
| **[Datumaro](https://github.com/open-edge-platform/datumaro)** | **CLI diagnostics.** [Explain missing optional dependencies before loading commands](https://github.com/open-edge-platform/datumaro/pull/2223). |
| **[Pydantic](https://github.com/pydantic/pydantic)** | **API documentation.** [Unify the serialization-method docstrings in `TypeAdapter`](https://github.com/pydantic/pydantic/pull/14037). |

Also contributed to **[Mistune](https://github.com/lepture/mistune/pull/516)**, **[Bracex](https://github.com/facelessuser/bracex/pull/52)**, **[Unbagged](https://github.com/jdmacleod/unbagged/pull/143)**, and **[CatGPT-Gateway](https://github.com/GautamVhavle/CatGPT-Gateway/pull/20)**.

<details>
<summary><strong>Explore all 17 merged contributions</strong></summary>

| Project | Contribution |
| :--- | :--- |
| Labelme | [#2741 · Avoid image-array copying and hashing during loading](https://github.com/wkentaro/labelme/pull/2741) |
| Labelme | [#2750 · Stop oversized images before pixel decoding](https://github.com/wkentaro/labelme/pull/2750) |
| Labelme | [#2744 · Double-click a Shape to edit its Label](https://github.com/wkentaro/labelme/pull/2744) |
| Labelme | [#2817 · Test linestrip hover and point insertion through real Qt events](https://github.com/wkentaro/labelme/pull/2817) |
| Labelme | [#2748 · Remove an unused Twine development dependency](https://github.com/wkentaro/labelme/pull/2748) |
| Kornia | [#6172 · Support integer-valued custom colormap bases](https://github.com/kornia/kornia/pull/6172) |
| Kornia | [#6202 · Explain unsupported Dissolving versions](https://github.com/kornia/kornia/pull/6202) |
| Kornia | [#6211 · Explain unsupported VisualPrompter configurations](https://github.com/kornia/kornia/pull/6211) |
| Supervision | [#2772 · Surface image-writing failures during dataset export](https://github.com/roboflow/supervision/pull/2772) |
| fsspec | [#2347 · Accept standard binary update-mode aliases](https://github.com/fsspec/filesystem_spec/pull/2347) |
| fsspec | [#2352 · Fix the FUSE foreground option](https://github.com/fsspec/filesystem_spec/pull/2352) |
| Datumaro | [#2223 · Diagnose missing optional CLI dependencies](https://github.com/open-edge-platform/datumaro/pull/2223) |
| Pydantic | [#14037 · Unify `TypeAdapter` serialization documentation](https://github.com/pydantic/pydantic/pull/14037) |
| Mistune | [#516 · Handle fence metadata in the highlighting example](https://github.com/lepture/mistune/pull/516) |
| Bracex | [#52 · Include documentation build inputs in source distributions](https://github.com/facelessuser/bracex/pull/52) |
| Unbagged | [#143 · Generate a complete Albertsons sample upload](https://github.com/jdmacleod/unbagged/pull/143) |
| CatGPT-Gateway | [#20 · Concurrent tabs, persistent sessions, and SSE streaming](https://github.com/GautamVhavle/CatGPT-Gateway/pull/20) |

</details>

<sub>Contribution and popularity snapshot: October 24, 2026. Counts refer to accepted PRs, not pending submissions. The four 10k+ star projects are Supervision, Pydantic, Labelme, and Kornia.</sub>

## Things I've built

| Project | What it does |
| :--- | :--- |
| **[WebLLM Pro](https://github.com/tongwentao/Web_LLM)** | Run LLMs in the browser with **WebGPU**, local model caching, persistent conversations, and Markdown rendering. Built with JavaScript and WebLLM. |
| **[Codeforces Analytics](https://github.com/tongwentao/codeforces-analytics-extension)** | A **Manifest V3** browser extension with interactive problem-solving analytics and high-resolution chart export. Built with JavaScript and ECharts. *Archived.* |

## Working toolkit

**Vision & data** &nbsp; Python · PyTorch · NumPy · Qt<br>
**Browser & local AI** &nbsp; JavaScript · WebGPU · WebLLM<br>
**Engineering** &nbsp; pytest · Git · GitHub Actions
