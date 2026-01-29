# Contributions

[![GitHub](https://img.shields.io/badge/GitHub-killerdevildog-181717?style=flat&logo=github)](https://github.com/killerdevildog)
[![Codeberg](https://img.shields.io/badge/Codeberg-killerdevildog-2185D0?style=flat&logo=codeberg)](https://codeberg.org/killerdevildog)
[![Radicle](https://img.shields.io/badge/Radicle-killerdevildog-6B5CE7?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0wIDE4Yy00LjQyIDAtOC0zLjU4LTgtOHMzLjU4LTggOC04IDggMy41OCA4IDgtMy41OCA4LTggOHoiLz48L3N2Zz4=)](https://app.radicle.xyz/nodes/seed.radicle.garden/rad:z34ZmBpUW1uQJX3Aohe5PQDGtmMhe)

A personal repository documenting my open source contributions across multiple platforms. This also serves as a portfolio showcasing my work and technical skills.

**Author:** killerdevildog  
**Radicle DID:** `did:key:z6Mkgi3EW1eVVb4REBZspeU9cHrJev8GEZae7uACZJkxCKMz`  
**GitHub:** [killerdevildog](https://github.com/killerdevildog)

## Overview

This repository serves as a central hub for tracking and showcasing my contributions to open source projects, including:

- Bug fixes
- Feature implementations
- Performance improvements
- Documentation updates
- New tools and utilities

---

## Projects Created

### Radicle Network

| Project | RID | Description |
|---------|-----|-------------|
| **rad-meta** | `rad:z4VghZAUgCSvz9s2p9AgJ9AY7ricx` | CLI for searching Radicle repositories via search.radicle.xyz |
| **Contributions** | `rad:z34ZmBpUW1uQJX3Aohe5PQDGtmMhe` | Open source contributions portfolio |
| **Programming_Benchmark** | `rad:z4RRJ6vMp6Ysa1WSRW7opPzQSDTfX` | Comprehensive multi-language benchmark suite comparing performance across 16+ programming languages |

### GitHub

| Project | Description | Link |
|---------|-------------|------|
| **rad-meta** | CLI for searching Radicle repositories via search.radicle.xyz | [GitHub](https://github.com/killerdevildog/rad-meta) |
| **PNGQrush** | A modernized fork of pngcrush with libdeflate and Zopfli compression backends | [GitHub](https://github.com/killerdevildog/PNGQrush) |
| **Qwast-Reader** | An SVG animation C++ library, kinda like a video codec for SVG | [GitHub](https://github.com/killerdevildog/Qwast-Reader) |
| **gameswf** | GameSWF library | [GitHub](https://github.com/killerdevildog/gameswf) |
| **codeberg-cli** | A gh-like CLI for Codeberg | [GitHub](https://github.com/killerdevildog/codeberg-cli) |
| **batswinggame** | Game for 7DFPS Dec 5th to Dec 14th Game Jam | [GitHub](https://github.com/killerdevildog/batswinggame) |

### Codeberg

| Project | Description | Link |
|---------|-------------|------|
| **codeberg-cli** | A gh-like CLI for Codeberg | [Codeberg](https://codeberg.org/killerdevildog/codeberg-cli) |

---

## Patches / Pull Requests / Merge Requests Submitted

> **Note:** Different platforms use different terminology for the same concept — a proposed code change submitted for review:
> | Platform | Term |
> |----------|------|
> | Radicle | Patch |
> | GitHub | Pull Request (PR) |
> | GitLab / Codeberg | Merge Request (MR) |

### Radicle: Heartwood (`rad:z3gqcJUoA1n9HaHKufZs5FCSGazv5`)

*Radicle Heartwood Protocol & Stack*

| Patch ID | Title | Status | Changes | Description |
|----------|-------|--------|---------|-------------|
| `772c50a` | feat(clone): initial groundwork for rad clone --meta flag | 🟢 Open | +532 / -101 | Add FetchMode enum with Full and Meta variants to support metadata-only fetches. Threads the mode parameter through the entire fetch pipeline (CLI, Node, Protocol, Fetch). When `--meta` is used, only the repository identity is fetched, allowing users to inspect project name and description without downloading full repository data. |
| `9f920f5` | stability/perf: reduce churn, add backoff/debounce, throttle GC, safer shutdown | 🟢 Open | +534 / -110 | Comprehensive stability and performance improvements including: defer inventory scan/refs db populate to idle, skip PoW work when target is zero, configurable network intervals, adaptive backoff for gossip/sync, debounce inventory announcements, throttle git gc during fetch, and graceful shutdown on control disconnect. |

### Radicle: Desktop (`rad:z4D5UCArafTzTQpDZNQRuqswh3ury`)

*Radicle Desktop Application*

| Patch ID | Title | Status | Changes | Description |
|----------|-------|--------|---------|-------------|
| `6e78517` | fix: markdown table text displaying vertically | 🟢 Open | +4 / -1 | Fixes issue where markdown table cell text was rendering character-by-character vertically instead of horizontally. Overrides word-break and overflow-wrap to 'normal' for table cells. |

### GitHub Pull Requests

#### ✅ Merged (22)

| Repository | Title | Date | Link |
|------------|-------|------|------|
| **queer/boxxy** | docs: replace obsolete tmux example with AWS CLI | 2026-01-13 | [PR #279](https://github.com/queer/boxxy/pull/279) |
| **g3n/engine** | fix: use IsNaN() instead of == NaN() comparison in Ray.IntersectPlane | 2026-01-07 | [PR #317](https://github.com/g3n/engine/pull/317) |
| **Amphuse76/GoGetEm** | changed to green sphere | 2025-08-18 | [PR #1](https://github.com/Amphuse76/GoGetEm/pull/1) |
| **methusalah/OpenRTS** | Cumulative updates | 2025-08-16 | [PR #117](https://github.com/methusalah/OpenRTS/pull/117) |
| **OpenKore/openkore** | Make maxWalkPath configurable in Field.pm | 2025-08-16 | [PR #4070](https://github.com/OpenKore/openkore/pull/4070) |
| **phase1geo/Minder** | Fix image resize crash in set_width method | 2025-08-03 | [PR #659](https://github.com/phase1geo/Minder/pull/659) |
| **MyGUI/mygui** | Enable CMake testing infrastructure for unit tests | 2025-08-02 | [PR #289](https://github.com/MyGUI/mygui/pull/289) |
| **opencv/opencv** | Fix Python Scalar typing issue #27528 | 2025-08-01 | [PR #27620](https://github.com/opencv/opencv/pull/27620) |
| **matrixcascade/PainterEngine** | Fix web keyboard input for shift+number and numpad keys | 2025-08-01 | [PR #144](https://github.com/matrixcascade/PainterEngine/pull/144) |
| **alekmaul/pvsneslib** | Fix docs issue 309 | 2025-08-01 | [PR #312](https://github.com/alekmaul/pvsneslib/pull/312) |
| **raysan5/raylib** | [build] Add ARM64 support to Linux builds | 2025-07-31 | [PR #5075](https://github.com/raysan5/raylib/pull/5075) |
| **microsoft/terminal** | Fix/scrollbar marks shell integration | 2025-07-29 | [PR #19185](https://github.com/microsoft/terminal/pull/19185) |
| **tornadoweb/tornado** | Fix ValueError in file_uploader.py by converting @gen.coroutine to async | 2025-07-28 | [PR #3523](https://github.com/tornadoweb/tornado/pull/3523) |
| **profanity-im/profanity** | Fix GPGME >= 2.0.0 compatibility issue #2048 | 2025-07-23 | [PR #2050](https://github.com/profanity-im/profanity/pull/2050) |
| **nasa/ExoMiner** | Fix tic ids csv structure check | 2025-07-21 | [PR #2](https://github.com/nasa/ExoMiner/pull/2) |
| **ultimatepp/ultimatepp** | Fix RichTxt::SetRefreshFrom logic (issue #137) | 2025-07-19 | [PR #293](https://github.com/ultimatepp/ultimatepp/pull/293) |
| **phase1geo/Minder** | Fix tab right-click crash (issue #655) | 2025-07-19 | [PR #656](https://github.com/phase1geo/Minder/pull/656) |
| **cycfi/elements** | fix: Remove duplicate source file entries in CMakeLists.txt | 2025-07-18 | [PR #438](https://github.com/cycfi/elements/pull/438) |
| **psf/requests** | docs: clarify timeout parameter uses seconds in Session.request | 2025-07-18 | [PR #6994](https://github.com/psf/requests/pull/6994) |
| **encode/django-rest-framework** | Fix mutable default arguments in OrderingFilter methods | 2025-07-18 | [PR #9742](https://github.com/encode/django-rest-framework/pull/9742) |
| **ezEngine/ezEngine** | Implement proper packaging for ShaderExplorer sample | 2025-07-17 | [PR #1613](https://github.com/ezEngine/ezEngine/pull/1613) |
| **STICKnoLOGIC/First-Accord** | Add killerDevildog to contributor list | 2025-07-12 | [PR #55](https://github.com/STICKnoLOGIC/First-Accord/pull/55) |

#### 🟢 Open (40)

| Repository | Title | Date | Link |
|------------|-------|------|------|
| **sammycage/lunasvg** | Fix #213: Replace nearest-neighbor with Lanczos-8 + Gaussian blur | 2026-01-21 | [PR #259](https://github.com/sammycage/lunasvg/pull/259) |
| **OpenLoco/OpenLoco** | Add forEachLoaded<T> helper function for object iteration | 2026-01-13 | [PR #3614](https://github.com/OpenLoco/OpenLoco/pull/3614) |
| **OpenSourceRisk/Engine** | Fix remaining 'boostrap' typo in QuantExt | 2026-01-07 | [PR #328](https://github.com/OpenSourceRisk/Engine/pull/328) |
| **microui-community/microui** | Fix issue 19 command alignment | 2026-01-05 | [PR #3](https://github.com/microui-community/microui/pull/3) |
| **fabianishere/brainfuck** | Feature/extern ffi | 2025-08-29 | [PR #89](https://github.com/fabianishere/brainfuck/pull/89) |
| **gameplay3d/gameplay** | Fix Linux build issues by integrating system-level dependencies | 2025-08-16 | [PR #1997](https://github.com/gameplay3d/gameplay/pull/1997) |
| **Gforcex/OpenGraphic** | Add Redot Engine to the Engine section | 2025-08-15 | [PR #9](https://github.com/Gforcex/OpenGraphic/pull/9) |
| **Aloshi/EmulationStation** | Fix/build missing stack include Fix #927 | 2025-08-11 | [PR #928](https://github.com/Aloshi/EmulationStation/pull/928) |
| **BuilderIO/gpt-crawler** | fix: handle query parameter exclusions that glob patterns cannot match | 2025-08-04 | [PR #406](https://github.com/BuilderIO/gpt-crawler/pull/406) |
| **java-decompiler/jd-gui** | Replace JCenter with Maven Central to fix build failure | 2025-08-04 | [PR #468](https://github.com/java-decompiler/jd-gui/pull/468) |
| **juce-framework/JUCE** | Fix #946: Add standard iterator traits to CharPointer_UTF8 | 2025-08-04 | [PR #1562](https://github.com/juce-framework/JUCE/pull/1562) |
| **mastodon/mastodon** | Handle moved accounts on the hover card | 2025-08-03 | [PR #35640](https://github.com/mastodon/mastodon/pull/35640) |
| **pmgl/microstudio** | fix(engine): decouple input reset from update loop | 2025-08-03 | [PR #243](https://github.com/pmgl/microstudio/pull/243) |
| **rxi/microui** | Fix misaligned pointer access in command list | 2025-08-03 | [PR #76](https://github.com/rxi/microui/pull/76) |
| **cnjinhao/nana** | Fix issue #687: Add configurable precision for spinbox | 2025-08-02 | [PR #729](https://github.com/cnjinhao/nana/pull/729) |
| **obsproject/obs-studio** | Fix localization for hardcoded strings in status bar and settings | 2025-08-02 | [PR #12469](https://github.com/obsproject/obs-studio/pull/12469) |
| **mdavisprog/OctaneGUI** | Fix GCC 13.2.1 compilation errors | 2025-08-01 | [PR #20](https://github.com/mdavisprog/OctaneGUI/pull/20) |
| **piskelapp/piskel** | fix(build): Remove reference to non-existent ImageUploadService.js | 2025-08-01 | [PR #1198](https://github.com/piskelapp/piskel/pull/1198) |
| **piskelapp/piskel** | fix(export): Add robust fallback for PNG export scaling in offline mode | 2025-08-01 | [PR #1197](https://github.com/piskelapp/piskel/pull/1197) |
| **playcanvas/engine** | Expose TextureHandler#parsers as public API | 2025-08-01 | [PR #7878](https://github.com/playcanvas/engine/pull/7878) |
| **oohlaf/python-whirlpool** | Fix Python 3.10+ compatibility | 2025-08-01 | [PR #14](https://github.com/oohlaf/python-whirlpool/pull/14) |
| **DanielChappuis/reactphysics3d** | Fix Issue #416: Implement dynamic resource file location for testbed | 2025-07-30 | [PR #428](https://github.com/DanielChappuis/reactphysics3d/pull/428) |
| **psf/requests** | Fix stringio content length | 2025-07-30 | [PR #7000](https://github.com/psf/requests/pull/7000) |
| **BrOrlandi/StarWarsIntroCreator** | Fix text viewport width issue to fill screen properly | 2025-07-29 | [PR #28](https://github.com/BrOrlandi/StarWarsIntroCreator/pull/28) |
| **karllessard/tensorflow-docs** | Add TensorFlow Java documentation generation tools | 2025-07-29 | [PR #1](https://github.com/karllessard/tensorflow-docs/pull/1) |
| **huggingface/transformers** | Fix SigLIP2 documentation model/processor mismatch | 2025-07-28 | [PR #39718](https://github.com/huggingface/transformers/pull/39718) |
| **MADE-Apps/legerity** | feat: Add Vue.js page object generation support | 2025-07-22 | [PR #276](https://github.com/MADE-Apps/legerity/pull/276) |
| **twbs/bootstrap** | fix(modal): prevent focus on modal container with negative tabindex | 2025-07-21 | [PR #41607](https://github.com/twbs/bootstrap/pull/41607) |
| **huxingyi/dust3d** | Add screenshot to readme | 2025-07-21 | [PR #172](https://github.com/huxingyi/dust3d/pull/172) |
| **huxingyi/dust3d** | Add export to gltf format | 2025-07-21 | [PR #171](https://github.com/huxingyi/dust3d/pull/171) |
| **huxingyi/dust3d** | Enable Linux build support with Ubuntu 24.04 badge | 2025-07-21 | [PR #170](https://github.com/huxingyi/dust3d/pull/170) |
| **xissburg/edyn** | Fix MSVC compiler warnings (issue #127) | 2025-07-21 | [PR #144](https://github.com/xissburg/edyn/pull/144) |
| **xissburg/edyn** | Add .clang-format configuration | 2025-07-20 | [PR #143](https://github.com/xissburg/edyn/pull/143) |
| **libuv/libuv** | Fix const-correctness warning in linux.c | 2025-07-19 | [PR #4843](https://github.com/libuv/libuv/pull/4843) |
| **ValveSoftware/Proton** | feat: Add IO and process priority controls | 2025-07-19 | [PR #8913](https://github.com/ValveSoftware/Proton/pull/8913) |
| **nothings/stb** | Document channel count behavior for stb_image_write formats | 2025-07-19 | [PR #1821](https://github.com/nothings/stb/pull/1821) |
| **pypa/wheel** | Add wheel info subcommand | 2025-07-19 | [PR #669](https://github.com/pypa/wheel/pull/669) |
| **GloriousPtr/ArcGameEngine** | Fix/linux build dependencies | 2025-07-17 | [PR #25](https://github.com/GloriousPtr/ArcGameEngine/pull/25) |
| **python/cpython** | gh-118469: Document sqlite3.Binary in module constants | 2025-07-17 | [PR #136734](https://github.com/python/cpython/pull/136734) |
| **EpicGames/UnrealEngine** | docs: Improve missing documentation comments for MovieScene constraint helpers | 2025-07-16 | [PR #13590](https://github.com/EpicGames/UnrealEngine/pull/13590) |

#### ❌ Closed (Not Merged)

| Repository | Title | Date | Link |
|------------|-------|------|------|
| **erincatto/box2d** | Optimize hit events | 2026-01-07 | [PR #1029](https://github.com/erincatto/box2d/pull/1029) |
| **OpenTTD/OpenTTD** | Fix issue #14485: Allow road vehicles to use cross-type stops | 2025-08-15 | [PR #14518](https://github.com/OpenTTD/OpenTTD/pull/14518) |
| **facebook/folly** | Fix GitHub issue #2487: Add missing <stdexcept> include | 2025-08-13 | [PR #2490](https://github.com/facebook/folly/pull/2490) |
| **Dav1dde/glad** | Fix issue #492: Handle GL implementations with 0 extensions | 2025-08-05 | [PR #518](https://github.com/Dav1dde/glad/pull/518) |
| **godotengine/godot** | Fix crash on empty GLTF texture | 2025-08-05 | [PR #109323](https://github.com/godotengine/godot/pull/109323) |
| **h2o/h2o** | doc: document 'client-ca-file' SSL option | 2025-08-04 | [PR #3497](https://github.com/h2o/h2o/pull/3497) |
| **ocornut/imgui** | docs: add "Why Immediate Mode?" FAQ entry (#8851) | 2025-08-04 | [PR #8862](https://github.com/ocornut/imgui/pull/8862) |
| **AndreaOrru/LaiNES** | Implement PPU color emphasis bits support. Fixes #3 | 2025-08-04 | [PR #46](https://github.com/AndreaOrru/LaiNES/pull/46) |
| **mlpack/mlpack** | Fix/arm64 openmp convolution segfault | 2025-08-03 | [PR #3979](https://github.com/mlpack/mlpack/pull/3979) |
| **pypa/pip** | Fix outdated upgrade recommendation syntax | 2025-08-01 | [PR #13518](https://github.com/pypa/pip/pull/13518) |
| **profanity-im/profanity** | Fix keyfile warning messages for non-critical files | 2025-08-01 | [PR #2056](https://github.com/profanity-im/profanity/pull/2056) |
| **ValveSoftware/Proton** | Fix libraryfolders.vdf index incrementing in setup_steam_files | 2025-08-01 | [PR #8943](https://github.com/ValveSoftware/Proton/pull/8943) |
| **kitao/pyxel** | Fix app2exe to handle paths with spaces | 2025-07-31 | [PR #637](https://github.com/kitao/pyxel/pull/637) |
| **Razakhel/RaZ** | Fix MSVC compatibility for TypeUtils hasAttribute() | 2025-07-30 | [PR #68](https://github.com/Razakhel/RaZ/pull/68) |
| **JeanPhilippeKernel/RendererEngine** | feat: Add CMakePresets.json support for cross-platform builds | 2025-07-30 | [PR #461](https://github.com/JeanPhilippeKernel/RendererEngine/pull/461) |
| **mikke89/RmlUi** | Lua: expose Element API on ElementPtr via __index forwarder | 2025-07-29 | [PR #797](https://github.com/mikke89/RmlUi/pull/797) |

---

## Learning Git & Open Source (The Hard Way)

When I started contributing to open source, I made mistakes. A lot of them. I used AI tools to help me learn faster, but sometimes I didn't vet the output carefully enough, misunderstood codebases, or submitted PRs that missed the mark. Some maintainers were patient and helpful. Others... less so.

This section documents the PRs where things went sideways — not to complain, but to be transparent about my learning journey. If you're new to open source, maybe you can learn from my mistakes.

📄 **[Full details: ai_slop.md](ai_slop.md)**

| Repository | PR | What Went Wrong |
|------------|-----|-----------------|
| OpenTTD/OpenTTD | [#14518](https://github.com/OpenTTD/OpenTTD/pull/14518) | Didn't fill in PR template properly |
| Dav1dde/glad | [#518](https://github.com/Dav1dde/glad/pull/518) | Code did nothing — didn't understand the logic |
| mlpack/mlpack | [#3979](https://github.com/mlpack/mlpack/pull/3979) | Addressed symptoms, not root cause |
| pypa/pip | [#13518](https://github.com/pypa/pip/pull/13518) | Referenced non-existent issues, over-explained |
| pypa/pip | [#13489](https://github.com/pypa/pip/pull/13489) | CI failures, didn't test properly |
| Razakhel/RaZ | [#68](https://github.com/Razakhel/RaZ/pull/68) | MSVC compatibility issues |
| mikke89/RmlUi | [#797](https://github.com/mikke89/RmlUi/pull/797) | Didn't test the code, included unnecessary files |
| solvespace/solvespace | [#1610](https://github.com/solvespace/solvespace/pull/1610) | Included unnecessary .md files in commit |
| ultimatepp/ultimatepp | [#294](https://github.com/ultimatepp/ultimatepp/pull/294) | Approach didn't fit the codebase |
| NationalSecurityAgency/ghidra | [#8373](https://github.com/NationalSecurityAgency/ghidra/pull/8373) | Didn't properly vet the changes |
| the-tcpdump-group/libpcap | [#1535](https://github.com/the-tcpdump-group/libpcap/pull/1535) | Second warning for auto-generated PR |
| schellingb/ZillaLib | [#21](https://github.com/schellingb/ZillaLib/pull/21) | Code was inactive/did nothing, untested |
| cfnptr/garden | [#85](https://github.com/cfnptr/garden/pull/85) | Low quality submission |

### Lessons Learned

1. **Always test your code** — Don't just compile it, actually run it
2. **Read the contribution guidelines** — Every project has different expectations
3. **AI is a tool, not a replacement** — Vet every line, don't blindly copy-paste
4. **Quality over quantity** — One good PR beats ten bad ones
5. **Be humble** — Maintainers are volunteers; respect their time

### The Reality of Being a New Contributor

Some things I encountered that made the learning curve steeper:

- **Following harassment**: Some individuals followed me from project to project, warning maintainers about me before I even submitted anything. My intent was always to help, but once you're labeled, it sticks.
- **Stale issues**: Many issues I tried to fix had been open for *years*. When I attempted to address them with AI assistance, some were rejected not because the fix was wrong, but because "you don't even use this library."
- **Gatekeeping**: Some projects have implicit requirements beyond the code itself — you need to prove you're "one of them" before contributions are accepted.

None of this stopped me. I kept learning.

### A Note on AI and the Technology Adoption Curve

Every transformative technology follows a similar pattern of resistance before acceptance. The adoption curve can be modeled as:

$$A(t) = \frac{L}{1 + e^{-k(t - t_0)}}$$

Where $L$ is the maximum adoption level, $k$ is the growth rate, and $t_0$ is the inflection point. This S-curve has played out repeatedly throughout history:

| Technology | Initial Fears | What People Learned |
|------------|---------------|---------------------|
| **The Wheel** | "It will make us lazy" | Enabled civilization |
| **Electricity** | "Invisible fire will kill us" | Proper insulation and grounding |
| **Automobiles** | "Horseless carriages are dangerous" | Inertia, braking, speed limits |
| **The Internet** | "A haven for criminals" | Enabled global collaboration |
| **AI-Assisted Coding** | "It produces slop, wastes time" | *We're still learning* |

People didn't understand inertia before driving — they learned the hard way that you slow down *before* the turn, not during it. They learned that cars need maintenance, that roads need rules, that licenses matter.

The same will happen with AI in open source. Right now, we're in the steep part of the learning curve. Some people are crashing. Some are figuring it out. The tools will improve, best practices will emerge, and projects will adapt their contribution guidelines.

**To maintainers:** Patience goes both ways. If someone is clearly trying to learn, a rejection with guidance is infinitely more valuable than mockery. The next generation of contributors will grow up with AI as natural as IDEs and linters. The question isn't *whether* AI will be part of open source — it's how we integrate it thoughtfully.

**To new contributors using AI:** You are the pioneers figuring this out. Document your failures. Learn publicly. The friction you experience today will become the best practices of tomorrow.

---

## Contribution Summary

| Type | Count |
|------|-------|
| Projects Created (Radicle) | 3 |
| Projects Created (GitHub) | 6 |
| Projects Created (Codeberg) | 1 |
| Radicle Patches | 3 |
| GitHub PRs (Merged) | 22 |
| GitHub PRs (Open) | 40 |
| GitHub PRs (Closed) | 16 |
| **Total Contributions** | **91** |

---

## Contact

Feel free to reach out if you'd like to collaborate on any open source projects!

- **GitHub:** [killerdevildog](https://github.com/killerdevildog)
- **Codeberg:** [killerdevildog](https://codeberg.org/killerdevildog)

---

*This repository is hosted on the [Radicle](https://radicle.xyz) network.* 
