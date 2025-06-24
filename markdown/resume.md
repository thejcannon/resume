# Joshua Cannon

---

> An engineer crazy about good, clean, fun code (and colleagues).

---

## Experience

### Member of Technical Staff (Infrastructure) - Anthropic \[Jan 2024 - present\]

- Wrote the "poor-man's build system approximation" - a system whose purpose was to be as absolutely as simple/invisible as possible while still providing most of the features of a "real" build system
  - Automatic dependency management, tooling, dependency scraping, and even a remote test cache - for peanuts compared to Bazel (and even Pants)
- Led/owned CI for the primary monorepo, with an emphasis on testing and merge queue strategy
  - Improved reliability, speed, cost, reproducibility, and the overall feedback loop
- Stood up the framework and rollout of powerful GitHub-Actions workflows, which balanced strict security requirements with maximum permissions
  - Ultimately increased security posture _as well as_ developer velocity 

### Team Lead/Build Engineer - IBM WatsonX Orders (prior McD Tech Labs) \[Jul 2021 - Jan 2024\]

- Supported the entire engineering org in all things Build Engineering
- Migrated our core build tooling from Bazel to Pants, resulting in:
  - **>10 Minutes** saved on local and PR runs of the static analysis and test pipeline
  - Over **twenty thousand** of lines of BUILD metadata collapsed into 800
- Introduced several new static analysis tools to our toolkit to help catch issues early in the SDLC
- Pioneered the ability to dockerize any file with:
  - bit-wise reproduction capabilities
  - maximum leveraging of the docker layer cache, yielding fast re-builds
  - automatic dependency upgrades
- Resident "Pythonista" offering support and solutions to all engineers for our entire codebase

Overall, removed hurdles and blockages that were interrupting an engineer's ability to focus on
writing production-ready application code, while still increasing code quality and security.

### Senior Software Engineer - National Instruments \[May 2014 - Jul 2021\]

- Led company-wide Python coding conventions and best practices group with an emphasis on automated
  tooling
- Aided the design and implementation of a new company-wide CI/CD pipeline with a focus on
  flexibility, performance, and ease-of-use
- Designed and implemented foundational C++ device API engine to replace outdated C-based
  implementation which resulted in better testing support, cleaner code, and in some cases 4x speed
  improvement
- Created/Maintained backport library of subset of "modern" C++ STL to be used with older compilers

## Technical

Pantsbuild
: Maintainer-emeritus of the [Pantsbuild open source Build system](https://www.pantsbuild.org/)

Programming Languages
: **Python:** Expert-level experience with a wide swath of the Python ecosystem. From the
interpreter and standard-library, to commonly-used libraries, to full-stack development,
to tooling for static analysis, packaging, and testing.

: **Intermediate knowledge of** C++, Rust, JS/TS

## Education

2013-2016
: **BS, Computer Science**; The University of Texas (Austin)

## Shenanigans

- Repo: [Advent of one-line-of Code 2023](https://github.com/thejcannon/AdventOf-OneLineOf-Code2023)
- ⚡ Talk: [PyOhio 2023 - Mommy, How Are Objects Made? - by Dunder Seuss](https://youtu.be/P6ZoR8Egkpg)
- Talk: [North Bay Python 2023 - Oh the (Methods) You Can (Make): By Dunder Seuss](https://youtu.be/CSpzTx-S8B0)
- Talk: [PyTexas 2023 - A Build Engineer in a buildless lang](https://youtu.be/OENthsW-bMs)
- ⚡ Talk: [PyTexas 2023 - Two Snakes in a Trenchcoat - Descriptors](https://youtu.be/Y_lfGon4iiE?t=1003)
- Podcast: [InfoQ 2022 - Enabling a Collaborative and Welcoming Open Source Community](https://www.infoq.com/podcasts/welcoming-open-source-community/)
- Blog: [Pantsbuild blog (multiple)](https://blog.pantsbuild.org/author/joshua/)
- Blog: [IBM Developer - Case study: Incrementally migrating a Python monorepo from Bazel to Pants](https://developer.ibm.com/blogs/case-study-incrementally-migrating-a-python-monorepo-from-bazel-to-pants/)

---

> <joshdcannon@gmail.com> | [GitHub:thejcannon](https://github.com/thejcannon) | [\@thejcannon\@fosstodon.org](https://fosstodon.org/@thejcannon)
