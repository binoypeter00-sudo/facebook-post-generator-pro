# FACEBOOK POST GENERATOR PRO

**Version:** 1.0.0  
**Status:** Stable initial release  
**Primary language:** Malayalam  
**Market focus:** India  
**Platform:** Facebook

A standalone, Malayalam-first content-generation Skill for Facebook Pages, Groups, Marketplace, Reels, carousels, and content calendars.

## What this Skill does

- Creates original Facebook posts and captions.
- Writes factual product promotions and Marketplace listings.
- Produces educational, engagement, announcement, and brand-story posts.
- Generates Reel scripts and carousel slide copy.
- Builds 7-day and 30-day content calendars.
- Rewrites and repurposes supplied content for Facebook.
- Adapts to Malayalam, English, and bilingual requirements.
- Applies accuracy, trust, and editorial quality checks.

## Package structure

```text
facebook-post-generator-pro/
├── README.md
├── SKILL.md
├── CHANGELOG.md
├── LICENSE
├── references/
│   ├── post-formats.md
│   ├── hook-cta-library.md
│   ├── brand-voice.md
│   └── quality-and-safety.md
└── examples/
    └── sample-output.md
```

## Quick start prompts

- "ഒരു Facebook post തയ്യാറാക്കൂ: വിഷയം [topic], ലക്ഷ്യം comments."
- "ഈ product വിവരങ്ങൾ ഉപയോഗിച്ച് Malayalam promotional post എഴുതൂ: [details]."
- "എന്റെ Facebook Page-ന് 7 ദിവസത്തെ content calendar ഉണ്ടാക്കൂ."
- "ഈ draft മൂന്ന് വ്യത്യസ്ത ശൈലികളിൽ rewrite ചെയ്യൂ: [draft]."
- "ഈ ഉൽപ്പന്നത്തിനായി Marketplace listing തയ്യാറാക്കൂ: [verified details]."
- "ഈ വിഷയത്തിന് ഒരു Reel script-ും caption-ും തയ്യാറാക്കൂ: [topic]."

## Installation — Claude

This repository follows the simple folder-based Skill layout: the entry instructions are in `SKILL.md`, with supporting references and examples beside it.

1. Download the source from the [v1.0.0 release](https://github.com/binoypeter00-sudo/facebook-post-generator-pro/releases/tag/v1.0.0).
2. Extract the `facebook-post-generator-pro` folder.
3. Copy the Skill folder (the folder containing `SKILL.md`) into the Skills directory supported by your Claude environment.
4. Enable or select the Skill in that environment and test with a Quick start prompt.

For Claude Code, a project-level Skill can be placed under `.claude/skills/facebook-post-generator-pro/`; a personal Skill can be placed under `~/.claude/skills/facebook-post-generator-pro/`. Keep the `references/` and `examples/` folders with `SKILL.md`.

## Installation — Manus Cue / other Skill managers

1. Open your Manus Cue Skill manager.
2. Choose its GitHub import/connect option (if available).
3. Connect this repository: `binoypeter00-sudo/facebook-post-generator-pro`.
4. Select the repository root or the folder containing `SKILL.md`, according to the importer's folder-selection requirements.
5. Confirm that the reference files are included, then enable the Skill.
6. Test with a Malayalam Facebook post brief.

Manus Cue's exact UI/import flow can vary. This repository does not claim that Manus Cue has already been connected or that the Skill has been installed there.

## Important scope boundary

This is a content-generation Skill. It does **not** automatically publish, schedule, moderate, or analyse Facebook Page activity. Those capabilities require separate integrations, permissions, and workflows.

Always review final content before publishing. Confirm prices, stock, claims, dates, delivery terms, and contact details. Check current Meta policies and applicable local laws for regulated or restricted categories.

## Version history

See [CHANGELOG.md](CHANGELOG.md).

## License

MIT. See [LICENSE](LICENSE).

## Repository

https://github.com/binoypeter00-sudo/facebook-post-generator-pro
