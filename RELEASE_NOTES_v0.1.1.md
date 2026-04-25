# Mealmaster v0.1.1

This update makes Mealmaster easier to use for smaller planning weeks.

## What Changed

- Added support for planning only 1 to 7 dinners instead of always forcing a full 7-dinner week
- Updated the plan builder with a `Dinners to plan` control
- Kept shopping lists tied only to the dinners in the current plan
- Added first-run AI setup so each user can save their own OpenAI API key locally
- Improved release packaging hygiene so generated build output stays out of the source repository

## What To Know Before Updating

- Existing saved plans still load normally
- New plans default to 7 dinners unless you choose a smaller count
- AI-backed planning is optional; standard planner mode still works without an API key
- Your household, pantry, recipes, and plan data stay local on your machine

## Known Issues

- Windows may show a trust prompt because the executable is unsigned
- Public desktop packaging is currently Windows-first
- Hosted multi-user sync is not part of this release

## Install

1. Download `Mealmaster-windows-v0.1.1.zip`
2. Extract the zip
3. Run `Mealmaster.exe` or use the included shortcut helper
4. Follow any normal Windows prompts for opening an unsigned app you trust

## Feedback

If you hit a bug or have a feature request, open an issue in the public releases repository.
