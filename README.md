# Mealmaster

<p align="center">
  <img src="assets/mascot-mealmaster.svg" alt="Mealmaster robot mascot" width="220">
</p>


<p align="center"><strong>Practical weekly meal planning.</strong></p>

<p align="center">Simple dinner plans. Optional pantry tracking. A built-in planner that helps without taking over.</p>

---

This repository is the public download page for Mealmaster releases.
It is not the source code repository.

## Download

Get the latest Windows build here:

- [Latest release](https://github.com/bitofastickler/mealmaster-releases/releases/latest)

Download the main app file from the latest release:

- `Mealmaster.exe`

## What Mealmaster Does

- Creates a meal plan for as many dinners as you need, from 1 to 7
- Keeps household preferences simple and editable
- Supports optional pantry-aware planning
- Lets you favorite recipes and refine the week
- Stores your data locally on your machine

## Screenshots

### Weekly plan overview

![Mealmaster weekly plan overview](assets/screenshots/plan-overview.png)

### Recipe browser

![Mealmaster recipe browser](assets/screenshots/recipes-browser.png)

### Pantry tracking

![Mealmaster pantry tracking](assets/screenshots/pantry-tracking.png)

### Favorites and quick chat

![Mealmaster favorites and quick chat](assets/screenshots/plan-chat.png)

## Why It Exists

Mealmaster is built for the common problem of knowing roughly what your household likes but still not wanting to think through dinner every night.

The goal is not gourmet cooking.
The goal is getting to a workable week faster.

## Windows Setup

1. Download the Windows release files.
2. Run `Create-Mealmaster-DesktopShortcut.bat` to create the `Mealmaster` desktop button.
3. Open Mealmaster from the desktop shortcut.
4. On first launch, paste your own OpenAI API key when prompted if you want AI-backed planning.
5. If Windows shows a trust warning for an unsigned app, continue only if you trust the download source.

If you skip API setup, Mealmaster still works in standard planner mode without AI.

## Privacy

Mealmaster is designed for local use.
Your saved household, pantry, and planning data stay on your machine unless you choose to host or deploy the app somewhere else.

Some builds may support optional AI-backed planning behavior depending on configuration.
Public desktop use is designed around each user providing their own OpenAI API key locally.

## Support

Use the `Issues` tab for:

- install problems
- bug reports
- feature requests

Please do not post API keys, private household information, or other secrets in public issues.

## Terms

Mealmaster is free to download and use for personal or internal household use under the terms included with each release.
No commercial-use rights are granted through this repository or its releases.
This repository does not provide access to the private source code.

## Release Notes

Each release includes:

- what changed
- anything to know before updating
- known issues

## Look and Feel

Mealmaster is intentionally planner-first:

- one household
- one clear weekly plan
- pantry support when you want it
- quick conversational edits without turning the app into a general chatbot
