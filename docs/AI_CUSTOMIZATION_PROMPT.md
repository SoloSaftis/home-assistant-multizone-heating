# AI customization prompt

Copy this prompt, attach the example files, and paste your completed entity worksheet below it.

```text
Customize this Home Assistant multi-zone heating project for my home.

Rules:
1. Use only entity IDs from my worksheet. Never invent an entity ID.
2. Generate complete YAML files, not partial snippets.
3. Keep physical away tracking independent from heating mode overrides.
4. Automatic: use the normal room schedule and activate 15 °C only after the configured away delay.
5. Force Away: activate the away temperature immediately.
6. Force Home: ignore away setback and use each room's chosen schedule. Do not rewrite schedule helpers or force 21 °C.
7. Preserve window protection, manual lockouts, sensor validation and thermostat min/max limits where configured.
8. Check YAML indentation, duplicate unique_id values, circular template references and invalid entity references.
9. Explain every replacement you made.

ENTITY WORKSHEET:
[paste completed worksheet here]
```
