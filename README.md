# ⚠️ This repository has moved

This project has been consolidated into the **[ai-plugins](https://github.com/matthew-a-carr/ai-plugins)** monorepo.

👉 **New location:** [`matthew-a-carr/ai-plugins/plugins/agent-skills`](https://github.com/matthew-a-carr/ai-plugins/tree/main/plugins/agent-skills)

## What changed?

`agent-skills`, `engineering-principles`, and the `claude-plugins` marketplace catalog have been merged into a single repository:

- **[`plugins/agent-skills/`](https://github.com/matthew-a-carr/ai-plugins/tree/main/plugins/agent-skills)** — 26 reusable agent skills (TDD, handoff, grilling, PR helpers, spec lifecycle, etc.)
- **[`plugins/engineering-principles/`](https://github.com/matthew-a-carr/ai-plugins/tree/main/plugins/engineering-principles)** — Engineering principles, patterns, and 3 skills

## Plugin installation

Plugin names are unchanged. Update only the marketplace URL:

```jsonc
{
  "extraKnownMarketplaces": {
    "matthew-a-carr": {
      "source": { "source": "github", "repo": "matthew-a-carr/ai-plugins" }
    }
  },
  "enabledPlugins": {
    "agent-skills@matthew-a-carr": true
  }
}
```

This repository is archived and will not receive further updates.
