# mdfolio-app

My tiny static site generator, ~100 lines of Python

Small but I use it weekly.

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Installation

```bash
pip install -r requirements.txt
```

## Features

- Markdown posts with fenced code and tables
- Single template, plain str.format, no Jinja
- RSS feed generation
- Index page with post list by date

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Why

Needed this for myself; figured others might too.

## License

MIT licensed, see LICENSE.
