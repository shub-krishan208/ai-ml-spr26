# important installations

**Setup:**

```bash
# MacOS
uv sync

# quarto
brew install --cask quarto
# graphviz (system file) -> however not using it anymore
brew install graphviz # (optional)

# tex for pdf rendering
uv run quarto install tinytex

uv run quarto check

# Linux
uv sync
yay -S quarto
uv run quarto install tinytex
uv run quarto check

```