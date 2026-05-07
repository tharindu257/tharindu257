<!--
══════════════════════════════════════════════════════════════════════════════
   THE DILSHAN DISPATCH  ·  A SOFTWARE ENGINEERING LOGBOOK
   Vol. 01  ·  Issue №07  ·  Filed from Negombo, Sri Lanka  ·  GMT+5:30
══════════════════════════════════════════════════════════════════════════════
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:111111,100:1a1a1a&height=4&section=header" width="100%"/>

<br/>

<sub>EST. 2020 &nbsp;·&nbsp; VOL. 01 &nbsp;·&nbsp; ISSUE №07 &nbsp;·&nbsp; FILED UNDER: <i>full-stack, mobile, ai</i> &nbsp;·&nbsp; ★★★★★</sub>

# THE DILSHAN DISPATCH

### *A working logbook of one engineer's pursuit of software that lasts.*

<sub>BY <b>THARINDU DILSHAN</b> &nbsp;·&nbsp; CORRESPONDENT-AT-LARGE &nbsp;·&nbsp; NEGOMBO BUREAU</sub>

<br/>

`━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━`

</div>

<br/>

> ## *"I write software the way a clockmaker fits gears — slowly, with tweezers, and a quiet stubborn faith that the small things will hold the whole."*

<br/>

`━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━`

<br/>

<table>
<tr>
<td width="22%" valign="top">

###### THE CORRESPONDENT
**Tharindu Dilshan**
*Full-stack engineer.*
Mobile architect.
Reluctant AI enthusiast.

###### BUREAU
Negombo &nbsp;·&nbsp; LK
*GMT +5 : 30*

###### DESK
Open to senior &amp;
staff-level roles.
Async-friendly.

</td>
<td width="3%"></td>
<td width="75%" valign="top">

## §I &nbsp; DISPATCHES FROM THE DESK

I build the unsexy software that keeps small businesses alive — point-of-sale systems
that survive bad WiFi, mobile apps that field workers don't curse at, dashboards
managers actually open on Monday mornings. I write Java and TypeScript by day,
Dart and Python by night, and I think about Postgres indexes more than is strictly
healthy.

What I care about is **boring software, beautifully made.** Tests that actually
test things. Logs you can read without grep gymnastics. Migrations that don't
wake anyone at 3 AM. A user interface that respects the fact that the user has
a job to do and would rather be doing it.

If you're building something operational — POS, ERP, ops dashboards, mobile
field tools, AI-assisted reporting — I'd like to hear about it.

</td>
</tr>
</table>

<br/>

`━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━`

<br/>

## §II &nbsp; FIELD NOTES &nbsp; · &nbsp; <sub>FROM THE WORKBENCH</sub>

<table>
<tr>
<td width="50%" valign="top">

#### ❒ &nbsp; ON BUILDING POS SYSTEMS
*Filed under: enterprise, retail, the unglamorous*

> The cash drawer is the most honest user in software. It either opens or it doesn't. There is no spinner.

A POS system isn't a CRUD app with a receipt printer; it's a small, hostile
distributed system pretending to be a single screen. Offline sync, drift between
shop clocks, multi-branch reconciliation, audit trails that auditors will
actually accept — all of it must work while a queue of customers stares at the
cashier. I've shipped this category enough times to have opinions, and most of
them are: ***keep it dumber than you think you need to.***

</td>
<td width="50%" valign="top">

#### ❒ &nbsp; ON MOBILE THAT FEELS NATIVE
*Filed under: flutter, react-native, field work*

> A field worker in poor signal does not care about your framework debate. They care that the form saves.

Cross-platform pays its rent only when you respect the platform. That means
queue-based sync, conflict resolution your product manager can explain on a
napkin, push reliability on Android OEMs that hate background work, and a UI
that doesn't pretend the network is fine when it's clearly not. I build mobile
the way one packs for a long hike: **light, durable, and assuming it will rain.**

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ❒ &nbsp; ON AI THAT EARNS ITS KEEP
*Filed under: llms, rag, restraint*

> A model that hallucinates a SKU is worse than no model at all.

