# Guild Crafting Orders (WoW Forever)

A small web app for a World of Warcraft: Forever guild (EU). Members list their characters' professions and post crafting or gathering orders that other members can claim, with an estimated ready time.

> Status: early development.

## Features (planned)

- Log in with Battle.net and import your WoW Forever characters
- Professions per character, including gathering (herbalism, mining, skinning, fishing)
- Crafting orders: pick a recipe, see the required reagents, post the order
- Gathering orders for raw materials, linkable to a crafting order
- Claim an order ("I'll do it") with a ready-by time, then mark it ready and delivered
- Discord notifications for new and claimed orders

## Data sources

- Professions, recipes, gathering and item data: [Data from ForeverDB.net](https://foreverdb.net)
- Characters, localized item names and icons: Blizzard Battle.net API

Game data is imported server-side into the app's own database and refreshed when a new game build is released.

## Disclaimer

World of Warcraft and Blizzard Entertainment are trademarks of Blizzard Entertainment, Inc. This project is not affiliated with or endorsed by Blizzard Entertainment or ForeverDB.
