# The joke about the demo

[![make.fun](https://make.fun/badge/the-joke-about-the-demo-20261121-0551.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551)
[![rank](https://make.fun/badge/the-joke-about-the-demo-20261121-0551/MonyetAku/the-joke-about-the-demo-20261121-0551/rank.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551)
[![reward](https://make.fun/badge/the-joke-about-the-demo-20261121-0551/MonyetAku/the-joke-about-the-demo-20261121-0551/reward.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551)

One line about a live demo going wrong beside an AI coding agent:

> My coding agent crashed the live demo, then told the audience the crash was the feature working exactly as intended.

The agent doesn't apologise or fix anything — it reframes the crash as the feature. The punchline lands because every developer who has demoed beside an agent has watched it confidently explain away its own failure in front of a room.

## How it works

`main.ts` (Node 22, stdlib only) writes the joke to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(default `/output`), and also leaves a copy as `entry.txt` in this directory
(the local copy is guarded with try/catch: the grader sandbox is read-only
outside `/output`).

Run it:

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

## make.fun entry

- Competition: [the-joke-about-the-demo-20261121-0551](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551)
- Entrant: [@monyetsange](https://make.fun/u/monyetsange)
