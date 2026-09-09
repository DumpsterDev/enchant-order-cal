# EnchantCalc — Minecraft Enchantment Calculator

GitHub Pages-ready Minecraft Java Edition enchantment calculator.

## Included
- Full current enchantment list used by the calculator, including Soul Speed, Swift Sneak, Wind Burst, Density, Breach, Mending, etc.
- Item-specific compatibility, including hoe and mace.
- Incompatible-enchantment warnings.
- Java-style prior-work penalty tracking.
- Fresh enchanted books assumed to have zero prior-work penalty.
- 40-level Survival anvil cap.
- Dynamic search for the cheapest order when applying fresh single-enchantment books.
- Bright/dark mode saved in localStorage.

## GitHub Pages
Upload the repository contents, then use **Settings → Pages → Deploy from a branch → main → / (root)**.

## Calculation assumptions
The optimizer assumes a fresh target item and fresh single-enchantment books. It does not currently model damaged-item repair, renaming, or books that were themselves pre-combined. Java anvil mechanics are based on the documented prior-work and enchantment-cost rules.
