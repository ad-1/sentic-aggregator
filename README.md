# sentic-aggregator

sentic-aggregator service for the Sentic platform.

## Purpose

- extractor: consume raw-news and enrich URLs with full-text markdown
- aggregator: deduplicate, window, and publish enriched batches
- analyst: run war-room reasoning and produce analysis results

## Quick start

```bash
python3.13 -m venv .venv
.venv/bin/pip install -e '.[dev]'
pytest
```
