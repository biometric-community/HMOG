# HMOG

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FHMOG-181717?logo=github)](https://github.com/biometric-community/HMOG)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://www.cs.wm.edu/~qyang/hmog.html)

**HMOG** — tbiom catalog packaging for `hmog` (behavioral; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/HMOG
- **Upstream source**: http://www.cs.wm.edu/~qyang/hmog.html
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `hmog` |
| Category | `behavioral` |
| Access | `register` |
| Upstream homepage | http://www.cs.wm.edu/~qyang/hmog.html |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Hand Movement, Orientation, and Grasp dataset.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/HMOG.git
cd HMOG
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_hmog.sh
```

Place licensed archives under `projects/datasets/hmog/` (gitignored).

## Dataset structure

```text
HMOG/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://www.cs.wm.edu/~qyang/hmog.html
- Packaging: https://github.com/biometric-community/HMOG/issues
