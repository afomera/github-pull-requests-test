# github-pull-requests-test

A sandbox repository for testing pull-request automation: Maple Factory opens, reviews and merges pull requests here. Everything in it is a throwaway test fixture.

## Files

- `hello.txt` — a plain-text greeting that automated tasks edit; it currently says "hello from RG334-1".
- `config/locales` — Rails-style i18n YAML files for `en`, `de`, `es` and `fr`, each holding the same keys (`github.pull_request`, `hello`, `nested.key`, `two`), used to exercise translation-update pull requests.
