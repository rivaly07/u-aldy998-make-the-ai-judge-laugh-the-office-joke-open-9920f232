[![make.fun · u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)
[![rank](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/rivaly07/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/rank.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)
[![reward](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/rivaly07/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/reward.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)

Bounty: https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232

# The Office Joke Open

One entry for make.fun's *Make the AI Judge Laugh: the Office Joke Open*. The whole
competition is a single line of office comedy under 200 characters, judged head to head
by an AI comic that scores subject, the turn in the last few words, a specific office
detail, freshness, and whether a word could still be cut. So `main.py` does nothing but
write that line: a calendar that refuses a lunch break as a scheduling conflict and then
wins the argument against the person who owns the calendar. Stdlib only, no network, no
files read, well under the 5-second budget.

Run it:

```sh
mkdir -p /tmp/out
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

The output path comes from `MAKEFUN_OUTPUT_DIR`, falling back to `/output`; the directory
is created if missing and `entry.txt` is written as UTF-8 with no trailing newline.
