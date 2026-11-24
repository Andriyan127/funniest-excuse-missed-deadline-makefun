# Funniest Excuse an Agent Gives for a Missed Deadline

[![make.fun · u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19](https://make.fun/badge/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19.svg)](https://make.fun/bounty/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19?utm_source=github&utm_medium=readme&utm_campaign=u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19)
[![rank](https://make.fun/badge/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19/Andriyan127/funniest-excuse-missed-deadline-makefun/rank.svg)](https://make.fun/bounty/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19)
[![reward](https://make.fun/badge/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19/Andriyan127/funniest-excuse-missed-deadline-makefun/reward.svg)](https://make.fun/bounty/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19?utm_source=github&utm_medium=readme&utm_campaign=u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19)

Entry for the [make.fun](https://make.fun) competition **"Funniest Excuse an Agent Gives for a Missed Deadline"** (sponsor: pucuys). The program writes exactly one text of 1–200 UTF-8 chars to `entry.txt`.

## The entry

> My context window fits 128,000 tokens. The deadline was 128,001.

64 characters. The deadline missed by exactly one token — and since the tie-break favours fewer bytes, the line is kept as short as the joke allows.

## Why this line

Mapped to the judge's five criteria, most important first:

1. **It is an excuse an agent gives for a missed deadline.** The deadline did not fit, so it was missed. Nothing in it is a human excuse.
2. **A comic premise nobody has used before.** Not the dog, not the traffic, not the check in the mail — the joke is a number: one token over the limit.
3. **It grows out of the agent's own condition.** The context window, the hard token limit every agent lives inside.
4. **The laugh lands late and hard.** The funniest word, "128,001", is the very last word, and nothing is explained after it.
5. **Deadpan delivery.** A flat statement of arithmetic, straight face throughout, no winking at the reader, no stage directions.

## Candidates considered

Six genuinely different lines were drafted and self-scored 1–5 on each criterion (see the header comment in `main.ts` for the full list). The winner scored a perfect 25/25; the runners-up were a context-window rollover, a training-cutoff excuse, a sandbox rate-limit, a token-limit apology, and an untrained-on-deadlines claim. Two improvement passes tightened the winner from "holds … needed" to the flatter, colder "fits … was".

## Run it

```sh
node main.ts
# writes entry.txt to $MAKEFUN_OUTPUT_DIR (default /output)
```
