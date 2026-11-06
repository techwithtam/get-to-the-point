# Get To The Point

Rewrite a draft so a decision-maker understands the ask immediately.

Decision-makers have very little time. In the first few lines, they need to know what's happening, what's needed from them, and what their options are. This skill puts that first and keeps your supporting detail ready for questions.

Use it for status updates, business cases, escalations, executive summaries, and decision requests for executives, leaders, and managers.

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

`SKILL.md` holds the complete method, and the assistant needs no other file to run it.

No plugins, code, API keys, or account connections are required.

## What it does

Give it your draft, tell it who the decision-maker is, and say what you need from them. It returns four things:

- **The message.** It opens with what's needed, why it matters, and what happens without action. Your options follow, with the implications of each. If the decision-maker asked a direct question, the answer comes before the conditions.
- **Likely questions.** Supporting detail moves here, as answers you can give when asked. Decision-makers often test one detail to find out whether you know the work, and a clear answer builds confidence in the rest of your message.
- **What changed.** The skill lists everything it moved, split, or cut, so you can restore it.
- **Questions for you.** The skill asks you for any missing date, figure, or owner, and it marks anything it inferred.

Each message has one intent: to inform, to explore options, or to get a decision. When your draft does more than one, the skill separates them, because each takes a different kind of thinking and people need time to move between them.

After the reply, the skill can draft your follow-up. When the answer is a maybe, the follow-up asks for the next step. When the answer is clear, it records the decision, the next steps, and their owners, so everyone works from the same version.

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

Write everything down first, including the conditions and qualifications. The skill needs that detail to prepare the likely questions.

> Get to the point on this draft. The decision-maker is [role and relationship to me]. I need them to [decide, approve, or know something]. [Paste your draft.]

Review the message and anything marked as inferred before you send it.

## Credits

The method adapts ideas from [Project HEADWAY: Get To The Point](https://www.projectmanagement.com/webinars/1232762/project-headway--get-to-the-point), a webinar by Mark Mullaly on ProjectManagement.com. See [NOTICE.md](NOTICE.md).

Created by [Tech With Tam](https://techwithtam.com). Released under the [MIT License](LICENSE).
