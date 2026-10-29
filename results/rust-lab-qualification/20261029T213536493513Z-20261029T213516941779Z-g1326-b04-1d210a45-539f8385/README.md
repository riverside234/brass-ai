# Lab qualification results

Open `evidence/runner.json` first (when present), then each stage's `qualification.json` and logs. Large reports are gzip compressed.

`export-manifest.json` maps original evidence paths to portable files and hashes. Original receipts are byte-for-byte copies, including lab-local paths. This is review evidence, not a relocated executable qualification. Build products, models, replay payloads and runtime dependencies stay on the lab machine.
