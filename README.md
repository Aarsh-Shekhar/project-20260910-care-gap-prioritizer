# Care Gap Prioritizer

Prioritizes synthetic care gaps for outreach queues.

## What it includes

- deterministic sample data
- scoring and ranking logic
- command line report
- unit tests
- continuous validation workflow

## Run

```bash
python3 -m care_gap_prioritizer.cli --input data/sample_members.json
```

## Test

```bash
python3 -m unittest discover tests
```
