# homebrew-github-agent-cli

Homebrew tap for [github-agent-cli](https://pypi.org/project/github-agent-cli/) — a repository and
wiki steward for GitHub: one command per documentation job, no runtime dependencies.

## Install

```bash
brew install paulmann/homebrew-github-agent-cli/github-agent-cli
ghagent --version        # github-agent 1.2.2
```

The formula builds the published sdist into a virtualenv with `python@3.13`, so no pip is involved.
`brew upgrade` picks up new versions; `livecheck` reads the PyPI JSON API.

## Verify

```bash
brew test paulmann/homebrew-github-agent-cli/github-agent-cli
```

## Other install paths

`uv tool install github-agent-cli`, `pipx install github-agent-cli`, `pip install github-agent-cli`,
the Windows bundle and the reusable GitHub Action are documented in the
[main repository](https://github.com/paulmann/github-agent).

## License

MIT