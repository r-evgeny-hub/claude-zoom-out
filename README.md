# Zoom Out — A Claude Skill for Holistic Thinking

AI is good at decomposing problems and poor at seeing them whole. **Zoom Out** is a small Claude skill that shifts the model out of execute mode into something closer to reflection. It works by changing the model's state, not by instructing it to "think wider" — that approach doesn't work.

---

## What it's for

You've asked Claude for help, gotten a technically correct answer, and felt it missed the point. This skill triggers a brief moment where the model looks at the whole situation instead of just the task, often surfacing connections you were missing from inside your own framing.

## What makes it different from other prompting techniques

Standard prompting techniques improve reasoning inside a task. Zoom Out switches the model up a level — from execution to observation.

The skill does three things:

- **Removes the executor frame** ("I don't need advice, I need you to actually think")
- **Removes fear of being wrong** ("there are no wrong conclusions")
- **Shifts focus from task to situation** ("what is the whole here? Not the task itself")

---

## Installation

Pick the path that matches your setup.

### Download and install

1. Click [`SKILL.md`](SKILL.md) above
2. Click the download button (top right of the file view)
3. Install it in your Claude interface

### Claude Code (command line)

```bash
git clone https://github.com/r-evgeny-hub/claude-zoom-out ~/.claude/skills/zoom-out
```

Restart your Claude Code session. The skill activates automatically on a trigger phrase.

### Any LLM (no install)

1. Open [`SKILL.md`](SKILL.md)
2. Copy everything from `# Zoom Out` to the end of the file
3. Paste it at the top of your message, then type your question below

---

## Trigger phrases

The skill activates automatically when you say something like:

- "What am I missing?"
- "Zoom out"
- "Step back"
- "Look at the big picture"
- "Connect the dots"
- "Am I overthinking this?"
- "I feel stuck"
- "We're going in circles"

---

## When it helps

- **Strategic decisions** where you're deep inside the framing and can't see out
- **Debugging your own thinking** when you suspect you're in a loop
- **Reviewing a plan** before committing — catches what structured review misses
- **Pre-human evaluation in agent pipelines** — a "zoom out" check before the human-in-the-loop stage, catching blind-spot errors that structured evaluation doesn't see

---

## Author

Built by **Evgeny Rodionov**.

- GitHub: [@r-evgeny-hub](https://github.com/r-evgeny-hub)
- LinkedIn: [evgeny-rodionov](https://linkedin.com/in/evgeny-rodionov/)

Issues, ideas, and counter-examples are welcome — open an issue or reach out on LinkedIn.

## License

[MIT](LICENSE). Use it, modify it, ship it commercially — just keep the copyright notice.
