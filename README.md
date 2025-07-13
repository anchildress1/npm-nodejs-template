# anchildress1/npm-nodejs-template 🚀

Shaping the Ultimate Starter Kit Together

> [!IMPORTANT]
> This is a work in progress and may take a few weeks before I have anything truly useful, but feel free to use anything available as a starting point.
>
> 📝 I'm open to suggestions. Dive into the [Dev.to post](https://dev.to/anchildress11/calling-all-nodejs-wizards-what-would-you-add-to-the-ultimate-boilerplate-38aj) for more context!

---

## 🧠 Looking for Ideas, Not Code

Have thoughts on:

- What makes a JS template actually useful?
- Underrated tools or workflows that you swear by?
- Opinions about what should (or shouldn’t) be included in the starter pack?
- Quirky pain points only Node devs understand?

Drop a comment (when Discussions are enabled!) or [reply on Dev.to](https://dev.to/anchildress11/calling-all-nodejs-wizards-what-would-you-add-to-the-ultimate-boilerplate-38aj). Your input could help shape this into something everyone can steal... I mean, use. 😇

---

##

---

## 📦 Planned Features (So Far)

Here’s what I’ve mapped out, but this is absolutely up for discussion. Have a hot take? Let me know!

1️⃣ Basic scaffold
2️⃣ Husky with Jira support
3️⃣ Conventional commits & CHANGELOG generation
4️⃣ Prettier auto-format
5️⃣ ESLint validation (strict)
6️⃣ CSpell checks
7️⃣ Vitest for unit and integration testing
8️⃣ Documentation with GitHub Markdown
9️⃣ GitHub Copilot starter

---

## 🤔 What’s Already Here

### Very basic scaffold

- [`README.md`](./README.md) – Project overview and starter info (you’re reading it!)
- [`commitlint.config.js`](./commitlint.config.mjs) – ES6 Commit message linting rules (not yet enforced)
- [`package.json`](./package.json) – Node.js project manifest
- [`LICENSE`](./LICENSE) – License file
- [`index.js`](./index.js) – Entry point
- [`src/`](./src/) – Empty source code folder
- [`tests/`](./tests/) – Empty test folder

---

## Tooling wish list (all up for feedback!)

### 🦊 Husky & Jira

- Optional, enforced branch names with Jira keys
- Commit messages that keep the PMs happy
- Lintstaged, because why wait until CI to fail?

### 📝 Conventional commits & changelog (started)

- In this area, I'm still a noob, but the goal is to have a system that:
  - Auto-enforce conventional commit format
  - Handles Semver versioning
  - Automatically generates a CHANGELOG

### ✨ Prettier

- Runs on pre-commit. Because who doesn’t want their code auto-prettified?

### 🕵️ Strict ESLint

- Leaning toward Airbnb + Unicorn configs—unless you have a spicier suggestion
- Some aggressive custom rules that I can't live without
- No warnings allowed at commit time (too strict?)

### 🪄 CSpell

- Spell checking everywhere
- Project-specific dictionary - still figuring out the best spot for it

### 🧪 Vitest

- I'll find an example something to test, with coverage and reporting
- Docs somewhere explaining the “why” of testing, not just the “how”

### 📖 Documentation

- Planning for either a `/docs` folder, wiki, or full GitHub Pages site - opinions needed!
- Explainers for each tool, folder, and weird decision

### 🤖 GitHub Copilot

- Starter tips for using Copilot well (not just “type // todo and hope for magic”)
- Would love to crowdsource actual examples and best practices

> If you don't know me, check out my recent blog posts on [Dev.to](https://dev.to/anchildress1) - then that last one will make perfect sense :innocent:

---

## 🌱 How You Can Help (Without Writing a Single Line of Code)

- Share stories: What’s the most annoying thing about starting a new Node project?
- Suggest tools: What’s one library you can’t live without (and why)?
- Vote: What do you think is overkill, and what’s missing?
- Philosophize: What does a “good” JS backend template mean to you?

Drop your thoughts here once Discussions are enabled, or leave a comment on my [Dev.to post](https://dev.to/anchildress11/calling-all-nodejs-wizards-what-would-you-add-to-the-ultimate-boilerplate-38aj).

---

## 🛠️ Next Steps

[ ] Add a starting place in Discussions for people to share their thoughts
[ ] Finish the basics (as described above)
[ ] Iterate on feedback and turn this template into something worth forking

---

## 🙏 Thanks for Stopping By

Stay tuned, and thanks in advance for your brainpower! 🧠💡
— Ashley

P.S. If you’re here from the future and Discussions are already open... go wild!

> Most likely, future me forgot to update this README, so if you see any typos or outdated info, please open an issue. Thanks!
