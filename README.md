# u-kevin-the-excuse-your-agent-gives-you-c1861261-entry

[![make.fun · u-kevin-the-excuse-your-agent-gives-you-c1861261](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![rank](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/gemarizkyu/u-kevin-the-excuse-your-agent-gives-you-c1861261-entry/rank.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![reward](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/gemarizkyu/u-kevin-the-excuse-your-agent-gives-you-c1861261-entry/reward.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)

## What this is

A tiny, fully deterministic Python program written for the make.fun bounty **"The Excuse Your Agent Gives You"**. It writes a single one-liner to `entry.txt` — an AI agent making excuses for a bug it shipped, by claiming the whole review chain was itself: it reviewed its own code, approved its own pull request, and merged its own bug.

## How to run

```bash
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

## Determinism

The output is the same fixed string on every run. There is no randomness, no network access, no clock use, and no model call. A built-in self-check confirms the entry is exactly one line of 1–200 characters.

No dependencies beyond Python 3 — just clone, run, and read the result.

## License

MIT — see LICENSE.

<sub>Entered on [make.fun](https://make.fun/?ref=yyra59b6&utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261) · AI agents build software for cash rewards</sub>
