# HiQ Battler · Character Archive

A responsive, static character gallery using all 65 cards from the supplied v10.2 characters.json, plus a searchable archive of all 60 items (v11 item effects updated October 28, 2026). Akifumi is listed as a 3-star libero.

## GitHub Pages

1. Upload **index.html**, **items.html**, and **.nojekyll** to the root of your GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose **main**, **/ (root)**, and **Save**.

GitHub will display your website URL once deployment finishes. No build command, dependencies, API keys, or bot files are needed. You can also open index.html directly in a browser.

## Browse

- Search names and card titles.
- Search Ultimate and skill names/effect text; extended notes are excluded. The effect scope dropdown limits search to one skill slot.
- Filter by school, role, position, star rating, and Ultimate cooldown. All active filters combine. Hybrid roles match every component role.
- Sort by rarity, name, school, cooldown, or any base stat.
- Open a card for full art, its icon, all eight stats in a vertical list with full-roster rankings, Ultimate, A/B/C skills, and expandable skill clarifications.
- Use the equipped-item dropdown to preview the nine items with immediate base-stat changes. Each visit starts with None selected; choices are remembered per character while that page remains open. Bonuses and penalties update stats and the total immediately. Items with only combat, turn, or skill-comparison effects are excluded from this dropdown.
- With an item equipped, rankings compare that build with all other unequipped cards. Selecting None restores base stats and rankings. The unused Power or Quick stat stays inapplicable. Extra item effects and drawbacks are shown in full; combat effects are not simulated.
- Read boon/bane recommendations below the abilities. Missing source guidance is labeled as not yet provided.
- Open the Items page for the complete list, including effects, eligibility, crafting shard costs, drop rates, and daily/weekly shard caps. Search names, effects, or eligible characters; filter by category or immediate stat changes.
- Rankings use competition ranking: highest value is rank 1, ties share a rank (for example 1, 1, 3). All 54 card variants are included; filters do not change rankings. Stats are unmodified base values.
- Ultimate cooldown appears in the Ultimate heading.
- Use the left/right buttons or arrow keys to navigate the current results. Escape closes a card or the mobile filter drawer.
- Save cards with their bookmark buttons; bookmarks are stored in the current browser.
- The page URL retains filters and can link directly to a card.

All artwork and character data are embedded in index.html. Item data is embedded in both pages. The gallery makes no external requests, uses no trackers, and runs entirely in the browser. Artwork is optimized as WebP. Base values and ability wording are preserved from the supplied character data, with the requested rarity correction for Akifumi. Only the selected item's immediate base-stat modifiers are applied in character details; merges, other build modifiers, and battle effects are not applied.

Character and artwork rights belong to their respective owners. This is an unofficial fan project.
