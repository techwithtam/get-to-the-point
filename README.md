# Get To The Point

Turn a detailed update, proposal or request into a message a busy reader can act on. This is for anyone who knows their work in depth and needs a decision from someone who has a few minutes to give it.

**[Download the skill ZIP](https://github.com/techwithtam/get-to-the-point/releases/latest/download/get-to-the-point.zip)** · [Read the skill](SKILL.md) · [See an example](examples/vendor-decision.md)

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

No plugins, code, API keys or account connections are required.

## What it does

Give it a draft, notes or a report, and tell it who will read the message. You get back:

- the message, opening with what is needed, why it matters and what happens without action
- your detail sorted into what stays in the message, what goes below it and what you keep ready
- the questions your reader is most likely to ask, with short answers
- the specific next step and who owns it
- a short decision record to send afterward, when you need one

Your facts stay as you wrote them, and anything it inferred is marked for you to check.

## Upload to Claude

1. Download the ZIP above. Keep it zipped.
2. In Claude, open **Customize > Skills**, then **+ > Create skill > Upload a skill**.
3. Upload `get-to-the-point.zip` and turn the skill on.
4. Open a chat and send the request below.

Claude requires **Code execution and file creation** to be enabled under **Settings > Capabilities**. A team administrator may control skill uploads. [Claude's upload instructions](https://support.claude.com/en/articles/12512180-use-skills-in-claude) cover those settings. Skills you upload also work in Cowork.

## Use in ChatGPT

1. Download the same ZIP and attach it to a ChatGPT Work chat that can open files.
2. Ask: "Unzip this file, read SKILL.md and use the skill on my draft."
3. Add the request below.

If your chat cannot open the ZIP, unzip it yourself and attach `SKILL.md`, or paste its contents. Saving a skill for reuse depends on your app and workspace. [OpenAI's skill documentation](https://learn.chatgpt.com/docs/build-skills) explains the supported skill environments.

## Install for Claude Code, Codex, Cursor and other agents

```bash
npx skills add techwithtam/get-to-the-point
```

## Start with your draft

> Get to the point on this draft. The reader is [who they are], and I need them to [what they need to do]. [Paste your draft.]

It works from what you give it, and you know your reader better than it does. Check the first three sentences before you send anything. The twelve-word sentence test is a starting point for you to adjust.

## Credits

The approach draws on [Project HEADWAY: Get To The Point](https://www.projectmanagement.com/webinars/1232762/project-headway--get-to-the-point), a webinar by Mark Mullaly on ProjectManagement.com. The wording here is original. See [NOTICE.md](NOTICE.md).

Created by [Tech With Tam](https://techwithtam.com). Released under the [MIT License](LICENSE).
