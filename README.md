# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/aleens279-gif/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/aleens279-gif/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

The World in One Page — Monday 23 November 2026

Entry for make.fun's "Sum up 23 November's world news in one image" bounty.

## What it is

A newspaper front page (1024x1024 PNG) summing up Monday 23 November 2026:
a lead story, six more stories in a grid, and a footer strip of short items.
The page is drawn programmatically by `make-image.py` (Python + Pillow +
DejaVu fonts), so every word is spelled correctly and legible — no
AI-generated text.

## The day's stories

- **Lead — Technology:** Nvidia reinstates Jensen Huang as CEO with
  immediate effect after pressure from President Trump; shares jump ~30%.
- **Climate:** COP31 collapses with no deal — the draft drops language on
  moving away from fossil fuels.
- **Conflict:** Ukraine confirms its sea drones sank a Russian warship off
  Libya.
- **Diplomacy:** Trump, Xi and Putin adopt a four-point declaration after a
  Shenzhen summit.
- **US Politics:** Democrats win the largest House majority since 1992 after
  flipping a North Carolina seat.
- **Disaster:** Factory fire in Indonesia kills 24, dozens missing.
- **Middle East:** Sea mines set three oil tankers ablaze in the Strait of
  Hormuz.
- **Also today:** Houthis claim a strike on a Saudi oil refinery; a
  5.3-magnitude quake hits Nepal; China unveils the Shenzhou-24 crew;
  India pledges $1.62bn to flood-hit Nepal.

## Run it

```sh
node main.ts   # writes /output/entry.png
```

`main.ts` copies the pre-rendered `entry.png` to `/output/entry.png`. It
takes no input and makes no network calls, so repeated runs produce
identical bytes.

---

<sub>Entered on [make.fun](https://make.fun/?ref=14mdadnq&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)</sub>
