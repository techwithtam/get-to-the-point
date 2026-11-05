# Get To The Point

Get To The Point is a skill that rewrites a detailed draft for a senior reader. It moves your request and recommendation to the opening, then organizes your analysis behind them so the reader can decide without working through everything you know.

Project work produces a lot of detail, and the person who did the work tends to report all of it. A sponsor or executive usually has limited time for any one project, so a recommendation on page four can go unread and the decision gets delayed. The skill keeps your detail, because you will need it when a reader challenges a specific point, but it takes that detail out of the opening.

Use it for status updates, business cases, escalations, executive summaries, and decision requests.

**[Download the skill ZIP](https://github.com/techwithtam/get-to-the-point/releases/latest/download/get-to-the-point.zip)** · [Read the skill](SKILL.md) · [See an example](examples/vendor-decision.md)

## What you get

- **An opening the reader can act on.** The first few sentences state what you need, why it matters, and what happens if the reader doesn't act. For many readers, those sentences are enough to make the decision.
- **Supporting detail in the right place.** Facts the reader needs in order to act stay in the message. Your reasoning moves below the opening, and everything else moves into the prepared answers.
- **Prepared answers to likely questions.** Readers often test one detail to check that you know the work. The skill lists the questions this reader is most likely to ask, with answers drawn from your draft.
- **A defined next step.** The message ends with the action, its owner, and the due date. After the decision, the skill can draft a short written record for the people affected.

The skill keeps your facts and your voice, and it marks anything it inferred. If a date, figure, or owner is missing from your draft, it asks you for it instead of guessing.

No plugins, code, API keys, or account connections are required.

## Start with your draft

Give the skill your draft, tell it who will read the message, and state what you need that person to do.

> Get to the point on this draft. My reader is [role and relationship]. I need them to [decision or action]. [Paste your draft.]

Review the opening before you send the message, because the skill only knows what you have told it about your reader.

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

The method adapts ideas from [Project HEADWAY: Get To The Point](https://www.projectmanagement.com/webinars/1232762/project-headway--get-to-the-point), a webinar by Mark Mullaly on ProjectManagement.com. See [NOTICE.md](NOTICE.md).

Created by [Tech With Tam](https://techwithtam.com). Released under the [MIT License](LICENSE).
