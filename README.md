# quillstatic

Static blog generator: markdown in, tidy HTML out

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Install

```bash
pip install -r requirements.txt
```

## Highlights

- Single template, plain str.format, no Jinja
- Markdown posts with fenced code and tables
- RSS feed generation
- Index page with post list by date

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## License

MIT - see [LICENSE](LICENSE).
