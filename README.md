# data-curation-observatory

Local-first data curation workflow using manifests, technical cards and CERTEZA/INFERENCIA/INCOGNITA reports.

Status: `STAGED_LOCAL_ONLY`. This staging repo is local-only until secret
scan, path scrub, claims scan, license review and ActionGate approval pass.

## What This Includes

- Provides generic templates for local data curation.
- Helps separate observed evidence, inference and unknowns.
- Produces review artifacts without touching input data.

## What This Excludes

See `PRIVATE_EXCLUSIONS.md`.

## License

MIT candidate; legal review still required before public release.

## Next Steps

- Add a synthetic sample folder.
- Add a manifest-generation smoke test.
- Run secret scan and path scrub before any push.
