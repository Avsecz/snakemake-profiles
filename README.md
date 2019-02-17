## Snakemake profiles

Modified SLURM profile from <https://github.com/Snakemake-Profiles/slurm>.

### Changelog

- `threads` corresponds to `cpus-per-task` and not `ntasks`
- added support for `resources: gpu=X`

## Installation

```bash
git clone git@github.com:Avsecz/snakemake-profiles.git ~/.config/snakemake
```

## Usage with `snakemake`

```
snakemake --profile slurm
```