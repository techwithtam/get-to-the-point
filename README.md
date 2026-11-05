# Get To The Point

Put your request first and your detail behind it. Executives often read only the first few lines. If the request is not there, the decision waits.

This skill rewrites your draft that way.

**[Download the skill ZIP](https://github.com/techwithtam/get-to-the-point/releases/latest/download/get-to-the-point.zip)** · [Read the skill](SKILL.md) · [See an example](examples/vendor-decision.md)

## What you get

- **A new opening.** Three short sentences state what you need, why it matters, and what happens without action.
- **Your detail, reorganized.** The message keeps what the reader needs to act. The rest moves below the opening.
- **Prepared answers.** You get the questions your reader is likely to ask, with short answers.
- **A clear next step.** The message names the action, the owner, and the date.

The skill keeps your facts and your voice. If a date, number, or owner is missing, it asks you.

No plugins, code, API keys, or account connections are required.

## Start with your draft

> Get to the point on this draft. My reader is [who they are]. I need them to [what you need them to do]. [Paste your draft.]

Check the first three sentences before you send it.

## Upload to Claude

1. Download the ZIP above. Keep it zipped.
2. In Claude, open **Customize > Skills**, then **+ > Create skill > Upload a skill**.
3. Upload `get-to-the-point.zip` and turn the skill on.
4. Open a chat and send the request above.

Claude requires **Code execution and file creation** to be enabled under **Settings > Capabilities**. A team administrator may control skill uploads. [Claude's upload instructions](https://support.claude.com/en/articles/12512180-use-skills-in-claude) cover those settings. Skills you upload also work in Cowork.

## Use in ChatGPT

1. Download the same ZIP and attach it to a ChatGPT Work chat that can open files.
2. Ask: "Unzip this file, read SKILL.md, and use the skill on my draft."
3. Add the request above.

If your chat cannot open the ZIP, unzip it yourself and attach `SKILL.md`, or paste its contents. Saving a skill for reuse depends on your app and workspace. [OpenAI's skill documentation](https://learn.chatgpt.com/docs/build-skills) explains the supported skill environments.

## Install for Claude Code, Codex, Cursor, and other agents

```bash
npx skills add techwithtam/get-to-the-point
```

## What's in the ZIP

```text
get-to-the-point/
├── SKILL.md
├── README.md
├── LICENSE
├── NOTICE.md
├── agents/
│   └── openai.yaml
└── assets/
    └── icon.svg
```

## Credits

Based on [Project HEADWAY: Get To The Point](https://www.projectmanagement.com/webinars/1232762/project-headway--get-to-the-point), a webinar by Mark Mullaly on ProjectManagement.com. See [NOTICE.md](NOTICE.md).

Created by [Tech With Tam](https://techwithtam.com). Released under the [MIT License](LICENSE).
