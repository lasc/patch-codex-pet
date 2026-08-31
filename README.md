# Patch — Muscovy Duck Codex Pet

<p align="center">
  <img src="images/patch-in-codex.png" width="216" alt="Patch, a plush Muscovy duck, running as a Codex pet">
</p>

Patch is a curious plush Muscovy duck who tends ideas and patiently fixes what matters. This repository contains the complete Codex v2 pet, the ready-to-share ZIP, and its preview images.

## Download and install

1. Download [`Patch-Codex-Pet.zip`](downloads/Patch-Codex-Pet.zip).
2. Unzip it and copy the included `patch` folder into your Codex pets directory:
   - macOS/Linux: `~/.codex/pets/patch`
   - Windows: `%USERPROFILE%\.codex\pets\patch`
3. Open **Settings → Pets** in the Codex desktop app.
4. Select **Refresh**, choose **Patch**, then enter `/pet` to wake the duck.

The installed folder must contain both [`pet.json`](patch/pet.json) and [`spritesheet.webp`](patch/spritesheet.webp). Patch uses the v2 desktop-pet format with a `1536 × 2288` sprite atlas.

[Official Codex pet instructions](https://developers.openai.com/codex/pets)

## Animation previews

| Idle | Running | Waiting |
|:---:|:---:|:---:|
| ![Idle](images/previews/idle.gif) | ![Running](images/previews/running.gif) | ![Waiting](images/previews/waiting.gif) |
| **Waving** | **Jumping** | **Review** |
| ![Waving](images/previews/waving.gif) | ![Jumping](images/previews/jumping.gif) | ![Review](images/previews/review.gif) |
| **Running left** | **Running right** | **Failed** |
| ![Running left](images/previews/running-left.gif) | ![Running right](images/previews/running-right.gif) | ![Failed](images/previews/failed.gif) |

## Sprite QA

### Animation contact sheet

![Patch animation contact sheet](images/contact-sheet.png)

### Look directions

![Patch directional poses](images/look-directions.png)

## Integrity

SHA-256 checksums are recorded in [`CHECKSUMS.sha256`](CHECKSUMS.sha256).
