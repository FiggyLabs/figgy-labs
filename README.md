# Figgy Labs

Tools for teams who make decisions in chat and lose them by Friday.

Built local-first. Open source. No accounts required.

---

## Tools

### [✅ Settled](https://github.com/FiggyLabs/slack-thread-to-decisions-tool)
**Turn messy Slack threads into clean decision records.**

Paste a thread. Get back what was decided, who owns it, why, and what happens next — in seconds, on your machine.

```bash
python3 settled.py --file thread.txt
```

---

### [📌 Stamped](https://github.com/FiggyLabs/stamped)
**Record decisions once. Never argue about them again.**

Log a decision in 10 seconds. Pull it up in 2 when someone forgets. Stores everything locally in plain JSON — nothing leaves your machine.

```bash
python3 stamped.py add "Stripe approved. Owner: Tom. Go-live: April 1st."
python3 stamped.py find stripe
```

---

## How they work together

Settled reads the chaos in your Slack thread and extracts the decision. Stamped keeps it permanently so no one can claim it never happened.

---

## Philosophy

- Local-first — your data stays on your machine
- Zero dependencies where possible
- Single-file tools you can read and trust
- Free forever for personal use

---

## License

MIT
