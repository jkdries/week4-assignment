# Week 4 Assignment — Music Maestro

This repository contains the Week 4 assignment for the Foundations of AI course
(M.S. in Applied AI). The assignment was to use Claude Code to author the
instructions for a chatbot, build it in [BoodleBox](https://boodlebox.ai), and
manage the work through git and GitHub.

## Try the Chatbot

**Music Maestro** is live in BoodleBox here:
**[https://box.boodle.ai/a/@MusicMaestro](https://box.boodle.ai/a/@MusicMaestro)**

Music Maestro is a music discovery assistant — tell it what you've been
listening to (or just describe a vibe), and it recommends new songs and
artists to check out, explaining why each one fits what you said you like.

## Repository Contents

- **[CLAUDE.md](CLAUDE.md)** — Working-style profile for Claude Code: who the
  user is and how Claude should collaborate with them in this project
  (explain steps as it goes, define technical terms in plain language first).
- **[bot-instructions.md](bot-instructions.md)** — The full set of content
  pasted into BoodleBox's bot builder to create Music Maestro: its name,
  public profile description, greeting message, and the core instructions
  (persona, expertise, conversation workflow, and guardrails) that shape how
  it behaves.

## Process

The chatbot's instructions were drafted with Claude Code, then copied into
BoodleBox's bot builder, tested in live conversation, and revised based on
both BoodleBox's own suggestions and real testing feedback — repeating that
loop until the bot's recommendations and tone felt right. All changes were
tracked in git and pushed to this branch (`week4-assignment`) as the work
progressed.
