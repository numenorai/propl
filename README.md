# propl wheels

Prebuilt Python wheels for the `propl` Prolog engine (source lives in a private repo). Wheels are attached to GitHub Releases here, indexed for uv/pip via GitHub Pages.

## Install

```toml
[project]
dependencies = ["propl>=0.1"]

[[tool.uv.index]]
url = "https://numenorai.github.io/propl/simple/"
```

Then `uv sync`.
