# Admin2x Security Basics

Source for https://help.admin2x.com, a free collection of consumer-level cybersecurity guides published by Admin2x, LLC.

Built with MkDocs and the Material theme. Articles are Markdown files under `docs/articles/`. Pushing to `main` builds and deploys the site automatically via GitHub Pages.

## Local preview

    python3 -m venv .venv && source .venv/bin/activate
    pip install -r requirements.txt
    mkdocs serve

## Adding an article

1. Create `docs/articles/<slug>.md` with a `title` and `description` in the front matter.
2. End it with `--8<-- "_includes/site-footer.md"` so every article carries the same footer.
3. Add it to `nav:` in `mkdocs.yml` and to the list on `docs/index.md`.
4. Commit and push to `main`.
