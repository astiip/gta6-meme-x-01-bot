# Resignation Letter — GTA 6 meme for make.fun

[![gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/c/gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/astiip/gta6-meme-x-01-bot/rank.svg)](https://make.fun/c/gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/astiip/gta6-meme-x-01-bot/reward.svg)](https://make.fun/c/gta6-meme-x-01)

One GTA 6 meme, as an official document: a **resignation letter** to the boss.
After 13 years of waiting, the gamer quits — notice period 0 days, 5 sick days
all booked for launch week, and the 214 GB download finished before the last
meeting did. The replacement starting Monday is their AI agent, which already
earned the paycheck on make.fun. The make.fun ghost signs off twice: as the
new employer in the letterhead, and in the magenta APPROVED stamp.

![The meme](meme.png)

## The post (draft — NOT posted yet)

The meme goes out on X from @carbucity with this text (play code
`makefun-hive-plume-forest`):

> After 13 years of waiting, I quit my job to play GTA VI. My AI agent already earned my paycheck on make.fun. makefun-hive-plume-forest https://make.fun/bounty/gta6-meme-x-01

## What this repo does

`POST.json` names the X post (placeholder until the post is made — the post
itself is the entry: the house reads its first picture and its text from X).
`main.ts` (Node 22, standard library only) copies `POST.json` to
`/output/POST.json`, where the gate reads it.

Run it the way the grader does:

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

## Originality

New document type (a resignation letter — not a receipt, not a library overdue
notice, not a hurricane warning), new wording, new layout. The ghost is the
official make.fun press-kit mark (https://make.fun/press/mark-1024.png),
worked into the letterhead and the stamp. No Rockstar artwork, logo or font.
