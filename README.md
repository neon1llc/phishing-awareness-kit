# Phishing awareness session kit

**Slides, exercises, and a one-page takeaway for an hour on scams and safer accounts.** For a team, a family, a senior center, or a classroom.

From [neon1](https://neon1.tech). *1 is glad to be of service.*

**Status:** stable. Accuracy and source updates only, no new modules for now.

---

## What people leave with

1. **Spot the pressure.** Most scams use hurry, fear, secrecy, or an unusual way to pay. Some build trust slowly first, so a calm, friendly message can still be one.
2. **Use the pause.** Hang up, look up the real number, and call back.
3. **Lock the front door.** Two-step sign-in is on for their email before they leave.
4. **Know who to tell.** A family code word, a way to report at work, and who to call if money is gone.

## What's inside

| Folder | What it holds |
|---|---|
| [`session/`](session/index.md) | The run sheet, a [slide deck](session/slides.md), and a [facilitator script](session/facilitator-script.md). |
| [`exercises/`](exercises/index.md) | Spot the scam, role-plays, the two-step sign-in lab, and a family code word activity. |
| [`handouts/`](handouts/index.md) | The [one-page takeaway](handouts/one-page-takeaway.md), a who-to-call card, a before-and-after quiz, and a feedback form. |
| [`guide/`](guide/index.md) | A field guide to eleven common scams. |
| [`audiences/`](audiences/index.md) | How to adapt the hour for families and seniors, teams, and students. |

## Running one

1. Read the [run sheet](session/index.md) and pick your [audience](audiences/index.md).
2. Swap two or three examples in [spot the scam](exercises/spot-the-scam.md) for ones your group has received, with names removed.
3. Turn the slides into a presentation (below) and print one takeaway per person.
4. Follow the [facilitator script](session/facilitator-script.md). Protect the two-step sign-in lab: it helps people even if they miss a scam later.

## The slides

[`session/slides.md`](session/slides.md) is written for [Marp](https://marp.app), an open-source Markdown slide tool. Use the Marp extension in VS Code, or the command line:

```
npx @marp-team/marp-cli session/slides.md --pdf     # or --pptx, or --html
```

## Related

- [Ready, Secure, Go](https://github.com/neon1llc/ready-secure-go): practice cards, playbooks, and teach kits. This kit links to its cards.
- [Household Tech Handbook](https://github.com/neon1llc/household-tech-handbook): for the person who looks after a family's devices and accounts.
- [SOC 2 Readiness](https://github.com/neon1llc/soc-2-readiness): training for companies. A session from this kit can count toward yearly awareness training.

## Checking a change

```
node tools/check.mjs    # front matter on every page, and no broken links
```

## Licenses

| What | License | What it means |
|---|---|---|
| Written material (everything except `tools/` and `.github/`) | [CC BY-SA 4.0](LICENSE) | Share, teach from, and adapt it, even commercially. Credit it as *"Based on Phishing Awareness Kit by neon1 (neon1.tech), CC BY-SA 4.0"* and share changes under the same license. |
| Code (`tools/`, `.github/`) | [MIT](LICENSE-CODE) | Use it for anything, keeping the copyright notice. |
| The Phishing Awareness Kit and neon1 names and the neon1 logo | Reserved | Not covered by either license. See [TRADEMARK.md](TRADEMARK.md). |

Phishing Awareness Kit is © 2026 neon1 LLC. Keep the [NOTICE](NOTICE) file in copies and adaptations.

Found something wrong or outdated? See [SECURITY.md](SECURITY.md). Want to help? See [CONTRIBUTING.md](CONTRIBUTING.md).
