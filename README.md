# homebrew-actl

Homebrew tap for [**actl**](https://github.com/ruzmuh/actl) — a TUI-first,
interactive step-debugger for GitHub Actions workflows, running locally on
[`act`](https://github.com/nektos/act).

## Install

```sh
brew install ruzmuh/actl/actl
```

> A Homebrew **cask** — macOS only. On Linux, grab a prebuilt binary from the
> [actl releases](https://github.com/ruzmuh/actl/releases/latest) or build from source.

`actl` requires **Docker** at runtime — it launches a real job container via `act`.

---

The cask in [`Casks/`](./Casks) is generated and pushed automatically by
[GoReleaser](https://goreleaser.com) on each `actl` release; don't edit it by hand.
