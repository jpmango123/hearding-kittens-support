# hearding-kittens-support coding instructions

## Focused testing — owner direction, November 6, 2026

Read [FOCUSED_TESTING.md](FOCUSED_TESTING.md) before choosing checks. Focused checks are the default; broaden for high-risk changes and once per affected release batch. This replaces older blanket run-everything requirements, while preserving product invariants and required CI checks.

For Numa's support/privacy site, check changed HTML, support/deletion links and mobile readability. Native app regression runs are unrelated to text-only site work.
