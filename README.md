# Iceland road status field guide

This repository contains a short, plain-language field guide for checking one
Iceland road segment before committing to a day plan.

The public documentation is built by Read the Docs with MkDocs. The guide does
not mirror live road data or make a route safe. It shows what to record from
the official road, weather and travel-safety services so that a vague
“the road looks fine” becomes a check someone else can repeat.

## Local preview

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

## Files

- `docs/index.md` — the field guide and decision matrix.
- `mkdocs.yml` — navigation and theme configuration.
- `.readthedocs.yaml` — reproducible Read the Docs build configuration.
- `requirements.txt` — pinned MkDocs version.

The original guide and configuration are released under the MIT licence.
