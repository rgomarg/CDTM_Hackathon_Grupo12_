<p align="center">
  <img src="assets/banner.png" alt="First to know, first to tell. Sherpas challenge at CDTM Valencia Hacks 2026, Saturday 21 November, The Terminal Hub, Valencia" width="100%">
</p>

# First to know, first to tell

**Sherpas challenge at CDTM Valencia Hacks 2026. Saturday 21 November 2026, The Terminal Hub, Valencia**

---

# What Team 12 built: Briefing Inbox

**The problems we chose:** communications at scale, with profiling and an
event tracker behind it. An advisor looks after ~150 families; when a
rule changes, every family should hear it first from their advisor, in
their own numbers — and the advisor should approve 30 personal messages
in minutes, not a morning.

**What we built:** a two-sided working prototype.

- **Client side:** Samantha gets a clear email from her advisor with her
  own numbers. One tap opens her report: **what happened, how it
  affects her, and what her options are**. She picks an option with one
  tap and her advisor sees it. Every past update stays in her timeline.
- **Advisor side:** Alex sees every family and the next clear step. He
  finds Samantha in one search; the update is already drafted from her
  plan data and fully editable. He previews exactly what she will see,
  then approves in one click.
- **The principle — graduated autonomy:** financial advice never sends
  itself; the advisor always approves. Light-touch messages (birthdays,
  reminders, check-ins) do send automatically, and everything is logged
  and auditable in the send history.

The worked example is the real 2027 Social Security wage-base change
($184,500 → $192,300) mapped onto Samantha Lewis's actual plan numbers:
about $484 more in 2027, nothing to fix.

## Live demos (open in any browser, no login)

- **Client view:** https://files.instinct.com/eouh3w0hnz2l-demo-sherpas-vista-cliente
- **Advisor view:** https://files.instinct.com/whbgqjufpheo-demo-sherpas-vista-asesor

## Demo videos

- **demo-narrado-pau.mp4** (1:08) — full walkthrough with voiceover.
- **demo-cliente-18s.mp4** (0:18) — quick client loop.
- **demo-asesor-rapido.mp4** (0:26) — quick advisor loop.

## How to run it

The prototypes in `demo/` are self-contained single-file HTML apps:
open them in a browser, no build step, no backend, no keys. Edits are
session-only.

## What is simulated

Everything on screen: the 150 families in the advisor queue (to show
scale), the drafts, the automatic messages, and the email preview. All
figures come from the supplied synthetic cases, mainly Samantha Lewis,
plus the 2027 wage-base value from the legal dataset. No real messages
are sent and no real people are used.

**Team 12:** Pau Romeu · Raquel · Pelin · Julia · Nico Roig

---

