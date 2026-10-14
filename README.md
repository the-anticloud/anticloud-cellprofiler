# CELLPROFILER

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-scientific_lab-lightgrey)

> Anticloud-hardened packaging of the upstream project `CELLPROFILER` in category **SCIENTIFIC LAB**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SCIENTIFIC LAB · **Upstream:** https://github.com/CellProfiler/CellProfiler · **Upstream pin:** `c1d6426989d64f4dc9774aa246c7054a214a7d33` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<picture>
    <source media="(prefers-color-scheme: dark)" srcset="src/frontend/cellprofiler/data/images/splash-white-text-alpha.png">
    <img alt="CellProfiler" src="src/frontend/cellprofiler/data/images/splash-black-text-alpha.png">
</picture>

[![Version](https://img.shields.io/badge/version-4.2.8-green.svg)](https://cellprofiler.org/releases)
[![Docs](https://img.shields.io/badge/documentation-4.2.8-brightgreen.svg)](https://cellprofiler-manual.s3.amazonaws.com/CellProfiler-4.2.8/index.html)
[![Image.sc forum](https://img.shields.io/badge/dynamic/json.svg?label=forum&url=https%3A%2F%2Fforum.image.sc%2Ftag%2Fcellprofiler.json&query=%24.topic_list.tags.0.topic_count&colorB=brightgreen&suffix=%20topics&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAABPklEQVR42m3SyyqFURTA8Y2BER0TDyExZ+aSPIKUlPIITFzKeQWXwhBlQrmFgUzMMFLKZeguBu5y+//17dP3nc5vuPdee6299gohUYYaDGOyyACq4JmQVoFujOMR77hNfOAGM+hBOQqB9TjHD36xhAa04RCuuXeKOvwHVWIKL9jCK2bRiV284QgL8MwEjAneeo9VNOEaBhzALGtoRy02cIcWhE34jj5YxgW+E5Z4iTPkMYpPLCNY3hdOYEfNbKYdmNngZ1jyEzw7h7AIb3fRTQ95OAZ6yQpGYHMMtOTgouktYwxuXsHgWLLl+4x++Kx1FJrjLTagA77bTPvYgw1rRqY56e+w7GNYsqX6JfPwi7aR+Y5SA+BXtKIRfkfJAYgj14tpOF6+I46c4/cAM3UhM3JxyKsxiOIhH0IO6SH/A1Kb1WBeUjbkAAAAAElFTkSuQmCC)](https://forum.image.sc/tag/cellprofiler)

**CellProfiler** is a free open-source software designed to enable biologists without training in computer vision or programming to quantitatively measure phenotypes from thousands of images automatically. More information can be found in the [CellProfiler Wiki](https://github.com/CellProfiler/CellProfiler/wiki).

## What version of CellProfiler should I use?

**We recommend the stable release of CellProfiler.**

You can download a stable release for macOS and Windows from the [CellProfiler website](http://cellprofiler.org/releases/).

If you’re **contributing or planning to contribute to CellProfiler**, you should **compile CellProfiler from source**. Instructions for compiling CellProfiler on [Linux](https://github.com/CellProfiler/CellProfiler/wiki/Source-installation-(Linux)), [macOS](https://github.com/CellProfiler/CellProfiler/wiki/Source-installation-%28OS-X-and-macOS%29) and [Windows](https://github.com/CellProfiler/CellProfiler/wiki/Source-installation-%28Windows%29) are available from [CellProfiler’s GitHub wiki](https://github.com/CellProfiler/CellProfiler/wiki).

If you’re the **maintainer of a third-party CellProfiler module**, you should use the **nightly** release of CellProfiler. You can download a nightly release for macOS and Windows from the [CellProfiler website](http://cellprofiler.org/releases/). Let us know if we’ve inadvertently broken your module by [submitting a GitHub issue](https://github.com/CellProfiler/CellProfiler/issues).

If you’re an **enthusiastic CellProfiler user**, you should try the **beta** release of CellProfiler. You can download a beta release for macOS and Windows from the [CellProfiler website](http://cellprofiler.org/releases/). Let us know if you encounter a bug by [submitting a GitHub issue](https://github.com/CellProfiler/CellProfiler/issues).

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `distribution/`, `nix/`, `scripts/`, `src/`, `tests/`
- Snapshot size: **1574 files**, **220934 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (930), `.tif` (207), `.png` (143), `.pipeline` (123), `.rst` (53), `(none)` (16)
- Upstream commit pinned for this packaging: `c1d6426989d64f4dc9774aa246c7054a214a7d33`

---

## Installation

If you’re the **maintainer of a third-party CellProfiler module**, you should use the **nightly** release of CellProfiler. You can download a nightly release for macOS and Windows from the [CellProfiler website](http://cellprofiler.org/releases/). Let us know if we’ve inadvertently broken your module by [submitting a GitHub issue](https://github.com/CellProfiler/CellProfiler/issues).

If you’re an **enthusiastic CellProfiler user**, you should try the **beta** release of CellProfiler. You can download a beta release for macOS and Windows from the [CellProfiler website](http://cellprofiler.org/releases/). Let us know if you encounter a bug by [submitting a GitHub issue](https://github.com/CellProfiler/CellProfiler/issues).

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

If you’re an **enthusiastic CellProfiler user**, you should try the **beta** release of CellProfiler. You can download a beta release for macOS and Windows from the [CellProfiler website](http://cellprofiler.org/releases/). Let us know if you encounter a bug by [submitting a GitHub issue](https://github.com/CellProfiler/CellProfiler/issues).

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

[![Image.sc forum](https://img.shields.io/badge/dynamic/json.svg?label=forum&url=https%3A%2F%2Fforum.image.sc%2Ftag%2Fcellprofiler.json&query=%24.topic_list.tags.0.topic_count&colorB=brightgreen&suffix=%20topics&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAABPklEQVR42m3SyyqFURTA8Y2BER0TDyExZ+aSPIKUlPIITFzKeQWXwhBlQrmFgUzMMFLKZeguBu5y+//17dP3nc5vuPdee6299gohUYYaDGOyyACq4JmQVoFujOMR77hNfOAGM+hBOQqB9TjHD36xhAa04RCuuXeKOvwHVWIKL9jCK2bRiV284QgL8MwEjAneeo9VNOEaBhzALGtoRy02cIcWhE34jj5YxgW+E5Z4iTPkMYpPLCNY3hdOYEfNbKYdmNngZ1jyEzw7h7AIb3fRTQ95OAZ6yQpGYHMMtOTgouktYwxuXsHgWLLl+4x++Kx1FJrjLTagA77bTPvYgw1rRqY56e+w7GNYsqX6JfPwi7aR+Y5SA+BXtKIRfkfJAYgj14tpOF6+I46c4/cAM3UhM3JxyKsxiOIhH0IO6SH/A1Kb1WBeUjbkAAAAAElFTkSuQmCC)](https://forum.image.sc/tag/cellprofiler)

**CellProfiler** is a free open-source software designed to enable biologists without training in computer vision or programming to quantitatively measure phenotypes from thousands of images automatically. More information can be found in the [CellProfiler Wiki](https://github.com/CellProfiler/CellProfiler/wiki).

## What version of CellProfiler should I use?

**We recommend the stable release of CellProfiler.**

You can download a stable release for macOS and Windows from the [CellProfiler website](http://cellprofiler.org/releases/).

If you’re **contributing or planning to contribute to CellProfiler**, you should **compile CellProfiler from source**. Instructions for compiling CellProfiler on [Linux](https://github.com/CellProfiler/CellProfiler/wiki/Source-installation-(Linux)), [macOS](https://github.com/CellProfiler/CellProfiler/wiki/Source-installation-%28OS-X-and-macOS%29) and [Windows](https://github.com/CellProfiler/CellProfiler/wiki/Source-installation-%28Windows%29) are available from [CellProfiler’s GitHub wiki](https://github.com/CellProfiler/CellProfiler/wiki).

If you’re the **maintainer of a third-party CellProfiler module**, you should use the **nightly** release of CellProfiler. You can download a nightly release for macOS and Windows from the [CellProfiler website](http://cellprofiler.org/releases/). Let us know if we’ve inadvertently broken your module by [submitting a GitHub issue](https://github.com/CellProfiler/CellProfiler/issues).

If you’re an **enthusiastic CellProfiler user**, you should try the **beta** release of CellProfiler. You can download a beta release for macOS and Windows from the [CellProfiler website](http://cellprofiler.org/releases/). Let us know if you encounter a bug by [submitting a GitHub issue](https://github.com/CellProfiler/CellProfiler/issues).

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 1574 |
| Lines of code | 220934 |
| Dependency references | 99 |
| Dependencies by ecosystem | conda: 45, pypi: 54 |
| Upstream license | BSD-3-Clause |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| conda | dev | - | src/subpackages/library/environment.yml |
| conda | conda-forge | - | src/subpackages/library/environment.yml |
| conda | numpy | - | src/subpackages/library/environment.yml |
| conda | scikit-image | - | src/subpackages/library/environment.yml |
| conda | scipy | - | src/subpackages/library/environment.yml |
| conda | matplotlib | - | src/subpackages/library/environment.yml |
| conda | mahotas | - | src/subpackages/library/environment.yml |
| conda | pip | - | src/subpackages/library/environment.yml |
| conda | centrosome | - | src/subpackages/library/environment.yml |
| pypi | numpy | >=1.26.4 | src/subpackages/library/pyproject.toml |
| pypi | scikit-image | >=0.20.0 | src/subpackages/library/pyproject.toml |
| pypi | scikit-learn | >=1.3.0 | src/subpackages/library/pyproject.toml |
| pypi | scipy | >=1.9.1 | src/subpackages/library/pyproject.toml |
| pypi | mahotas | >=1.4.13 | src/subpackages/library/pyproject.toml |
| pypi | centrosome | >=1.3.0 | src/subpackages/library/pyproject.toml |
| ... | (84 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `mypy.ini`
- `pytest.ini`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing Guidelines

Hello! We're so glad you're interested in contributing to CellProfiler!

This document provides guidelines for contributing to CellProfiler. You'll find information on what you can contribute, choosing what to contribute, setting up your local workstation for development, and submitting your contribution for review and acceptance.

We'd like to ensure this document is always accurate and understandable. Please [file an issue](https://github.com/CellProfiler/CellProfiler/issues/new) if any information is missing, unclear, or incorrect.  

You may also check out our [YouTube tutorial](https://youtu.be/fgF_YueM1b8) for a discussion of many of these issues and demonstration of editing and creating 
modules.

## Creating an Issue

The CellProfiler team uses [GitHub issues](https://github.com/CellProfiler/CellProfiler/issues) to track upcoming and ongoing work. Examples of issues are:

* Documentation additions and corrections
* Errors starting or running CellProfiler
* Unexpected behavior or output
* Feature requests (e.g., new modules)

When there is an issue you would like to file, please check that the issue does not already exist. You can search open issues by including the default search filters "is: issue is: open". Once you are certain no issue exists, [create a new issue](https://github.com/CellProfiler/CellProfiler/issues/new) while keeping the following guidelines in mind:

1. Give your issue a descriptive title. A good title summarizes the issue in a single sentence. Be specific. Avoid general titles such as "Add documentation" or "Error running CellProfiler".

2. Provide specific information about your issue.
  * Documentation: What is the mistake? Where is the mistake? What is the correct documentation?
  * Errors: What is the exact error? How did it occur? Please provide error details from the GUI or output from the terminal.
  * Unexpected behavior: What behavior did you observe? How did it occur? What behavior do you expect?
  * Feature requests: What is the feature? Why would you like to have this functionality in CellProfiler?

3. Click "Submit new issue". After an issue is created, CellProfiler maintainers will add appropriate labels to categorize your issue. The maintainers may also ask clarifying questions and engage you and the greater community in discussion of your issue. Please be ready to engage in the discussion.

## Choosing an Issue

CellProfiler GitHub issues are categorized using labels. We encourage new

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: BSD-3-Clause** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
The BSD 3-Clause License

Copyright © 2003 - 2021 Broad Institute, Inc. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

    1.  Redistributions of source code must retain the above copyright notice,
        this list of conditions and the following disclaimer.

    2.  Redistributions in binary form must reproduce the above copyright
        notice, this list of conditions and the following disclaimer in the
        documentation and/or other materials provided with the distribution.

    3.  Neither the name of the Broad Institute, Inc. nor the names of its
        contributors may be used to endorse or promote products derived from
        this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED “AS IS.”  BROAD MAKES NO EXPRESS OR IMPLIED
REPRESENTATIONS OR WARRANTIES OF ANY KIND REGARDING THE SOFTWARE AND
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original BSD-3-Clause terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `BSD-3-Clause` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `CELLPROFILER` (category: SCIENTIFIC LAB)
- **Upstream URL:** https://github.com/CellProfiler/CellProfiler
- **Pinned commit (SHA):** `c1d6426989d64f4dc9774aa246c7054a214a7d33`
- **Branch:** main
- **Pin provenance:** GitHub API commits/<branch> (response quoted in report). The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`24df4b10869c4288954018c7d5c09836aeb5a5092ffcbf37b706d703118307f1`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

