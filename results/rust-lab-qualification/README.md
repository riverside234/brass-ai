# Rust lab qualification results

The B01–B04 launcher automatically creates a new timestamped directory here after each run, including failures and deferred readiness. This directory is tracked by Git so results can be pushed on the lab machine and pulled here.

See [the current bundle instructions](../../distribution/rust-lab-g1326/README.md). Read `evidence/runner.json`, stage receipts and logs inside an export. `export-manifest.json` maps portable file paths and hashes; reports larger than 1 MiB are gzip compressed. The review copy excludes model weights, replay payloads and build products, and does not replace the original lab evidence used for admission.
