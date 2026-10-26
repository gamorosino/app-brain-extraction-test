# BRAIN EXTRACTION APP TEST 10/26/26

Skull-strip a T1w volume with FSL's bet.

## Inputs

- `t1` (neuro/anat/t1w)

## Outputs

- `brain` (neuro/anat/t1w) -- 

## Usage

Brainlife.io: run via `faber-app-run`/`faber-app-pipeline` (once registered
with `faber-app-create`), or the web UI.

Locally (outside brainlife): copy `config.json.example` to `config.json`,
fill in real file paths, then run `./main` from this directory. `main` pulls
its own container (`singularity exec docker://...`) -- no local install of
the underlying tool needed, only Singularity itself.

Entrypoint: `brain_extract.py`

## Authors

- Gabriele Amorosino <g.amorosino@gmail.com>

#### MIT Copyright (c) 2026 Gabriele Amorosino
