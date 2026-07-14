# Hospital Supply Optimizer

Prioritizes synthetic clinical supply reorder decisions.

## What it includes

- deterministic sample data
- scoring and ranking logic
- command line report
- unit tests
- continuous validation workflow

## Run

```bash
python3 -m hospital_supply_optimizer.cli --input data/sample_inventory.json
```

## Test

```bash
python3 -m unittest discover tests
```
