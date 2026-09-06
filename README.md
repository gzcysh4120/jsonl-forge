# jsonl-forge

Clean and split JSONL datasets for fine-tuning

Side project, maintained when I have time.

## Highlights

- Length filters keep the sweet spot
- Deterministic split with a seed
- Prints a stats summary you can eyeball
- Dedup by normalized instruction text

## Examples

```bash
python prep.py raw.jsonl --out-dir data/ --valid-ratio 0.1
```

## Installation

```bash
# stdlib only
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── Makefile
├── SECURITY.md
└── prep.py
```

## License

MIT - see [LICENSE](LICENSE).
