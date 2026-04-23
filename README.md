# Backrooms: Feline Mutant Start

A [Cataclysm: Dark Days Ahead](https://cataclysmdda.org/) mod that adds a post-threshold Feline mutant start to the [Backrooms] scenario.

## Features

- Extends the **Backrooms Dweller** start with forced **post-threshold Feline traits**:
  - THRESH_FELINE
  - FELINE_FUR
  - FELINE_EARS
  - FELINE_FLEXIBILITY
  - FELINE_LEAP
- Grants access to **all pre-threshold FELINE mutations** and **generic mutations** (e.g. Tough, Quick).
- **Automatically syncs** the mutation list with the latest CDDA experimental releases via GitHub Actions.

## Installation

1. Download the latest `backrooms_feline_mutant_start_*.zip` from the [Releases](../../releases) page.
2. Extract the zip into your CDDA `data/mods/` folder.
3. Enable **Backrooms**, **Extra Mut Scenarios**, and **Backrooms: Feline Mutant Start** when creating a new world.

## Requirements

- [Backrooms]
- [Extra Mut Scenarios]

## How It Works

A GitHub Actions workflow runs daily, fetches the latest CDDA release tag, and uses a shallow clone of the CDDA repository to filter mutations. Only **FELINE** and **generic** mutations are included. If changes are detected, a new mod release is automatically published.

## License

MIT License.