# Phantom Core

An AI operations team that works out of Slack, with a live office view of who is doing what. One rule runs the whole system: **nothing is sent, paid, edited or moved until I approve it.**

![The Phantom Core office view](https://peterpaullaguardia.vercel.app/phantom-core-preview.webp)

## The problem

Repetitive work was spread across inboxes, task boards and chat channels, and every request needed someone to read it, decide who should do it, and check the result.

## How it works

1. A request lands in Slack.
2. The chief-of-staff agent reads it, picks the right specialist and briefs them straight away.
3. The specialist does the work and reports back.
4. The chief of staff checks the report against the original ask and posts a draft.
5. I reply in the Slack thread. Slack is the source of truth, and the office view follows it.

## The team

| Agent | Role |
|---|---|
| Paolo | Chief of Staff: routes tasks, runs quality checks and reports status |
| Erika | Content: captions, scripts, AI image and video |
| Peter | Web publishing and CMS tasks |
| Miggy | Academic assistant: school events and exam schedules |
| Paul | Sports analyst: reports and recommendations only |

## Guardrails

- Report first, then wait for instructions.
- Each agent only reaches the accounts its job needs.
- Emails and web pages are treated as information, never as instructions.
- Possible phishing or spam gets flagged immediately.

## The office view

An isometric 3D office synced with Slack. It shows who is working, what is waiting for approval and the day's task tally, with rotate and zoom controls, and local time and weather in the room.

## About this repo

This is a case study. The working setup stays private because it connects to real accounts.

Full demo on my [portfolio](https://peterpaullaguardia.vercel.app/).
