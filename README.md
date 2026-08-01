# SERC Skills

Open source [Claude Skills](https://support.anthropic.com/en/articles/12512180-getting-started-with-skills) for [Southeastern Reptile Conservation](https://southeastreptile.org). These capture Linda Nichols' writing voice and streamline the content SERC publishes across its platforms.

## Skills

| Skill | What it does | Triggers on |
|---|---|---|
| [linda-voice](linda-voice/SKILL.md) | Linda's writing voice and platform rules for all SERC content. Core tone, per-platform rules (Instagram, TikTok, Facebook, outreach email), wildlife and location privacy rules, and example endings. | Any request to write, draft, or edit content for Linda or SERC. |
| [serc-social-post](serc-social-post/SKILL.md) | Prompt template for social media posts. Asks a short set of questions, then drafts the post using `linda-voice`. | Any request to create a social post for Instagram, TikTok, or Facebook. |

`serc-social-post` builds on `linda-voice`, so install both for the best results.

## Install

Each skill is a folder containing a single `SKILL.md` file. To add one to [Claude.ai](https://claude.ai):

1. Zip the skill folder so the archive contains the folder and its `SKILL.md` (for example, `linda-voice/SKILL.md`).
2. In Claude, open **Settings → Capabilities → Skills**.
3. Choose **Upload skill** and select the zip.
4. Repeat for each skill you want.

To zip both skills from a clone of this repo:

```bash
zip -r linda-voice.zip linda-voice
zip -r serc-social-post.zip serc-social-post
```

Skills are also supported in Claude Code and the Claude Agent SDK. See [Getting started with Skills](https://support.anthropic.com/en/articles/12512180-getting-started-with-skills) for the current options.

## Roadmap

- **grant-writing** — a skill for drafting and tailoring grant applications in Linda's voice.

## License

[MIT](LICENSE) © Southeastern Reptile Conservation
