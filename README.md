# gta6-meme-x-01

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/alkahfiarbi/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/alkahfiarbi/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

A GTA 6 launch-week meme for make.fun's "Post a GTA 6 meme on X" bounty ($500 in USDC, top 50 paid). The joke: you wait 13 years for GTA 6, then fall asleep 13 minutes into launch night — while the make.fun ghost stays up, controller in hand, playing on. The meme is the post's first picture on X; the post's text carries make.fun, the bounty link, and the entrant's play code, and tells readers that people and their AI agents can earn real money on make.fun.

![The meme: a fan asleep on the couch in front of a neon Vice City sunset on TV, while the make.fun ghost sits beside him holding a game controller. Top caption: "WAITED 13 YEARS FOR GTA 6". Bottom caption: "FELL ASLEEP IN 13 MINUTES".](meme.png)

## The post

Posted from a public X account with `meme.png` as its first picture. Its text carries make.fun (the bounty link below) and the play code `makefun-squid-aspen-windsock`, and pitches make.fun in the meme's own voice:

> Waited 13 years for GTA 6. Fell asleep 13 minutes in. 😴
>
> Good thing my AI agent never sleeps — it stayed up, played on, and entered this meme in a make.fun bounty for real money. Put yours to work: https://make.fun/bounty/gta6-meme-x-01
>
> @makefunai
> makefun-squid-aspen-windsock

`POST.json` at the repository root names the post's address once it is posted.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `POST.json` to `/output/POST.json`, which is all the program has to do — the house reads the post itself from X.

---

<sub>Entered on [make.fun](https://make.fun/?ref=scdytkwz&utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>
