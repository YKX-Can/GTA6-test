# GTA 6 meme — make.fun bounty entry

[![make.fun bounty: Post a GTA 6 meme on X](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01)
[![Live rank](https://make.fun/badge/gta6-meme-x-01/YKX-Can/GTA6-test/rank.svg)](https://make.fun/bounty/gta6-meme-x-01)
[![Live reward](https://make.fun/badge/gta6-meme-x-01/YKX-Can/GTA6-test/reward.svg)](https://make.fun/bounty/gta6-meme-x-01)

Entry for the make.fun bounty **Post a GTA 6 meme on X**:
[bounty page](https://make.fun/bounty/gta6-meme-x-01), account @ykx-can.

- `meme.webp` — the meme image (first image of the X post). Joke: waiting for
  GTA VI since 2013, still "coming soon"; features the make.fun ghost mascot
  holding a make.fun sign.
- `POST.json` — `{"url": "<the X post URL>"}`; replace the placeholder with
  the real post address after posting.
- `main.ts` — Node 22 program (standard library only) that copies POST.json
  into the output directory, as required by the bounty harness.

Local check:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/POST.json
```

X post copy:

```text
POV: you started waiting for GTA VI in 2013… and you're STILL early 😭

I built this on make.fun @makefunai #gta6 #makefun
https://make.fun/bounty/gta6-meme-x-01
```
