# Job Finder

A desktop app that finds job openings worth your time, and helps you apply to them properly.

**[⬇ Download the latest version](../../releases/latest)**

---

## Who made this

I'm **Andrii Stakhov** — a Product Operations Manager. I'm from Ukraine and I live in Tallinn, Estonia.

I was applying for roles across Europe and losing entire evenings to the same three chores: scrolling
past listings that were never going to fit, re-reading the same rejections, and rewriting the same cover
letter for the tenth time. So I built something to do the boring parts. It's been my daily tool since.

This is a personal project. There's no team behind it, nothing is being sold, and there's nothing to
sign up for.

**LinkedIn:** [andrii-stakhov](https://www.linkedin.com/in/andrii-stakhov-888000310/) — that's me, and
the fastest way to reach me if something breaks or you want to ask what it does.

---

## What it does

**Finds openings.** It watches job boards across Europe on a schedule you set — the big remote boards,
company career pages, and national employment services — and collects whatever matches your searches.

**Reads them so you don't have to.** Every posting is weighed against your CV and a set of rules you
write yourself, in plain language: the roles you want, the ones you don't, where you can legally work,
what languages you speak. Each one comes back with a score, a short summary, and the specific reasons it
might not be for you. You get a shortlist instead of a firehose.

**Helps you apply.** For a job you like, it drafts a cover letter grounded in your real CV, suggests
targeted edits to that CV for the role, answers the screening questions employers ask, and exports both
CV and letter as proper PDFs. You can rewrite any of it by describing the change you want in a sentence.

**Keeps track.** It remembers where each application stands — applied, test task, interviews, offer or
rejection — so you can see what your effort is actually producing.

**Tells you when something good turns up.** Optional Telegram digest, strong matches only.

It does **not** apply to jobs for you. Everything is drafted for you to read, edit and send yourself.

---

## How it works, briefly

Job Finder runs entirely on your own computer. There's no account to create, no server of mine to sign
into, and no copy of your CV anywhere but your own machine.

The reading and writing are done by an AI service you choose and pay for directly — you paste your own
API key into the app's settings, and it stays on your machine. The app states plainly which of your data
goes to that service and where its servers are, so you can decide before switching anything on.

Beyond that, the only things it talks to are the job boards it's reading, Telegram if you turn the
digest on, and GitHub to check whether a newer version exists.

---

## Installing

**macOS** — open the `.dmg` and drag Job Finder to Applications. The first time you open it, right-click
the app and choose **Open** rather than double-clicking. macOS asks this once for any app that isn't
signed with a paid Apple Developer certificate, which this one isn't — it's a personal project, not a
registered developer account. After that it opens normally.

**Windows** — run the installer and choose **More info → Run anyway** when Windows flags an unrecognised
app, for the same reason. No administrator rights needed.

You'll need an API key from the AI service you want to use. The settings page links to where to get one.

The app checks this page on launch and can update itself in one click.

---

## What it doesn't do

- It doesn't submit applications on your behalf.
- It doesn't log into LinkedIn or any job board for you, and never asks for those passwords.
- It doesn't collect analytics, usage data, or anything else about you.
- It doesn't send your CV anywhere except the AI service you chose, when you ask it to do something.

---

## Status

Working, and in daily use by me. It's built around how I look for work, so expect opinions baked in. If
you try it and something is confusing or broken, tell me on
[LinkedIn](https://www.linkedin.com/in/andrii-stakhov-888000310/).

Free to use. Not open source, and not licensed for redistribution or reuse.

© Andrii Stakhov
