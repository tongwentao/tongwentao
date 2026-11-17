<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Wentao Tong — Computer vision, Python infrastructure, and local AI" width="100%">
</picture>

<p align="center">
  <strong>40 merged PRs</strong> &nbsp; / &nbsp; <strong>24 upstream projects</strong> &nbsp; / &nbsp; <strong>4 with 10k+ stars</strong>
</p>

I build practical tools for **computer vision**, **local AI**, and **Python developers**. My open-source work focuses on performance, reliable data handling, and regression tests that protect real workflows.

Graduate student at **Zhejiang University of Science and Technology**, Hangzhou.

[Merged work](https://github.com/search?q=author%3Atongwentao+is%3Apr+is%3Amerged&type=pullrequests) · [My projects](https://github.com/tongwentao?tab=repositories) · [Contribution history](https://github.com/search?q=author%3Atongwentao+is%3Apr&type=pullrequests)

## Accepted upstream

Selected contributions merged into established open-source projects. Each link leads to the accepted change.

| Project | Selected work |
| :--- | :--- |
| **[Labelme](https://github.com/wkentaro/labelme)** · 12 merged | **Annotation UX, performance & formats.** [Support JPEG 2000 images via Pillow](https://github.com/wkentaro/labelme/pull/2833), [3-point circle drawing](https://github.com/wkentaro/labelme/pull/2788), [location-aware context menus](https://github.com/wkentaro/labelme/pull/2745), [atomic-save directory permissions](https://github.com/wkentaro/labelme/pull/2819), [preserve POSIX mode bits](https://github.com/wkentaro/labelme/pull/2747), [avoid full-image copy & hash](https://github.com/wkentaro/labelme/pull/2741), [reject oversized images before decoding](https://github.com/wkentaro/labelme/pull/2750), and [double-click Shapes to edit Labels](https://github.com/wkentaro/labelme/pull/2744). |
| **[Supervision](https://github.com/roboflow/supervision)** · 2 merged | **Dataset handling & export safety.** [Load YOLO segmentation datasets with compact masks](https://github.com/roboflow/supervision/pull/2834), and [raise an error when an image cannot be written during export](https://github.com/roboflow/supervision/pull/2772). |
| **[Kornia](https://github.com/kornia/kornia)** · 3 merged | **Type compatibility & actionable errors.** [Accept integer-valued colormaps while preserving floating dtype behavior](https://github.com/kornia/kornia/pull/6172); explain [unsupported Dissolving versions](https://github.com/kornia/kornia/pull/6202) and [VisualPrompter configurations](https://github.com/kornia/kornia/pull/6211). |
| **[SAHI](https://github.com/obss/sahi)** · 2 merged | **Slicing Aided Inference & dataset processing.** [Preserve directory and stem names in YOLO label paths](https://github.com/obss/sahi/pull/1480), and [fix category-zero filtering in COCO subsampling](https://github.com/obss/sahi/pull/1479). |
| **[Trimesh](https://github.com/mikedh/trimesh)** | **3D geometry data loading.** [Fix XYZ delimiter column counting and newline-free input](https://github.com/mikedh/trimesh/pull/2635). |
| **[fsspec](https://github.com/fsspec/filesystem_spec)** · 2 merged | **Filesystem compatibility.** [Accept standard binary update-mode aliases](https://github.com/fsspec/filesystem_spec/pull/2347) and [correct the FUSE CLI foreground option](https://github.com/fsspec/filesystem_spec/pull/2352). |
| **[Pydantic](https://github.com/pydantic/pydantic)** | **API documentation.** [Unify serialization-method docstrings in `TypeAdapter`](https://github.com/pydantic/pydantic/pull/14037). |
| **[Python Infrastructure](https://github.com/pytest-dev/iniconfig)** | **Core tooling & developer experience.** [Fix callable positional default overloads in `pytest-dev/iniconfig`](https://github.com/pytest-dev/iniconfig/pull/87), [probe locks with `blocking=False` in `tox-dev/filelock`](https://github.com/tox-dev/filelock/pull/873), [resilient CLI path reporting in `tox-dev/platformdirs`](https://github.com/tox-dev/platformdirs/pull/638), and [explain missing dependencies before loading commands in `Datumaro`](https://github.com/open-edge-platform/datumaro/pull/2223). |

Also contributed to **[Mistune](https://github.com/lepture/mistune/pull/516)**, **[python-humanize](https://github.com/python-humanize/humanize/pull/469)**, **[python-utils](https://github.com/wolph/python-utils/pull/64)**, **[petl](https://github.com/petl-developers/petl/pull/764)**, **[python-ulid](https://github.com/mdomke/python-ulid/pull/68)**, **[cacheout](https://github.com/dgilland/cacheout/pull/49)**, **[click-repl](https://github.com/click-contrib/click-repl/pull/144)**, **[Bracex](https://github.com/facelessuser/bracex/pull/52)**, **[Unbagged](https://github.com/jdmacleod/unbagged/pull/143)**, **[pandora](https://github.com/npechl/pandora/pull/122)**, **[hardcover-mcp](https://github.com/kristianedlund/hardcover-mcp/pull/95)**, **[smart-house-research-toolkit](https://github.com/jddrtn/smart-house-research-toolkit/pull/24)**, and **[CatGPT-Gateway](https://github.com/GautamVhavle/CatGPT-Gateway/pull/20)**.

## Upstream collaboration & maintainer acknowledgements

Several investigations, edge-case mappings, and architectural proposals were adopted or cited by project maintainers when landing foundational upstream fixes:

| Project | Context & Maintainer Recognition |
| :--- | :--- |
| **[wkentaro/labelme](https://github.com/wkentaro/labelme)**<br>*(#2787, #2751, #2743, #2749)* | **Kentaro Wada (@wkentaro)** built multiple upstream features on top of these PRs:<br>• **Unused Label Removal** ([#2787](https://github.com/wkentaro/labelme/pull/2787)): Stacked into [#3047](https://github.com/wkentaro/labelme/pull/3047) and [#3048](https://github.com/wkentaro/labelme/pull/3048): *"Thanks @tongwentao. This work continues in a stack built on it... #3048 ports this PR's removal flow onto the Annotations section with your tests and translations."*<br>• **Missing Image Recovery** ([#2751](https://github.com/wkentaro/labelme/pull/2751)): Merged as [#2964](https://github.com/wkentaro/labelme/pull/2964): *"Thank you for the work here... #2964 keeps your Locate Image dialog and the reader that validates a replacement image."*<br>• **Shape Locking** ([#2743](https://github.com/wkentaro/labelme/pull/2743)): *"Your PR was a useful reference while I worked on #2755 (which shipped shape locking)."*<br>• **Translation Schema Guards** ([#2749](https://github.com/wkentaro/labelme/pull/2749)): Kentaro noted: *"The call sites and edge cases it mapped were the input for the smaller version (#3042)."* |
| **[python-pillow/Pillow](https://github.com/python-pillow/Pillow)**<br>*(#10256)* | **Andrew Murray (@radarhere)** commended the read-only memory mutability investigation in [#10256](https://github.com/python-pillow/Pillow/pull/10256) and followed up with [#10351](https://github.com/python-pillow/Pillow/pull/10351) adapting `_ensure_mutable()` to protect image buffer writes. |
| **[wolph/python-utils](https://github.com/wolph/python-utils)**<br>*(#62)* | **Rick van Hattem (@wolph)** praised the test isolation and edge-case handling in [#62](https://github.com/wolph/python-utils/pull/62) (*"The tests that check nothing is consumed are a nice touch"*), directly guiding the accepted deprecation cycle merged in [#64](https://github.com/wolph/python-utils/pull/64). |

<details>
<summary><strong>Explore all 40 merged contributions</strong></summary>

| Project | Contribution |
| :--- | :--- |
| roboflow/supervision | [#2834 · feat(dataset): load YOLO segmentation datasets with compact masks](https://github.com/roboflow/supervision/pull/2834) |
| roboflow/supervision | [#2772 · fix(dataset): raise when an image cannot be written during export](https://github.com/roboflow/supervision/pull/2772) |
| wkentaro/labelme | [#2833 · feat: support JPEG 2000 images through Pillow](https://github.com/wkentaro/labelme/pull/2833) |
| wkentaro/labelme | [#2819 · test: cover atomic-save directory permissions](https://github.com/wkentaro/labelme/pull/2819) |
| wkentaro/labelme | [#2818 · test(settings): verify keep-previous toggles survive restart](https://github.com/wkentaro/labelme/pull/2818) |
| wkentaro/labelme | [#2817 · test(canvas): cover linestrip phantom edges through real interaction](https://github.com/wkentaro/labelme/pull/2817) |
| wkentaro/labelme | [#2788 · feat: support drawing circles through three circumference points](https://github.com/wkentaro/labelme/pull/2788) |
| wkentaro/labelme | [#2750 · perf(io): bail out on oversized images before decoding](https://github.com/wkentaro/labelme/pull/2750) |
| wkentaro/labelme | [#2748 · chore: drop dead twine dev pin in pyproject.toml (closes #2489)](https://github.com/wkentaro/labelme/pull/2748) |
| wkentaro/labelme | [#2747 · fix(config): preserve existing POSIX mode bits during atomic saves](https://github.com/wkentaro/labelme/pull/2747) |
| wkentaro/labelme | [#2746 · test(app): cover real Windows UNC cross-volume path fallback](https://github.com/wkentaro/labelme/pull/2746) |
| wkentaro/labelme | [#2745 · feat(canvas): choose shape or canvas context menus by click location](https://github.com/wkentaro/labelme/pull/2745) |
| wkentaro/labelme | [#2744 · feat(canvas): double-click shape to edit label (closes #2190)](https://github.com/wkentaro/labelme/pull/2744) |
| wkentaro/labelme | [#2741 · perf(canvas): avoid full image array copy and hashing in load_pixmap](https://github.com/wkentaro/labelme/pull/2741) |
| kornia/kornia | [#6211 · fix(contrib): explain unsupported VisualPrompter configurations](https://github.com/kornia/kornia/pull/6211) |
| kornia/kornia | [#6202 · fix(filters): explain unsupported dissolving versions](https://github.com/kornia/kornia/pull/6202) |
| kornia/kornia | [#6172 · fix(color): accept integer-valued custom colormap bases](https://github.com/kornia/kornia/pull/6172) |
| obss/sahi | [#1480 · Preserve directory and stem names in YOLO label paths](https://github.com/obss/sahi/pull/1480) |
| obss/sahi | [#1479 · Fix category-zero filtering in COCO subsampling](https://github.com/obss/sahi/pull/1479) |
| mikedh/trimesh | [#2635 · Fix XYZ delimiter column counting and newline-free input](https://github.com/mikedh/trimesh/pull/2635) |
| pydantic/pydantic | [#14037 · Unify `TypeAdapter` serialization methods docstrings](https://github.com/pydantic/pydantic/pull/14037) |
| fsspec/filesystem_spec | [#2352 · Fix the FUSE CLI foreground option](https://github.com/fsspec/filesystem_spec/pull/2352) |
| fsspec/filesystem_spec | [#2347 · Accept standard binary update mode aliases in MemoryFileSystem.open](https://github.com/fsspec/filesystem_spec/pull/2347) |
| open-edge-platform/datumaro | [#2223 · fix(cli): explain missing optional dependencies before loading commands](https://github.com/open-edge-platform/datumaro/pull/2223) |
| pytest-dev/iniconfig | [#87 · Fix get overloads for callable positional defaults](https://github.com/pytest-dev/iniconfig/pull/87) |
| tox-dev/platformdirs | [#638 · 🐛 fix(cli): keep reporting when home is unknown](https://github.com/tox-dev/platformdirs/pull/638) |
| tox-dev/filelock | [#873 · 📝 docs(how-to): probe with blocking=False](https://github.com/tox-dev/filelock/pull/873) |
| lepture/mistune | [#516 · docs: handle fence metadata in the highlighting example](https://github.com/lepture/mistune/pull/516) |
| python-humanize/humanize | [#469 · Docs: clarify metric prefix selection examples](https://github.com/python-humanize/humanize/pull/469) |
| petl-developers/petl | [#764 · Refresh OpenRefine's name and links in related work](https://github.com/petl-developers/petl/pull/764) |
| mdomke/python-ulid | [#68 · fix: print results when running ulid as a module](https://github.com/mdomke/python-ulid/pull/68) |
| dgilland/cacheout | [#49 · Preserve memoized function signatures during type checking](https://github.com/dgilland/cacheout/pull/49) |
| click-contrib/click-repl | [#144 · fix: display docstring-derived help in command completions](https://github.com/click-contrib/click-repl/pull/144) |
| wolph/python-utils | [#64 · fix: deprecate nonpositive batch sizes before 5.0](https://github.com/wolph/python-utils/pull/64) |
| facelessuser/bracex | [#52 · fix: include current documentation build inputs in sdist](https://github.com/facelessuser/bracex/pull/52) |
| jdmacleod/unbagged | [#143 · feat(samples): generate a complete Albertsons sample upload](https://github.com/jdmacleod/unbagged/pull/143) |
| npechl/pandora | [#122 · docs: map starting points for new contributors](https://github.com/npechl/pandora/pull/122) |
| kristianedlund/hardcover-mcp | [#95 · docs: document Claude Code setup and current tool capabilities](https://github.com/kristianedlund/hardcover-mcp/pull/95) |
| jddrtn/smart-house-research-toolkit | [#24 · docs: add a dataset catalogue example](https://github.com/jddrtn/smart-house-research-toolkit/pull/24) |
| GautamVhavle/CatGPT-Gateway | [#20 · feat: add multi-tab concurrency, persistent sessions with history deduplication, and SSE streaming](https://github.com/GautamVhavle/CatGPT-Gateway/pull/20) |

</details>

<sub>Contribution and popularity snapshot: November 17, 2026. Counts refer to accepted PRs across independent upstream projects. Projects with 10k+ stars include Supervision, Pydantic, Labelme, and Kornia.</sub>

## Things I've built

| Project | What it does |
| :--- | :--- |
| **[WebLLM Pro](https://github.com/tongwentao/Web_LLM)** | Run LLMs in the browser with **WebGPU**, local model caching, persistent conversations, and Markdown rendering. Built with JavaScript and WebLLM. |
| **[Codeforces Analytics](https://github.com/tongwentao/codeforces-analytics-extension)** | A **Manifest V3** browser extension with interactive problem-solving analytics and high-resolution chart export. Built with JavaScript and ECharts. *Archived.* |

## Working toolkit

**Vision & data** &nbsp; Python · PyTorch · NumPy · Qt<br>
**Browser & local AI** &nbsp; JavaScript · WebGPU · WebLLM<br>
**Engineering** &nbsp; pytest · Git · GitHub Actions
