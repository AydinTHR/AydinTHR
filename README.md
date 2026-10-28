# Aydin Tehrani

Full-stack & AI developer, Seneca Polytechnic '26, Greater Toronto Area.
I build AI agents that stay reliable: the model writes the words, and tested code owns every number, time and decision.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aydin-tehrani-4466222ab/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:aidinthr82@gmail.com)
[![Website](https://img.shields.io/badge/aydintehrani.com-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://aydintehrani.com)

Open to junior full-stack / AI roles, available now.
I keep the decisions in ADRs, the tests in CI, and the numbers in code rather than in the model.

## Projects

### Aimentum
Personal AI accountability agent that messages me first: a morning plan, a nudge if no plan arrives, an evening check-in with real pace numbers, and a weekly retro.
Private repo for now, happy to walk through it · solo build

**Highlights:** a greedy week scheduler whose every plan is re-checked by an independent validator before it is published, scheduled jobs that run exactly once and recover from missed ticks and crashes, and commitments confirmed by a tap or a deterministic evidence check, never by asking the model. 607 backend tests against PostgreSQL in CI and 7 ADRs.

`Python` `FastAPI` `PostgreSQL` `React` `TypeScript` `Claude API`

### PaperPilot
Autonomous paper-trading agent with hard risk limits, running an LLM strategy side by side with classical ones.
[Repo](https://github.com/AydinTHR/paperpilot) · solo build

**Highlights:** one pure risk engine shared by backtests and the live loop (position cap, daily-loss kill switch, a drawdown halt that survives restarts, broker-held stop-losses), two separate flags required before any real-money order, and walk-forward validation that flagged an optimized strategy as overfit (WFE -0.72). 262 tests, CI on Python 3.11 to 3.13, and 9 ADRs, including fixes from running it live.

`Python` `Alpaca API` `pandas` `backtesting.py` `SQLAlchemy` `Docker`

### MoneyMind
AI personal-finance copilot that remembers who you are with money.
[Live demo](https://money-mind-seven.vercel.app) · [Repo](https://github.com/mahyar-jbr/moneymind) · Google Cloud Rapid Agent Hackathon, team of 3

**My role:** frontend lead. I built most of the Next.js frontend: the dashboard with its spend chart and category breakdown, the streaming chat shell, the animated intervention-approval cards, and the demo video. My teammates built the agent, its memory, and the data pipeline.

`Next.js` `React 19` `TypeScript` `Tailwind` `Clerk` `Framer Motion`

### Portfolio
My personal site, live at [aydintehrani.com](https://aydintehrani.com).
[Repo](https://github.com/AydinTHR/portfolio) · solo build

**Highlights:** a React 19 frontend on Vercel and a FastAPI + MongoDB API on Render. An in-browser admin CMS with autosaved drafts and version history, a spam-protected contact form with an admin inbox, first-party analytics with no third-party trackers, and a simplex-noise contour background rendered in a Web Worker.

`React 19` `Vite` `Framer Motion` `FastAPI` `MongoDB` `Playwright`

### Brinkpot
Play-money jackpot game where every round can be verified with a commit-reveal scheme.
[Play it](https://aydinthr.github.io/brinkpot/) · [Repo](https://github.com/AydinTHR/brinkpot) · solo build

**Highlights:** a pure, deterministic engine (integer cents and milliseconds, seeded random numbers, no wall clock), and a verifier that replays your moves through the same simulation code to reproduce the result. 39 unit tests at 98% coverage on the game logic, plus an end-to-end round in CI.

`TypeScript` `React` `Zustand` `Web Crypto` `Vitest` `Playwright`

## Other projects

- **[AI Job Search Assistant](https://github.com/AydinTHR/job-search-assistant)**, a Seneca course project: a three-phase CLI that analyzes job postings, finds resume gaps, and drafts an application package. Pydantic-validated LLM outputs, retries with backoff, Tavily web research, and an evaluation harness. `Python` `OpenRouter` `Gemini 2.5 Flash`
- **[Dog Wash Booking](https://github.com/mahyar-jbr/dog-wash-booking)**, team of 3: I built the customer booking frontend. `React` `Vite` `Material UI`

## Stack

<table>
  <tr>
    <td align="center"><strong>Languages</strong></td>
    <td align="center"><strong>Backend</strong></td>
    <td align="center"><strong>Frontend</strong></td>
    <td align="center"><strong>Tools</strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=python,ts,js,cpp,c" height="28" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=fastapi,postgres,mongodb,mysql" height="28" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,materialui" height="28" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=docker,githubactions,git,linux" height="28" />
    </td>
  </tr>
</table>

<sub>AI / LLM: Anthropic, OpenAI, and Gemini APIs (structured outputs, tool calling, multi-agent), built with Claude Code</sub>
