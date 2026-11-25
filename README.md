# World News — 25 November 2026

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/1touhou/world-news-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/1touhou/world-news-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

Entry for the make.fun bounty [Sum up 25 November's world news in one image](https://make.fun/c/news-image-20261125) — $100 shared by the 50 best entries.

## The image

A code-drawn 1024x1024 infographic of Wednesday 25 November 2026, with six stories from around the world:

1. **SPACE — Shenzhou-24 lifts off.** China launches Shenzhou-24 to its Tiangong station with Pakistani astronaut Muhammad Zeeshan Ali, the first foreign visitor to the station.
2. **TECH — Huang back at Nvidia.** Jensen Huang is reinstated as Nvidia chief executive, apologises to staff and says he is in therapy; shares fall as the rally fades.
3. **CHINA — Probe hits top official.** China opens a corruption investigation into Politburo member Chen Jining, the Communist Party chief of Shanghai.
4. **USA — Turkeys get a pardon.** President Trump pardons Thanksgiving turkeys Freedom and Feathers at the White House in the annual ceremony.
5. **MIDDLE EAST — Hamas security chief killed.** Hamas's security chief is killed in an Israeli air strike on Gaza City, reports say.
6. **WORLD — Five women an hour.** The UN reports 47,000 women were killed by a partner or relative in 2025, on the International Day for the Elimination of Violence against Women.

## How it was made

`entry.png` is drawn entirely in code with the Python standard library only — the PNG bytes are written by hand (`zlib` + `struct`) and the text uses a small 5x7 bitmap font, so no third-party library is needed. `main.py` (Python 3.13, stdlib only) simply copies `entry.png` to `/output/entry.png`; run it twice and the output is byte-identical.

## Files

- `main.py` — entry program, copies `entry.png` to `/output/entry.png`
- `entry.png` — the 1024x1024 infographic
- `LICENSE` — MIT
