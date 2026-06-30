# skAIld marketplace

Claude Code plugin marketplace for **skAIld** — disciplined AI dev workflows for Claude Code.

## Install

```
/plugin marketplace add drophit/skaild-marketplace
/plugin install skaild-start@skaild        # free
/plugin install skaild-build@skaild        # paid (requires access)
```

Each plugin ships three model-tuned branches (`v4.6` / `v4.7` / `v4.8`); install the entry matching your Claude model. Paid plugins live in private repos — access is granted on subscription at https://skaild.com.

## What's inside

Every plugin includes the **foundation trio** — `/start` (session banner + workflow menu), `karpathy-guidelines` (coding discipline), and `/whats-new` (auto-changelog) — so no paid tier installs without the free value. On top of that:

| Plugin | Price | Adds |
|---|---|---|
| `skaild-start` | free | the foundation trio only |
| `skaild-plan` | [Click for pricing](https://skaild.com/#pricing) | `/quick-plan`, `/start-planning` |
| `skaild-build` | [Click for pricing](https://skaild.com/#pricing) | `/start-coding`, `/serve-worktree`, `/review-pr`, `/team-review`, `/create-pr`, `/merge-approved` |
| `skaild-ship` | [Click for pricing](https://skaild.com/#pricing) | `/pre-deploy`, `/light-deploy`, `/hotfix`, `/handoff`, `/close-session` |

The **Complete Bundle** ([click for pricing](https://skaild.com/#pricing)) grants plan + build + ship. Every plugin auto-installs its required dependencies (`superpowers`, `commit-commands`) on install.
