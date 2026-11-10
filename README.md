# BenAI Token Saving Mods

A pack of Claude Code mods that cut token costs, made by **Ben AI** (YouTube channel: [Ben AI](https://www.youtube.com/@BenAI92)).

- Video: [Copy These 5 Claude Mods, Never Hit a Token Limit Again](https://www.youtube.com/watch?v=4d6OK7IGdBU)
- Official page: [Token Saving Mods Pack](https://benai.notion.site/Token-Saving-Mods-Pack-4111124570fe81728d6cc04294a399aa)

All credit goes to Ben AI. This is an unmodified copy of the pack, kept for personal use. Get the official version from the links above.

## Mods

| Mod | What it does |
|---|---|
| input-router | Haiku reads big files and connector results first; Claude gets short notes |
| effort-optimizer | Picks the effort level each prompt needs |
| model-router | Sends each subagent task to the cheapest model that can handle it (MIT, based on [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates)) |
| cache-clock | Counts down until the prompt cache goes cold, can keep it warm |
| handoff | At 250k tokens, writes a handoff and moves to a fresh chat |
| research-router | Keeps web research out of the main chat |
| efficient-browser-use | Shrinks or describes browser screenshots |
| mods | `/mods` pane to turn each mod on or off |
| savings-proof | `/savings` pane showing tokens saved |

## Install

See [INSTALL.md](INSTALL.md). The marketplace name is `token-saving-mods`.

## License

Only `plugins/model-router` has a license (MIT, see its `LICENSE`). The rest of the pack has no license; all rights belong to Ben AI.