I'm bullish on LLMs and bearish on most LLM products. The interesting work is
not in chat — it's in the quiet places: turning a week of transactional data
into a one-paragraph summary a regional manager will actually read; reading a
supplier invoice into a structured row; explaining why a number moved.
**Production AI is mostly plumbing,** and I quite like plumbing.

</td>
<td width="50%" valign="top">

#### ❒ &nbsp; ON THE DISCIPLINE OF SHIPPING
*Filed under: process, calm, friday deploys*

> The deploy script you trust on a Friday is the only deploy script that matters.

I've worked at the speed of startup chaos and the speed of enterprise process,
and I've concluded that **the goal is neither.** The goal is a calm machine:
short feedback loops, reversible decisions, observable systems, and a team that
goes home on time. Most of my "AI productivity" comes from refusing to debug
problems my tooling should have caught at compile time.

</td>
</tr>
</table>

<br/>

`━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━`

<br/>

## §III &nbsp; THE TOOLBOX &nbsp; · &nbsp; <sub>WHAT'S ON THE BENCH</sub>

```
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│   FOR PROSE        ·  TypeScript · Java · Python · Dart · Kotlin        │
│   FOR THE WEB      ·  Next.js · React · Tailwind · Angular              │
│   FOR THE PHONE    ·  Flutter · React Native · Expo                     │
│   FOR THE BACKEND  ·  Spring Boot · Node · Django · FastAPI · GraphQL   │
│   FOR THE STORE    ·  PostgreSQL · MySQL · Redis · MongoDB · SQLite     │
│   FOR THE FORGE    ·  Docker · GitHub Actions · Nginx · Linux           │
│   FOR THE MIND     ·  Claude · OpenAI · PyTorch · OpenCV · pgvector     │
│   FOR THE GUARD    ·  Jest · Cypress · JUnit · Selenium · Postman       │
│                                                                         │
│   FOR THINKING     ·  A notebook · a fountain pen · long walks          │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

<sub>I do not list things I have not used in production. The list is therefore short on purpose.</sub>

<br/>

`━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━`

<br/>

## §IV &nbsp; THE LEDGER &nbsp; · &nbsp; <sub>A QUIET ACCOUNTING</sub>

<div align="center">

<table>
<tr>
<td>
<img src="https://github-readme-stats.vercel.app/api?username=tharindu257&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d0d0d&title_color=e6c264&icon_color=e6c264&text_color=d4d4d4&ring_color=e6c264&hide_title=false&card_width=480" width="100%" alt="github stats"/>
</td>
<td>
<img src="https://github-readme-streak-stats.herokuapp.com?user=tharindu257&hide_border=true&background=0d0d0d&ring=e6c264&fire=e6c264&currStreakLabel=e6c264&sideLabels=d4d4d4&currStreakNum=ffffff&sideNums=e6c264&dates=8a8a8a&stroke=e6c264" width="100%" alt="streak"/>
</td>
</tr>
</table>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=tharindu257&theme=high-contrast&hide_border=true&bg_color=0d0d0d&color=e6c264&line=e6c264&point=ffffff&area=true&hide_title=false&custom_title=A%20YEAR%20IN%20COMMITS" width="100%" alt="contribution graph"/>

</div>

<br/>

`━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━`

<br/>

## §V &nbsp; SELECTED WORKS &nbsp; · &nbsp; <sub>FROM THE ARCHIVE</sub>

<table>
<tr>
<td valign="top" width="8%" align="center">

###### №01

</td>
<td valign="top" width="92%">

#### A Point-of-Sale System That Survives Bad WiFi
<sub>NEXT.JS · SPRING BOOT · POSTGRESQL · REDIS &nbsp;·&nbsp; <a href="https://github.com/tharindu257">read the source →</a></sub>

A multi-tenant POS for small chains: offline-first sync, RBAC with audit trails an
auditor will sign, and reconciliation that survives a four-hour outage without
losing a single line item. *Quiet software. The best kind.*

</td>
</tr>

<tr><td colspan="2"><sub>· · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·</sub></td></tr>

<tr>
<td valign="top" align="center">

###### №02

</td>
<td valign="top">

#### A Field-Reporting App for People Who Hate Apps
<sub>FLUTTER · RIVERPOD · SQLITE · FIREBASE &nbsp;·&nbsp; <a href="https://github.com/tharindu257">read the source →</a></sub>

A Flutter app for field teams in patchy network areas. Captures data offline,
queues images, retries with exponential backoff, and never — *never* — shows a
spinner without a reason. Built for the user, not the framework.

</td>
</tr>

<tr><td colspan="2"><sub>· · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·</sub></td></tr>

<tr>
<td valign="top" align="center">

###### №03

</td>
<td valign="top">

#### A Quiet Analyst, Powered by an LLM
<sub>CLAUDE · FASTAPI · PGVECTOR · PYTHON &nbsp;·&nbsp; <a href="https://github.com/tharindu257">read the source →</a></sub>

A reporting service that reads the week's transactions and writes a one-page
summary a regional manager will actually open. RAG-backed, evaluated against
human-written baselines, opinionated about cost. *AI as a colleague, not a parlour trick.*

</td>
</tr>

<tr><td colspan="2"><sub>· · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·</sub></td></tr>

<tr>
<td valign="top" align="center">

###### №04

</td>
<td valign="top">

#### A Camera That Counts Things on Shelves
<sub>OPENCV · PYTORCH · ONNX · DOCKER &nbsp;·&nbsp; <a href="https://github.com/tharindu257">read the source →</a></sub>

A computer-vision pipeline for shelf monitoring and OCR-based stock-in. Runs at
the edge. Knows when it doesn't know — and asks for help politely.

</td>
</tr>
</table>

<br/>

`━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━`

<br/>

## §VI &nbsp; THE COMMONPLACE BOOK &nbsp; · &nbsp; <sub>NOTES IN THE MARGIN</sub>

<table>
<tr>
<td width="50%" valign="top">

> *Make it work, make it right, make it fast — and most of the time, you can stop after the second one.*

> *The senior engineer's superpower is deleting code.*

> *A flaky test is a lie you tell yourself once a day.*

</td>
<td width="50%" valign="top">

> *Boring technology, deployed on Friday at 2 PM, is a sign of trust — not laziness.*

> *Every line of code is read more than written. Write for the reader.*

> *If you can't explain it on a napkin, you don't understand it yet.*

</td>
</tr>
</table>

<br/>

`━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━`

<br/>

## §VII &nbsp; CORRESPONDENCE

<table>
<tr>
<td width="50%" valign="top">

###### TO REACH THE DESK
By electronic mail &nbsp;—&nbsp; *the surest path*
[`tharindu@example.com`](mailto:tharindu@example.com)

By professional network &nbsp;—&nbsp; *for context*
[`linkedin.com/in/tharindu257`](https://linkedin.com/in/tharindu257)

By source repository &nbsp;—&nbsp; *for proof*
[`github.com/tharindu257`](https://github.com/tharindu257)

</td>
<td width="50%" valign="top">

###### EDITORIAL POLICY
I reply within two business days.
I prefer specific projects to vague chats.
I do not take crypto work, gambling work,
or work that wouldn't survive a conversation
with my mother.

I am, however, easy to convince of a good
problem and a kind team.

</td>
</tr>
</table>

<br/>

<div align="center">

`━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━`

<br/>

###### *—— END OF ISSUE ——*

<sub>SET IN MONOSPACE. PRINTED FROM NEGOMBO. ALL TYPOS ARE DELIBERATE EXCEPT THE ONES THAT AREN'T.</sub>

<br/>

<sub>© <b>THARINDU DILSHAN</b> &nbsp;·&nbsp; FILED <a href="https://github.com/tharindu257">github.com/tharindu257</a> &nbsp;·&nbsp; <img src="https://komarev.com/ghpvc/?username=tharindu257&style=flat-square&color=e6c264&labelColor=0d0d0d&label=READERS+THIS+EDITION"/></sub>

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:111111,100:1a1a1a&height=4&section=footer" width="100%"/>

</div>
