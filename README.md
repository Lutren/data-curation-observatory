# data-curation-observatory

Local-first data curation workflow using manifests, technical cards and CERTEZA/INFERENCIA/INCOGNITA reports.

Status: public-safe toolkit. Use it with synthetic or reviewed inputs first; do
not point it at private folders, secrets, paid content, or unreleased IP without
a separate release gate.

## Problems It Helps With

- Research folder chaos: turn loose notes and files into manifests and technical
  cards.
- Duplicated sources: preserve the useful ficha and mark redundant source files
  for review instead of copying everything forever.
- Mixed certainty: separate `CERTEZA`, `INFERENCIA`, and `INCOGNITA` so agents
  stop treating every paragraph as fact.
- Publication risk: create review artifacts before deciding what can become
  open source, paid product, internal research, or private material.

## What This Includes

- Provides generic templates for local data curation.
- Helps separate observed evidence, inference and unknowns.
- Produces review artifacts without touching input data.

## What This Excludes

See `PRIVATE_EXCLUSIONS.md`.

## License

MIT License.

## Next Steps

- Add a synthetic sample folder.
- Add a manifest-generation smoke test.
- Run secret scan and path scrub before any push.
