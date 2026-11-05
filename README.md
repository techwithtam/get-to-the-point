# Get To The Point

Rewrite a long update, report, or request so your reader can act on it in minutes. This is for when you've done all the work, written it all down, and the reply still asks what you need from them.

I built it after I wrote a detailed review for a client's executives. The detail was good, but they had to read too much to find what I needed from them. So I moved the detail behind a one-page decision brief, and this skill does the same for your work.

**[Download the skill ZIP](https://github.com/techwithtam/get-to-the-point/releases/latest/download/get-to-the-point.zip)**
· [Read the skill](SKILL.md) · [See an example](examples/vendor-decision.md)

The ZIP contains the complete skill folder:

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

No plugins, code, API keys, or account connections are required.

## What it does

Give it your draft or notes and tell it who's reading. You get back:

- a rewrite that opens with what you need, why it matters, and what happens if they don't act
- the questions your reader will probably ask, with short answers ready
- a list of what it moved or cut, so you can restore anything you want to keep
- the next step and who owns it
- a short record of the decision to send afterward, when you need one

It keeps your facts and your voice, and it marks anything it inferred. If a date, number, or owner is missing, it asks you.

## Upload to Claude

1. Download the ZIP above. Keep it zipped.
2. In Claude, open **Customize > Skills**, then **+ > Create skill > Upload a skill**.
3. Upload `get-to-the-point.zip` and turn the skill on.
4. Open a chat and send the request below.

Claude requires **Code execution and file creation** to be enabled under **Settings > Capabilities**. A team administrator may control skill uploads. [Claude's upload instructions](https://support.claude.com/en/articles/12512180-use-skills-in-claude) cover those settings. Skills you upload also work in Cowork.

## Use in ChatGPT

1. Download the same ZIP and attach it to a ChatGPT Work chat that can open files.
2. Ask: "Unzip this file, read SKILL.md, and use the skill on my draft."
3. Add the request below.

If your chat cannot open the ZIP, unzip it yourself and attach `SKILL.md`, or paste its contents. Saving a skill for reuse depends on your app and workspace. [OpenAI's skill documentation](https://learn.chatgpt.com/docs/build-skills) explains the supported skill environments.

## Install for Claude Code, Codex, Cursor, and other agents

```bash
npx skills add techwithtam/get-to-the-point
```

## Start with your draft

> Get to the point on this draft. My reader is [who they are], and I need them to [what you need them to do]. [Paste your draft.]

Read the first three sentences yourself before you send it. You know this reader, and the skill only knows what you told it. The twelve-word sentence check is a starting guess for you to adjust.

## Credits

The approach adapts ideas from [Project HEADWAY: Get To The Point](https://www.projectmanagement.com/webinars/1232762/project-headway--get-to-the-point), a webinar by Mark Mullaly on ProjectManagement.com. The skill is written in my own words. See [NOTICE.md](NOTICE.md).

Created by [Tech With Tam](https://techwithtam.com). Released under the [MIT License](LICENSE).
