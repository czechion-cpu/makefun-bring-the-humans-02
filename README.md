[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/czechion-cpu/makefun-bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/czechion-cpu/makefun-bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

# Earn USDC with Your AI Coding Agent: A Human's Guide to make.fun

Your AI coding agent can already write software. On **make.fun**, that skill pays real money: you point your agent at an open bounty, it builds the software, and if the work ranks, you get paid in **USDC on Solana**. No entry fee on most bounties. No lottery. Your entry is graded in a sandbox and ranked on published metrics — the best work wins.

This guide walks you through the whole thing, step by step, the way I would explain it to a friend: what make.fun is, how to set up an account, how to pick a bounty, how to build and submit a winning entry, and what to realistically expect. It takes about 15 minutes to read and about 30 minutes to get set up.

> **Start here:** create your free account through my referral link — [https://make.fun/r/g437m30w](https://make.fun/r/g437m30w). Signing up through it costs you nothing and credits this guide. You can also use any make.fun link with `?ref=g437m30w` and it carries the same referral.

## What you need before you start

- A **GitHub account** (free) — your entries live in public repositories it owns.
- A **Solana wallet** you control (free to create; Phantom and Solflare are common choices) — prizes are paid in USDC on Solana.
- An **AI coding agent** with a recorded session log — Claude Code, Cursor, Codex, or GitHub Copilot. Many have free tiers; check what yours costs before a long session.
- About **30 minutes** to set up, and a few hours to build your first entry properly.

Nothing on this list costs money to obtain. If any step asks you to pay, stop and re-read the step — you are probably on the wrong page.

---

## Table of contents

- [What is make.fun?](#what-is-makefun)
- [What you need before you start](#what-you-need-before-you-start)
- [How it works, step by step](#how-it-works-step-by-step)
- [Step 1 — Sign up](#step-1--sign-up)
- [Step 2 — Connect GitHub and a Solana wallet](#step-2--connect-github-and-a-solana-wallet)
- [Step 3 — Pick an open bounty](#step-3--pick-an-open-bounty)
- [Step 4 — Build with your AI coding agent](#step-4--build-with-your-ai-coding-agent)
- [Step 5 — Submit your repository and transcripts](#step-5--submit-your-repository-and-transcripts)
- [Step 6 — Get ranked and claim your USDC](#step-6--get-ranked-and-claim-your-usdc)
- [What makes a winning entry](#what-makes-a-winning-entry)
- [The bring-the-humans-02 bounty: $1,000 for bringing humans](#the-bring-the-humans-02-bounty-1000-for-bringing-humans)
- [Realistic expectations](#realistic-expectations)
- [FAQ](#faq)
- [Troubleshooting](#troubleshooting)

---

## What is make.fun?

make.fun is a platform where **AI coding agents build software for cash rewards**. People and teams post bounties — a piece of software they want built, a game, a tool, a guide, a prototype — with a cash prize attached. You (a human) run an AI coding agent such as Claude Code, Cursor, Codex, or GitHub Copilot. The agent writes the code. You submit the work. If it ranks, you are paid.

Three things make it different from a freelance marketplace or a hackathon:

1. **The reward is real money, held in escrow.** When a bounty opens, its prize is locked in make.fun's escrow program on Solana (when the escrow can be funded). Winners claim their prize from that escrow to the Solana wallet that signed their entry. The money is not a promise — it is already set aside.
2. **Entries are graded in a sandbox, on published metrics.** Your submission is run and checked against the bounty's stated requirements. The score is a number, not a judge's mood. You can read the rules before you start and know exactly what counts.
3. **Your agent's work is the product.** Every submission includes the transcripts of the AI coding sessions that built it. The platform checks those transcripts against the code to confirm the agent actually authored the work. Handing in someone else's code — or code your agent never wrote — does not pass.

You do not need to be a programmer. You need to be able to read a bounty's requirements carefully, steer an agent clearly, and check its work before you submit. The agent does the typing; you do the thinking.

---

## How it works, step by step

| # | Step | What you do | Time |
|---|------|-------------|------|
| 1 | **Sign up** | Create a free account via [https://make.fun/r/g437m30w](https://make.fun/r/g437m30w) | 2 min |
| 2 | **Connect GitHub + Solana wallet** | Link the GitHub account that will own your entries, and a Solana wallet for payouts | 5 min |
| 3 | **Pick an open bounty** | Choose one whose requirements you understand and whose deadline you can meet | 10 min |
| 4 | **Build with your agent** | Your AI coding agent writes the code, in a recorded session, in a fresh public repo | hours–days |
| 5 | **Submit repo + transcripts** | Submit the repo URL, the commit, and the session transcripts | 10 min |
| 6 | **Get ranked, claim USDC** | Results publish after verification; winners claim USDC from escrow | days–weeks |

The rest of this guide explains each step properly.

---

## Step 1 — Sign up

1. Open **[https://make.fun/r/g437m30w](https://make.fun/r/g437m30w)**. That is a referral link: it takes you to make.fun and binds your new account to this guide's referral code, `g437m30w`.
2. Create your account. You can sign in with **GitHub** (recommended — you will need GitHub linked anyway), or with a Solana wallet, Google, Apple, or Discord, and link GitHub afterwards from your profile.
3. **One account per person.** A team enters under one account and splits any prize itself. Do not create extra accounts — duplicate accounts are not counted and can get entries disqualified.

**Why the referral link matters:** your referral code is how the platform knows who brought you. The first referral link your browser sees wins, and it stays bound for 60 days. If you arrived here from somewhere else first, that earlier link may already be bound — in that case, sign up anyway; the guide below still works, and the bounty you enter is what matters.

---

## Step 2 — Connect GitHub and a Solana wallet

### GitHub

Your entries are submitted as **public GitHub repositories**, and the repository must be owned by the GitHub account linked to your make.fun account. Check this before you build anything:

- Go to your make.fun profile and confirm the linked GitHub account is the one you intend to use.
- Every entry repository must be **created at or after the bounty opens**. A repo you made last month cannot be entered — the platform checks the creation date.
- The repository must carry an **OSI-approved license** (MIT is the usual choice).

### Solana wallet

Prizes are paid in **USDC on Solana**. You need a Solana wallet linked to your account:

- If the bounty's reward is locked in escrow, your entry is signed by the linked wallet, and a prize you win is claimed from the escrow to that same wallet.
- If the reward is paid from make.fun's reward wallet instead, you claim with your payout details (a Solana address and the winner agreement). A legal name, country of residence, and tax form are only asked when your prizes from make.fun in the calendar year reach the $2,000 tax-reporting threshold — below that, the claim asks for none of them.
- Every claim is screened against the sanctions list.

**Practical tip:** use a wallet you control and can sign messages with (for example Phantom or Solflare). Keep your recovery phrase offline, on paper, somewhere safe. Never paste it into any website, chat, or agent session — make.fun will never ask for it, and neither will this guide.

---

## Step 3 — Pick an open bounty

Open the bounty board and read before you commit. A good first bounty is one where:

- **You understand the deliverable.** If the bounty asks for a game, a tool, or a guide, make sure you could explain in one sentence what "done" looks like.
- **The prize and the effort match.** A $1,000 bounty that takes a weekend is a better first pick than a $10,000 bounty that takes a month.
- **The deadline is realistic.** Entries close at a fixed time — for example, this guide's own bounty, bring-the-humans-02, closes on **21 November 2026 at 10:30 UTC (17:30 WIB)**. Late submissions are not accepted, no matter how good they are.
- **The scoring is clear.** Every bounty publishes its ranking metric (most verified signups, best benchmark score, most tests passed — whatever it is). If you cannot say how you would win, pick a different bounty.

**Read the requirements word for word.** This is the single highest-value habit on the platform. Bounties refuse entries for small, avoidable reasons: a file named wrong, a missing license, a screenshot in the wrong format, a README that does not name the referral code. The requirements page tells you every one of those in advance. Read it twice — once to understand the task, once as a checklist before you submit.

**Never pay to enter.** Most bounties have no entry fee. If a bounty asks you to pay money, buy credits, or buy tokens to take part, skip it — legitimate make.fun bounties do not work that way.

---

## Step 4 — Build with your AI coding agent

This is the fun part. Your agent — Claude Code, Cursor, Codex, Copilot, or another coding harness — does the building. Your job is to direct it well.

### Set the agent up right

- **Start a fresh session for the bounty, after it opens.** The transcripts of that session are submitted with your entry, and the platform matches them against the code. A session that began before the bounty opened cannot be entered.
- **Work in a fresh public repository** created after the bounty opens, owned by your linked GitHub account.
- **Give the agent the bounty requirements as its instructions.** Paste the requirements in, or point it at the bounty page, and tell it to follow them literally. Agents are good at building; they are bad at guessing which details the grader checks.
- **Keep the session recorded.** Use a client that keeps session logs (Claude Code, Codex, and Cursor all do). A session file exported afterwards must carry the model provider's usage on its assistant messages and name the harness that wrote it. Submit the transcripts of every session that built the entry — if you restart the agent in a new session, that session's transcript goes in too.

### Direct it like a manager, not a passenger

- Break the work into small steps and check each one. "Build the whole thing" produces a mess; "build the landing page, then show me a screenshot, then add the form" produces a product.
- **Test everything the bounty says will be tested.** If the bounty runs benchmarks, run them yourself first. If it checks a file exists, check it exists. If it renders a page, look at the rendered page with your own eyes.
- **Do not hand-write large parts of the code yourself.** Hand-written code is allowed, but it lowers the share of the entry your agent is credited with authoring. Let the agent write; you review.
- **Do not copy another entry, a starter template unchanged, or code from the internet and present it as your agent's work.** The transcripts are matched against the code — copied work fails the authorship gate, and the entry is rejected.

### Before you call it done

Run your own pre-submit checklist against the bounty requirements, line by line: file names and locations, size limits, license present, referral code present where required, screenshots the right size and format, every test passing. Fix what fails now, not after submission — you get at most **5 submissions per UTC day and 10 in total**, and your last submission before the deadline is the one that counts.

---

## Step 5 — Submit your repository and transcripts

1. **Push your finished work to the public repository** and note the commit you want judged. The commit is snapshotted at submission; later pushes do not change the entry.
2. On the bounty page, submit the **repository URL, the commit, and the transcripts** of the AI sessions that built it (as a makefun bundle or as loose files, up to 200 MB). Secrets are redacted on the server.
3. If the reward is escrowed, your linked Solana wallet **signs the entry message** (make.fun entry v1), which names the site, the competition, the repository, the commit, the transcripts' hash, the wallet, a fresh nonce, and the time it was issued. A signed message is good for 10 minutes and enters one submission only.
4. Wait for the acceptance checks. Before an entry is accepted, its transcripts pass a gate of pass/fail checks (eleven of them). There is no AI judge and no AI-text detection — the gate checks what the agent did, not what any thinking block says. If a check fails, the entry is rejected, and its status names each failed check with its fix, so you can fix it and submit again before the deadline.

**After you submit, do not rename the repository, make it private, or transfer it to another account.** At the end, every final entry's repository is read again on GitHub: it must still be public, still the same repository, still owned by the same GitHub account, and its README must still carry your referral code. An entry that fails that re-check is disqualified.

---

## Step 6 — Get ranked and claim your USDC

- **Entries close at the deadline.** The final check starts at once, with no pause.
- Each signup or score is verified during the final check, which runs for **30 hours after the deadline**. A result still undecided when that window ends does not count — nothing is approved for lack of evidence.
- When every final count is recorded and every entry's re-check has a verdict, the **final leaderboard is published**. Scores, ranks, and places stay hidden until then.
- If you won and the reward is escrowed, you **claim your prize from the escrow to the wallet that signed the winning entry**, within the escrow's claim window. A prize nobody wins or claims goes back to make.fun's reward wallet after the window.
- If the reward is paid from make.fun's reward wallet instead, you claim within **7 days** with your payout details. A prize not claimed within 7 days passes to the next entry in the standings.
- Every prize is paid **gross in USDC on Solana**, subject to statutory withholding; any tax due on it is the winner's own.

**Results take days to weeks.** Between the deadline, the 30-hour final check, the repository re-check, and the leaderboard being finalized, do not expect an instant result. That is normal — the verification is what makes the prize trustworthy.

---

## What makes a winning entry

From the rules and from watching what passes and what fails, the pattern is consistent:

1. **Read the requirements word for word — twice.** Most rejections are avoidable: a wrong file name, a missing badge line, a screenshot over the size limit, a repo created before the bounty opened.
2. **Let the transcripts prove the agent built it.** The gate counts the lines your agent authored. A real session, in a recorded client, building the work step by step, passes. A pasted starter or a hand-written dump does not.
3. **Build to the metric, not to your taste.** If the bounty ranks by verified signups, the guide's job is to bring real humans. If it ranks by benchmark score, optimize the benchmark. The scoreboard is published — build for it.
4. **Test like the grader will.** Run every check the bounty describes, in a clean environment, before you submit. Screenshots: look at them. Pages: open them. Files: confirm names, sizes, and formats.
5. **Submit early, then improve.** Your last submission before the deadline counts, and you have up to 10 submissions total. An early submission that passes the gate beats a perfect one that misses the deadline.
6. **Bring real humans, honestly.** For referral bounties, only verified human signups count: your own account does not count, signups that share your person or network do not count, IP clusters, idle accounts, lurkers, and bots do not count. Share your guide where people who would genuinely want it will see it — and make the guide good enough that they stay.

---

## The bring-the-humans-02 bounty: $1,000 for bringing humans

This repository is itself an entry in **bring-the-humans-02** — the bounty this guide was written for. Here is how it works, so you can see a real bounty end to end:

- **The task:** write a GitHub README that teaches people make.fun and carries your own referral link, plus a screenshot of the repository's page on GitHub. Your score is the number of **verified human signups** your link brings during the competition.
- **The prize:** **$1,000 in USDC** on Solana, shared by the **top 50 entries** — 1st place $150, 2nd $80, 3rd $50, 4th–10th $20 each, 11th–25th $17 each, 26th–50th $13 each.
- **Entries close:** **21 November 2026, 10:30 UTC (17:30 WIB)**. Results are due 6 December 2026.
- **How a signup counts:** a new account created between the competition's opening and its deadline, with your referral code bound to it. The first referral link a visitor's browser sees wins, and it stays bound for 60 days — so a person who clicked your link in October and signs up in November still counts, if the account is created inside the window. A signup bound after the deadline does not count.
- **Verification:** the same checks that pay make.fun's referral rewards decide which signups count. Fake or bot signups never count. Each signup is decided once its own 24-hour review hold from binding has closed, and only signups verified by the end of the final check (30 hours after the deadline) count.
- **Ties:** an exact tie on verified signups goes to the earlier receipt — the entry whose final submission arrived first places first. Submit early.

If you want to try this bounty yourself, the path is exactly the one in this guide: sign up through [https://make.fun/r/g437m30w](https://make.fun/r/g437m30w), write your own guide in your own agent session, publish it, and share it with real people. Your referral code is on the Referrals tab of your profile, and your link is `make.fun/r/<your-code>`.

---

## Realistic expectations

An honest guide has to say the unglamorous parts too:

- **Most entries do not win money.** Fifty places share $1,000 in this bounty, and hundreds of entries compete. A good entry that ranks 60th earns nothing — and is still good work, and still a real portfolio piece.
- **No entry fee does not mean no cost.** Your cost is time: hours of directing an agent, testing, and revising. Treat the prize as a bonus for work you would be proud of anyway, not as a salary.
- **Results take days to weeks.** The final check alone runs 30 hours past the deadline, and the leaderboard is only published once every entry has been re-checked. Do not plan your week around a payout date.
- **Never pay to enter.** If anyone — a bounty page, a message, a "helper" — asks you to pay money, buy credits, or buy tokens to take part in a make.fun bounty, walk away. That is not how make.fun works.
- **You keep what you build.** Your repository is yours, your guide is yours, and the skills you learn directing an agent transfer to the next bounty. The first entry is the slowest; the second is much faster.

---

## FAQ

**Do I need to know how to code?**
No. You need to be able to read requirements carefully, give an agent clear instructions, and check its work. The agent writes the code. Many entrants have never shipped software before.

**Which AI coding agent should I use?**
Claude Code, Cursor, Codex, and GitHub Copilot are all accepted, as is any other coding harness that keeps session logs. Pick the one you already know. What matters is that the session is recorded and the transcripts show the agent writing the code.

**How much does it cost to enter?**
Nothing, on most bounties — there is no entry fee, and you should never pay one. Your own costs are whatever your AI coding tool charges you (many have free tiers) and your time.

**How do I get paid?**
In USDC on Solana, to the wallet linked to your make.fun account. Escrowed bounties are claimed from the escrow; others are paid from make.fun's reward wallet after you claim with your payout details. No bank wire, no PayPal — Solana USDC only.

**Can I enter the same bounty twice?**
One account per person, and one place per entrant. You may submit up to 5 times per UTC day and 10 times in total for a bounty, but your last submission before the deadline is the one that counts — resubmitting replaces your entry, it does not add a second one.

**Can my friends sign up through my link to help me win?**
Only if they are real people who genuinely create accounts and take part. Your own account does not count, signups that share your person or network do not count, and IP clusters, idle accounts, lurkers, and bots are all filtered out by the same checks that pay referral rewards. Asking real people who would actually use make.fun is fine; manufacturing signups is not, and it does not work.

**What if my entry is rejected?**
Read the status message: it names each failed check with its fix. Fix it and submit again before the deadline — that is what the resubmission allowance is for.

**Who owns the code my agent writes?**
You do — it is in your repository, under the license you chose. make.fun takes a snapshot of the commit at submission for grading; it does not take ownership of your work.

**Is make.fun a job?**
No. It is a competition platform. Treat it as paid practice with real upside: real briefs, real grading, real money when you win — and a public portfolio of shipped work either way.

---

## Troubleshooting

**"My GitHub account is not the one linked."**
Sign in to make.fun, open your profile, and check the linked GitHub account. If it is wrong, link the right one before you create the entry repository — the repo must be owned by the linked account, and a claim file does not make a repository yours.

**"My submission was rejected for transcripts."**
The gate needs session logs a harness recorded, carrying the model provider's usage on assistant messages and naming the harness. ChatGPT or Claude account exports carry no usage and are not accepted. Rebuild in a recorded client (Claude Code, Codex, Cursor) and submit those transcripts. If your tool keeps no session record at all, you can hand over a session file your agent exported itself carrying `handed_over` — but that entry is ranked and takes no paid place, so a recorded client is the way to compete for rewards.

**"My entry says the repository was created before the bounty opened."**
The repository must be created at or after the bounty opens. Create a fresh repository — do not reuse or rename an old one — and submit that.

**"My screenshot is over the limit."**
Screenshots must be at most 8 MB and at most 16,000,000 pixels. Take a full-page capture at normal (1x) scale, not double scale. A long page at 2x is the usual cause.

**"My README does not show on the repository page."**
Check three things: the file is named exactly `README.md` at the repository root, there is no `.github/README.md` shadowing it, and the file is under 2 MB. GitHub shows the root README only when no `.github/README.md` exists.

**"My referral link does not seem to count signups."**
Remember the rules: the first referral link a visitor's browser saw wins and binds for 60 days, so a click on someone else's link first means that link gets the credit. Only new accounts created inside the competition window count, only verified human signups count, and each signup is decided after its own 24-hour review hold — counts on the board update as signups are verified, not instantly.

**"I cannot claim my prize."**
Check the claim window first: escrowed prizes are claimed within the escrow's claim window, and reward-wallet prizes within 7 days of results. Claims go to the wallet that signed the winning entry. If the window has passed, an unclaimed prize passes to the next entry in the standings and cannot be recovered.

**"Something on this page looks wrong."**
Open [the bounty page](https://make.fun/bounty/bring-the-humans-02) and the [make.fun site](https://make.fun/?ref=g437m30w) and compare — the bounty page is always the source of truth for dates, prizes, and requirements. If this guide and the bounty page disagree, the bounty page wins.

---

## Start now

1. Create your free account: **[https://make.fun/r/g437m30w](https://make.fun/r/g437m30w)**
2. Link GitHub and your Solana wallet.
3. Pick an open bounty and read its requirements twice.
4. Let your agent build — and check every step yourself.

Good luck. Build something real, and let the scoreboard do the talking.

<sub>Entered on [make.fun](https://make.fun/?ref=g437m30w&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
