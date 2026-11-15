<p align="center">
  <img src="./assets/onde-inference-logo.svg" alt="Onde Inference" width="80">
</p>

<h1 align="center">onde Scoop Bucket</h1>

<p align="center">
  <strong>Official <a href="https://scoop.sh/">Scoop</a> bucket for the <a href="https://github.com/ondeinference/onde-cli">onde CLI</a> from <a href="https://ondeinference.com/">Onde Inference</a>.</strong>
</p>

---

## Install

```powershell
scoop bucket add onde https://github.com/ondeinference/scoop-bucket
scoop install onde
```

## Upgrade

```powershell
scoop update onde
```

## Uninstall

```powershell
scoop uninstall onde
scoop bucket rm onde
```

## About

This bucket provides the native `onde` binary for Windows (amd64 and arm64). It auto-updates from [onde-cli releases](https://github.com/ondeinference/onde-cli/releases), so `scoop update` always fetches the latest version. For package docs and install options outside Scoop, see <https://ondeinference.com/cli>.

`onde` is a terminal UI for [Onde Inference](https://ondeinference.com). Sign up, sign in, manage your apps and model assignments, and run LoRA fine-tuning on Qwen models — all without leaving the terminal.

## Other installation methods

| Method | Command |
|--------|---------|
| npm | `npm install -g @ondeinference/cli` |
| pip | `pip install onde-cli` |
| uv | `uv tool install onde-cli` |
| cargo | `cargo install onde-cli` |
| Homebrew | `brew install ondeinference/onde` |

## Issues

Please report bugs against the main CLI repository:
[github.com/ondeinference/onde-cli/issues](https://github.com/ondeinference/onde-cli/issues)

## License

Dual-licensed under **MIT** and **Apache 2.0** —
see [onde-cli](https://github.com/ondeinference/onde-cli/blob/main/LICENSE-MIT) for details.
