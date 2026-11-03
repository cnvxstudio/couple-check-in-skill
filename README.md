# Five-minute couple check-in

A small, reusable skill for turning “we should talk more” into three conversation cards and an optional next step. It runs in an assistant’s conversation using the instructions in `SKILL.md`.

The cards move through three moments: notice something good, make room for an everyday preference or difficulty, and choose something small to discuss. Each person can pass. Questions adapt to a light, weekly or next-week conversation without assuming marriage, children or a shared home.

## Install

For agents supported by the skills CLI:

```sh
npx skills add cnvxstudio/couple-check-in-skill
```

Or copy `SKILL.md` into the skill location documented by your assistant. This repository contains one skill, named `ccq-five-minute-check-in`.

## Try it

- “Give us a gentle five-minute check-in.”
- “Make it playful and keep it to two minutes.”
- “Give us another round with fresh questions.”
- “Turn those cards into plain Markdown I can copy.”

A typical round invites one ordinary moment to repeat, one manageable way to make a busy day easier, and one inexpensive thing to look forward to. The skill supplies a brief turn-taking instruction with each question and leaves the follow-up optional.

## Working boundaries

The workflow focuses on everyday conversation. The instructions ask the assistant to use the current conversation, avoid claims about an absent partner’s thoughts, and leave suggested agreements unconfirmed until the people involved agree. They also tell the assistant to avoid saving personal answers through tools, contacting a partner or creating reminders. This package contains no executable code or credential requirements.

## Project reference

Maintained by the maker of [Couple Compatibility Quiz](https://couplecompatibilityquiz.com/), which provides free browser quizzes and conversation-question collections. That link is an optional reference; using the cards does not require a site visit. The skill does not append a promotional footer to its answers.

## License

MIT No Attribution (MIT-0). See [LICENSE](LICENSE).
