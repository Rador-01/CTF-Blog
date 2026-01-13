# CTF Writeups

My personal CTF writeup blog built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

## Local Development

```bash
# Install dependencies
pip install -r requirements.txt

# Run local server
mkdocs serve
```

Then open http://127.0.0.1:8000 in your browser.

## Deployment

Push to `main` branch → GitHub Actions automatically builds and deploys to GitHub Pages.

## Adding New Writeups

1. Create a new folder under `docs/writeups/` for the CTF (e.g., `docs/writeups/picoctf-2026/`)
2. Add markdown files for each category (e.g., `forensics.md`, `web.md`)
3. Update the `nav` section in `mkdocs.yml` to include the new pages
4. Push to `main`

## Contributing

Contributions are welcome! If you'd like to add a writeup, fix a typo, or suggest improvements:

1. **Fork** this repository
2. **Create a branch** for your changes (`git checkout -b my-writeup`)
3. **Make your changes** and commit them
4. **Open a Pull Request** with a clear description of what you're adding

### Guidelines

- **Original content only** — Don't copy writeups from other sources without permission
- **Credit where due** — If your solution was inspired by someone else's work, mention them
- **Wait until CTF ends** — Never publish writeups for active competitions
- **Keep it educational** — Explain your thought process, not just the final solution

### What I'm Looking For

- Writeups for challenges I participated in but didn't solve
- Alternative solutions to existing writeups
- Corrections or improvements to explanations
- Better code snippets or tooling suggestions

## License

This project is licensed under the [MIT License](LICENSE).

You're free to:
- Use these writeups for learning
- Share and adapt the content
- Use the blog template for your own writeups

Just include attribution back to this repo if you reuse substantial portions.

## Acknowledgments

- Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
- Thanks to everyone in the CTF community who shares their knowledge