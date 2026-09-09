# EnchantCalc — Minecraft Enchantment Calculator

A lightweight, GitHub Pages-ready Minecraft enchantment calculator.

## Features
- Responsive modern UI
- Bright/dark mode toggle with saved preference
- Item-specific compatible enchantments
- Search and level filters
- Selected enchantment chips
- Suggested combination order
- No build step or dependencies

## Run locally
Open `index.html` in a browser.

## GitHub Pages
1. Create a GitHub repository.
2. Upload all files while preserving the `data/` folder.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`.
5. Save and wait for GitHub Pages to publish.

## Important
The calculator currently uses a simplified heuristic for combination ordering. For a production-grade calculator, replace the calculation function with a complete Minecraft anvil-cost simulator that accounts for exact prior-work penalties, book costs, enchantment incompatibilities, and item/book combinations.
