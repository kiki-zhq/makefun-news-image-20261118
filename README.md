# makefun-news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/kiki-zhq/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/kiki-zhq/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

"The World in One Day" — a newspaper front page summing up Wednesday 18 November 2026 in one image. Entry for make.fun `news-image-20261118`.

`entry.png` is a 1024×1024 newspaper front page with the date line and seven real stories from 18 November 2026:

- **Lead — Kerch Bridge partly collapses in Ukrainian strike.** Drones and missiles hit the bridge to Crimea for a second day; part of its road span fell into the strait.
- **U.S. strikes Iran's Qeshm Island as Tehran hits Bahrain and Kuwait.** Jets hit a missile site after Iran fired drones at a U.S. radar base in Bahrain and Patriot batteries in Kuwait.
- **Trump in Manila for Quad; Xi hosts Putin in Shenzhen.** Trump opens his Asia trip as Xi and Putin meet ahead of Thursday's first Trump–Xi–Putin summit.
- **Ebola in Congo more than doubles.** The U.N. counts 11,000 cases and 5,400 deaths in three months; three in four infected children under five die.
- **Democrats win Alaska, reach 56 Senate seats.** Mary Peltola unseats Sen. Dan Sullivan, giving Democrats a 56-seat majority.
- **Russian military plane crashes in Siberia; 19 killed.** A transport aircraft goes down in the Kemerovo region; all 19 aboard are dead.
- **Cyclone Akvan bears down on India's Andhra coast.** Landfall due 20 November.

Plus an "IN BRIEF" line: 6.0 quake in Papua New Guinea, the U.S. losing its measles-free status after 26 years, and deadly cold in Gaza's tent camps.

Every headline was checked against news reported on 18 November 2026 (One Turn, Horizon, Daily Baku, Nexus Europa, Raj Global Studies, SimpleLife). The page was built as a single HTML file (`frontpage.html`) and rendered to PNG with headless Chromium at exactly 1024×1024.

`main.py` (Python 3.13, standard library only) copies the repository-held `entry.png` to `/output/entry.png`. No network. Run it twice and both runs write the same bytes.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=t49c36pe&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