[CDTM Valencia Hacks](https://vlc.hacks.cdtm.com/) is a one-day hackathon by CDTM Valencia (UPV and Universitat de València) with cases from several companies. Sherpas is one of the main sponsors; this page is everything you need for the Sherpas case.

## Join the Discord first

<a href="https://discord.gg/mCHYWRhFw"><img src="assets/discord-qr.png" alt="QR code: join the Discord" width="160" align="right"></a>

**[CDTM VLC Hacks x Sherpas Wealth on Discord](https://discord.gg/mCHYWRhFw)** is where the day happens. Scan the code or click the link:

- **Announcements and rules**: accept the rules in #welcome to see the rest
- **Your team's private channels**: in #welcome press **Join my team** and type the email you registered with for CDTM Valencia Hacks. You go straight into your team's private text and voice channels, which only your team, the mentors and the organisers can see
- **Questions**: the #help forum, or `/mentor` in your team channel to call the Sherpas mentor
- **Your idea** with `/idea` (type `/help` for all commands). The official hand-in is on Polievalúa, see [Your day](#your-day-and-what-you-hand-in)

Every team member should join before the kick-off on Saturday.

## Start here

1. Read this page: the challenge, the families, the data and the hand-in are all here.
2. Click **Use this template &gt; Create a new repository** (top right on GitHub). One person per team does this, under their own account, and chooses **Public** so the mentors and the jury can open it. Everyone in the team needs a free GitHub account.
3. Open one family's plan from [the cases table](#the-cases) and read the same family's `persona.md`.
4. Connect to the case data ([Connect to the cases](#connect-to-the-cases)) or read the files in [`cases/`](cases/) and [`legal/`](legal/).

Any language, framework or device. Keep a README that says what you built, how to run it, what it uses and which parts are simulated.

## Who we are

Sherpas Wealth is an AI platform for financial advisors in the United States ([sherpaswealth.com](https://sherpaswealth.com)). Advisors are our customers; families are their clients. For every family, an advisor does three jobs:

| | Job | Today |
|---|---|---|
| 1 | **Collect the data**: who the family is, what they earn, own and owe, and what they want | Solved by Sherpas |
| 2 | **Build the plan** | Solved by Sherpas: a narrated plan with an overview, advice area by area, a living map of their finances year by year, and concrete strategies |
| 3 | **Keep the family close**: after the plan, the relationship goes on for years | **This is your challenge** |

## The challenge: nurturing at scale

**A financial advisor looks after around 150 families. Each one wants to feel like the only one.**

The plan is not a once-a-year relationship. Between meetings, laws change, markets move, careers and families change, and every family wants to know that their advisor is on it: that if something matters to them, they will hear it first, from their advisor, in their own terms. And that if they hear nothing, it is because nothing needs doing.

Sherpas already collects the data and builds the plan. Your challenge is the day-to-day relationship after it: **how do you make every family feel looked after, personally and ahead of time, when one advisor has 150 of them?**

### The problems

What happens in the family's head:

1. **They hear it from the news first.** A tax rule changes: *"What does this mean for us? Do we have to change anything? Our advisor hasn't said a word. Do I have to ask?"* Every time they have to ask, they trust their advisor a little less.
2. **Markets fall and they panic alone.** Nvidia falls 30% in two weeks, or the market drops 20%: *"Is the bubble bursting? Do we sell? Can we still buy the beach house? Should we buy now?"* What they need first is someone telling them this is normal and the plan was built for it, then what it means for them.
3. **They feel like a number.** *"Our advisor has clients with two or three million. We have $150,000, but it is our $150,000."* Silence reads as "nobody is watching".
4. **Their life moves and nobody connects it to the plan.** A promotion (and the risk of spending all of the raise), layoffs at their company, a child turning 11 with seven years to college, a child about to lose the family's health cover at 26, a house they are thinking about.
5. **Generic content.** The same newsletter for every family: it explains what an annuity is to someone who already holds one, and skips the topics they actually care about.
6. **Big decisions take more than one message.** A Roth conversion: first they need to understand what it is, then why it suits them, then accept it, then feel ready to act. People need to hear about something four or five times before it feels familiar.

What happens on the advisor's side:

7. **Nobody can watch everything for everyone.** Regulation, markets, each family's employer, their LinkedIn, the dates already in their plan, for 150 families, every week.
8. **Knowing each person takes time.** What they care about, what they already know, how they react to risk: in a couple, one may shrug at a market drop while the other panics.
9. **Every message needs the advisor's approval.** AI should not write to a client on its own yet: the advisor approves first. With 30 personal drafts a day, approving them one by one is the whole morning.

### Where you could start

Pick the problems you believe in. Four parts of an answer, as examples; build one, several, or something else:

| Part | The question it answers |
|---|---|
| **Profiling** | Who is this person? Which topics matter to them, what do they already know, how do they decide and react to risk? |
| **Tracker** | What just happened to this family, their employer, the market or the law, and does it touch their plan? |
| **Content library** | What do we already have to say about this: to reassure, to explain, to check in, to celebrate? |
| **Communications** | Who hears what, when, and how does the advisor approve 30 personal messages in minutes: an inbox, a conversation ("seven messages today, this one because..."), or something new? |

**The core is communication that feels personal, approved by the advisor at scale, built on profiling and an event tracker.** Profiling tells you what each person cares about and already knows; the tracker connects events to their plan. A content library is an optional plus and counts least. Format, channel and stack are yours. You will not build everything in one day, and you do not need to.

Four families are supplied. You can simulate more to demonstrate scale; label them in your README.

### What already exists (do not rebuild it)

- **The plan:** for every family, Sherpas collects the data and builds a narrated plan (overview, advice by area, a living map year by year).
- **Tax and legal values:** every value behind a plan carries its official source; when a rule changes, Sherpas publishes the new value and new plans recalculate with it. Knowing that a number changed is solved; what it means for each family, and telling them, is not.
- **Emails around the plan:** the questionnaire invitation and reminders, an invitation to book a meeting, access to the plan. Once the plan is delivered, nothing more goes out.

## The cases

Four synthetic households, true to life, built for this event. Every team gets all four. Each has a complete Sherpas plan and a client profile: how each person takes risk and decides, what drives and worries them, and the dates already in their plan.

| Family | Who they are | Their story | Plan in the app | Files |
|---|---|---|---|---|
| Timothy & Melanie Weah | 40 and 38, Liam (6) and Josh (3). $150,000 in cash, an $18,000 card at 18%, a $350,000 home. San Francisco, CA | Plenty of cash and an expensive card. Where should each dollar go? | [Open the plan](https://app.sherpaswealth.com/plan/shared/RcCtgoNkGmD6dvGtYVKWLGefdCTFdc4JP_jH9Jbz2jo) | [`cases/timothy-melanie-weah/`](cases/timothy-melanie-weah/) |
| Michael Carter | 37, $180,000 salary, renting. Austin, TX | A $550,000 home in 2027 and retiring at 58. Can he do both? | [Open the plan](https://app.sherpaswealth.com/plan/shared/ZshH0AUJjZnvwKIYtP5wYKyvI6Nc1nsGwQlDncXLfek) | [`cases/michael-carter/`](cases/michael-carter/) |
| Daniel & Emily Johnson | 44 and 42, two children, a $560,000 mortgage, an $18,000 card at 24.9%. Denver, CO | College for Oliver and Sophia and retiring at 62. What comes first? | [Open the plan](https://app.sherpaswealth.com/plan/shared/FjVPq_UEwSMxaye8aOWj3osJWWSE3cDnYWcxm1X7I78) | [`cases/daniel-emily-johnson/`](cases/daniel-emily-johnson/) |
| Samantha Lewis | 47, two teenagers, $250,000 salary, debt-free and well insured. Miami, FL | College bills now and a second home in 2030. What next? | [Open the plan](https://app.sherpaswealth.com/plan/shared/vyV2h64-qSet-sJuwkAHxw-iUaYV88Lkwsg29L2Y5y8) | [`cases/samantha-lewis/`](cases/samantha-lewis/) |

**Plan in the app** opens the family's plan exactly as the client sees it: the advice, the living map and the investment analysis. No login needed, read only.

Each family folder contains:

| File | What it contains |
|---|---|
| `financial-health.json` | Who the family is (ages, state, tax filing status), their score and why, incomes, accounts, debts, insurance, goals, key metrics, written analysis and yearly projection |
| `investment-analysis.json` | Accounts and holdings, key metrics and the written investment analysis |
| `persona.md` | The client profile: wealth, life stage, risk per person (stated, revealed and inferred), how they decide, what drives them, upcoming transitions, concerns **O1, O2...** and tensions **T1, T2...** (sections **D0 to D6**). Its figures match the plan. A starting point for profiling |
| `signals.json` | Real examples of one possible structure for a tracker: a past market shock, the 2027 tax changes and a dated moment from the plan, each with what it touches in this family's plan and where to look. Not a list of what to build |
| `legal-values.json` | The same tax and legal values as [`legal/legal-dataset-sample.json`](legal/legal-dataset-sample.json), so you can read them through the MCP |
| `report.pdf` | The client report, for Timothy and Melanie, Michael, and Daniel and Emily. Samantha's is not included |

All amounts are US dollars.

## Your day, and what you hand in

| When | What |
|---|---|
| 08:30 | **Registration and welcome** at The Terminal Hub: bring your ID |
| 09:00 | **Kick-off and case briefing**: Sherpas, the families and the challenge |
| 10:00 | **Hacking time**, with mentor rounds |
| 13:30 | **Lunch** (30 minutes) |
| 14:00 | **Working time**: final push on the prototype and the pitch |
| 16:45 | **Hand-in deadline**, one per team, on **Polievalúa**: pitch deck, GitHub repo link and demo video. Hard cut-off |
| 17:00 to 18:15 | **Pitches**: 3 minutes per team plus 2 minutes of questions |
| 18:15 to 19:00 | **Jury deliberation, awards** and the group photo |

Teams of five; CDTM matches you with your team. Everything happens in English: code, README and pitch. Agenda from CDTM's participant guidebook on [vlc.hacks.cdtm.com](https://vlc.hacks.cdtm.com/); if CDTM changes a time on the day, theirs wins.

What you hand in:

1. **Pitch deck** for your 3-minute pitch: the problem you chose, what you built, and why it matters to the family and the advisor.
2. **GitHub repo** with your working MVP and a README: the problems you chose, what you built, how to run it, what it uses, and which parts are simulated. It runs on the supplied families and can cover one part (profiling, tracker, content library, communications) or several; you do not need to build the whole chain.
3. **Demo video** showing what the family and the advisor experience with your MVP.

## Prize

<p align="center">
  <img src="assets/join.png" alt="Sherpas wants you. Internship opportunities" width="100%">
</p>

**500 € in Amazon vouchers for the winning team: a 100 € Amazon gift card for each of its five members.** Sherpas is looking for talent: the best prize is building real things with us.

## A few terms

- **Social Security wage base:** the most salary per person that Social Security tax applies to in a year.
- **Standard deduction:** the part of income not taxed, by filing status.
- **Filing status:** how a household files its US tax return, for example single or married filing jointly.
- **RMD:** required minimum distribution, the yearly withdrawal the law requires from retirement accounts from a set age.
- **IRMAA:** a Medicare surcharge for people with higher income.
- **QCD:** qualified charitable distribution, a gift to charity straight from an IRA.
- **401(k), IRA, HSA, 529:** US retirement, health and education savings accounts with tax advantages.
- **Living map:** a year-by-year view of the family's projected financial life.
- **MCP:** Model Context Protocol, a standard way for AI assistants and code to read data from a server.
- **Backend:** the part of your app that runs on a computer or server, where keys stay private.
