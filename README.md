# 2025.pyho.conference

This project is a documentation site for the 2025 PyHo Conference, built using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Features

- Modern, responsive documentation powered by MkDocs Material theme
- Easy navigation and search
- Customizable layouts and color schemes

## Getting Started

### Prerequisites

- Python 3.7+
- [pip](https://pip.pypa.io/en/stable/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hopythonusergroup/2025.pyho.conference.git
   cd 2025.pyho.conference
   ```

2. Create a Virtual Environment
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

2. Install dependencies:

   ```bash
   pip install mkdocs-material
   pip install -r requirements.txt
   ```

### Usage

To serve the documentation locally:

```bash
mkdocs serve
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

To build the static site:

```bash
mkdocs build
```

The generated site will be in the `site/` directory.

## Customization

Edit `mkdocs.yml` to change site configuration, navigation, and theme options.  
Add or edit Markdown files in the `docs/` directory for your content.

## Deployment

You can deploy the site to GitHub Pages:

```bash
mkdocs gh-deploy
```

## Resources

- [MkDocs Material Documentation](https://squidfunk.github.io/mkdocs-material/)
- [MkDocs Documentation](https://www.mkdocs.org/)

## License

This project is licensed under the MIT