# Pressure spells and retreats (RLC-148)

A **pressure spell**: the ball and all three of a team's players in the opponents' half, whoever touched it last; it ends when the ball crosses into the team's own half or a goal is scored. A **retreat**: one of the three crossing back over halfway during the spell; its **depth** is how far past halfway they went (0 at halfway, 5120 at their own goal line), until they cross back or the spell ends. A retreat's **run** is the deepest point in the 3 s after it began, and what followed it is read on fixed horizons from that moment, so neither is cut short by the goal or clear it is compared with. A spell's outcome: *scored* (during the spell), *conceded* (during, or within 10 s of the end), *regained* (a new spell within 10 s, no goal between), *lost* (none of those).

## Across the ladder

| band | games | spells per game | retreats per spell | retreat run: median | p75 | p90 | retreats taking a big pad | spells scored | conceded |
|---|---|---|---|---|---|---|---|---|---|
| diamond-1 | 200 | 16.5 | 1.92 | 2854 | 4438 | 4835 | 27.0% | 17.8% | 10.2% |
| diamond-2 | 200 | 16.7 | 1.96 | 2854 | 4423 | 4840 | 27.2% | 16.6% | 10.8% |
| diamond-3 | 200 | 17.1 | 1.98 | 2790 | 4424 | 4835 | 28.1% | 17.0% | 9.4% |
| champion-1 | 200 | 18.0 | 2.08 | 2832 | 4400 | 4825 | 28.7% | 17.9% | 10.0% |
| champion-2 | 200 | 19.2 | 2.04 | 2770 | 4373 | 4786 | 28.2% | 16.8% | 9.2% |
| champion-3 | 200 | 19.2 | 2.09 | 2799 | 4386 | 4812 | 30.6% | 16.9% | 8.7% |
| grand-champion-1 | 200 | 20.4 | 2.09 | 2697 | 4346 | 4808 | 31.0% | 15.3% | 9.2% |
| grand-champion-2 | 200 | 20.9 | 2.11 | 2748 | 4355 | 4808 | 31.7% | 16.9% | 9.5% |
| grand-champion-3 | 200 | 19.6 | 2.00 | 2982 | 4420 | 4887 | 32.4% | 18.7% | 10.4% |
| supersonic-legend | 36 | 21.8 | 1.97 | 3087 | 4398 | 4891 | 32.0% | 17.8% | 10.8% |

Per-game median retreat run, Diamond 1 → Grand Champion 3 (Jonckheere–Terpstra, one value per game): tau-b +0.007, p = 0.69; Champion 1 vs Grand Champion 3: tau-b +0.100, p = 0.015.

### Only retreats that began with the ball in their third

Going back while the ball is near halfway is ordinary rotation; going back while the ball is deep in their end is what leaving the play looks like.

| band | games | spells per game | retreats per spell | retreat run: median | p75 | p90 | retreats taking a big pad | spells scored | conceded |
|---|---|---|---|---|---|---|---|---|---|
| diamond-1 | 200 | 16.5 | 1.20 | 2178 | 4259 | 4689 | 29.7% | 17.8% | 10.2% |
| diamond-2 | 200 | 16.7 | 1.26 | 2225 | 4304 | 4707 | 29.9% | 16.6% | 10.8% |
| diamond-3 | 200 | 17.1 | 1.26 | 2048 | 4264 | 4665 | 30.6% | 17.0% | 9.4% |
| champion-1 | 200 | 18.0 | 1.35 | 2126 | 4251 | 4636 | 30.3% | 17.9% | 10.0% |
| champion-2 | 200 | 19.2 | 1.28 | 2088 | 4231 | 4608 | 30.0% | 16.8% | 9.2% |
| champion-3 | 200 | 19.2 | 1.30 | 2131 | 4247 | 4608 | 32.9% | 16.9% | 8.7% |
| grand-champion-1 | 200 | 20.4 | 1.29 | 1950 | 4207 | 4608 | 33.3% | 15.3% | 9.2% |
| grand-champion-2 | 200 | 20.9 | 1.32 | 1891 | 4220 | 4608 | 33.1% | 16.9% | 9.5% |
| grand-champion-3 | 200 | 19.6 | 1.23 | 2156 | 4263 | 4608 | 34.8% | 18.7% | 10.4% |
| supersonic-legend | 36 | 21.8 | 1.23 | 2439 | 4268 | 4608 | 34.6% | 17.8% | 10.8% |

Per-game median of these: tau-b -0.051, p = 0.002; Champion 1 vs Grand Champion 3: tau-b +0.030, p = 0.46.

### Taking a big pad on the way back

Per-game share of retreats that took a big pad, Diamond 1 → Grand Champion 3: tau-b +0.170, p = 2.7e-24; Champion 1 vs Grand Champion 3: tau-b +0.217, p = 1.3e-07 (Holm over the two): **higher** with rank.

## Retreat run and what followed, Champion 1 and above (1236 games, 50059 retreats)

| retreat run past halfway | retreats | goal for within 10 s | goal against within 10 s | pressure still on 3 s later |
|---|---|---|---|---|
| 0–500 uu | 6671 | 11.9% | 3.4% | 90.2% |
| 500–1000 uu | 5465 | 10.7% | 3.1% | 81.5% |
| 1000–1500 uu | 4933 | 8.8% | 3.7% | 73.3% |
| 1500–2000 uu | 3416 | 8.5% | 4.0% | 60.0% |
| 2000–2500 uu | 2860 | 6.1% | 5.1% | 47.6% |
| 2500–3000 uu | 2658 | 4.5% | 6.0% | 38.3% |
| 3000–3500 uu | 2495 | 4.6% | 5.9% | 32.3% |
| 3500–4000 uu | 2724 | 3.4% | 8.2% | 25.7% |
| 4000–4500 uu | 8559 | 5.4% | 5.5% | 54.4% |
| 4500+ uu | 10278 | 4.5% | 8.5% | 27.0% |

### Only retreats that began with the ball in their third

| retreat run past halfway | retreats | goal for within 10 s | goal against within 10 s | pressure still on 3 s later |
|---|---|---|---|---|
| 0–500 uu | 5357 | 12.8% | 3.5% | 94.3% |
| 500–1000 uu | 4200 | 11.0% | 2.9% | 89.9% |
| 1000–1500 uu | 3606 | 9.3% | 3.5% | 83.4% |
| 1500–2000 uu | 2300 | 8.6% | 3.4% | 72.0% |
| 2000–2500 uu | 1787 | 6.2% | 4.3% | 60.5% |
| 2500–3000 uu | 1545 | 4.7% | 5.6% | 51.4% |
| 3000–3500 uu | 1348 | 4.8% | 5.6% | 45.0% |
| 3500–4000 uu | 1340 | 4.0% | 6.3% | 41.5% |
| 4000–4500 uu | 5343 | 6.4% | 4.7% | 71.1% |
| 4500+ uu | 4526 | 7.0% | 5.7% | 49.9% |

## Where the deepest player is during a spell, Champion 1 and above

| deepest player, from halfway | states (0.5 s) | goal for within 5 s | goal against within 10 s |
|---|---|---|---|
| -5000 to -4000 uu | 19769 | 3.8% | 5.0% |
| -4000 to -3000 uu | 21074 | 3.7% | 4.9% |
| -3000 to -2000 uu | 25437 | 3.6% | 5.0% |
| -2000 to -1000 uu | 39456 | 4.0% | 5.0% |
| -1000 to +0 uu | 67739 | 4.9% | 4.9% |
| +0 to +1000 uu | 93087 | 6.9% | 4.8% |
| +1000 to +2000 uu | 65565 | 9.0% | 4.8% |
| +2000 to +3000 uu | 31173 | 11.3% | 4.8% |
| +3000 to +4000 uu | 9155 | 15.1% | 5.8% |
| +4000 to +5000 uu | 1176 | 15.3% | 7.5% |

### Only moments with the ball in their third

| deepest player, from halfway | states (0.5 s) | goal for within 5 s | goal against within 10 s |
|---|---|---|---|
| -5000 to -4000 uu | 12952 | 5.1% | 4.0% |
| -4000 to -3000 uu | 13910 | 4.8% | 4.0% |
| -3000 to -2000 uu | 15853 | 4.9% | 4.0% |
| -2000 to -1000 uu | 26094 | 5.3% | 4.0% |
| -1000 to +0 uu | 52216 | 5.9% | 4.2% |
| +0 to +1000 uu | 79682 | 7.5% | 4.2% |
| +1000 to +2000 uu | 62085 | 9.3% | 4.3% |
| +2000 to +3000 uu | 30782 | 11.4% | 4.5% |
| +3000 to +4000 uu | 9094 | 15.2% | 5.6% |
| +4000 to +5000 uu | 1167 | 15.4% | 7.2% |

## Our games (35 games, 375 spells, 690 retreats)

| band | games | spells per game | retreats per spell | retreat run: median | p75 | p90 | retreats taking a big pad | spells scored | conceded |
|---|---|---|---|---|---|---|---|---|---|
| ours | 35 | 10.7 | 1.84 | 2360 | 4247 | 4775 | 18.8% | 20.0% | 9.9% |

With the ball in their third when the retreat began:

| band | games | spells per game | retreats per spell | retreat run: median | p75 | p90 | retreats taking a big pad | spells scored | conceded |
|---|---|---|---|---|---|---|---|---|---|
| ours | 35 | 10.7 | 1.07 | 1352 | 3428 | 4574 | 20.4% | 20.0% | 9.9% |

| player | retreats | median run | p75 | p90 | took a big pad | of which ball in their third | median run then | p90 then |
|---|---|---|---|---|---|---|---|---|
| Josh | 245 | 2352 | 4255 | 4847 | 18.0% | 136 | 1472 | 4282 |
| Jake | 224 | 1976 | 4193 | 4730 | 20.5% | 138 | 1308 | 4571 |
| Mike | 221 | 2650 | 4275 | 4788 | 18.1% | 128 | 1335 | 4590 |

| retreat run past halfway | retreats | goal for within 10 s | goal against within 10 s | pressure still on 3 s later |
|---|---|---|---|---|
| 0–500 uu | 121 | 10.7% | 2.5% | 86.0% |
| 500–1000 uu | 88 | 14.8% | 3.4% | 86.4% |
| 1000–1500 uu | 70 | 7.1% | 2.9% | 72.9% |
| 1500–2000 uu | 41 | 4.9% | 2.4% | 65.9% |
| 2000–2500 uu | 35 | 11.4% | 5.7% | 48.6% |
| 2500–3000 uu | 39 | 5.1% | 0.0% | 43.6% |
| 3000–3500 uu | 51 | 2.0% | 5.9% | 13.7% |
| 3500–4000 uu | 45 | 2.2% | 6.7% | 20.0% |
| 4000–4500 uu | 66 | 1.5% | 9.1% | 25.8% |
| 4500+ uu | 134 | 4.5% | 13.4% | 21.6% |

| deepest player, from halfway | states (0.5 s) | goal for within 5 s | goal against within 10 s |
|---|---|---|---|
| -5000 to -4000 uu | 139 | 10.1% | 4.3% |
| -4000 to -3000 uu | 143 | 3.5% | 5.6% |
| -3000 to -2000 uu | 236 | 3.0% | 6.4% |
| -2000 to -1000 uu | 472 | 3.4% | 4.4% |
| -1000 to +0 uu | 1075 | 4.6% | 5.6% |
| +0 to +1000 uu | 1653 | 5.7% | 4.8% |
| +1000 to +2000 uu | 1312 | 10.0% | 4.3% |
| +2000 to +3000 uu | 755 | 13.8% | 4.6% |
| +3000 to +4000 uu | 257 | 14.8% | 8.9% |
| +4000 to +5000 uu | 42 | 9.5% | 4.8% |

With the ball in their third:

| deepest player, from halfway | states (0.5 s) | goal for within 5 s | goal against within 10 s |
|---|---|---|---|
| -5000 to -4000 uu | 97 | 14.4% | 3.1% |
| -4000 to -3000 uu | 82 | 6.1% | 6.1% |
| -3000 to -2000 uu | 107 | 4.7% | 6.5% |
| -2000 to -1000 uu | 266 | 5.3% | 4.1% |
| -1000 to +0 uu | 769 | 6.2% | 4.0% |
| +0 to +1000 uu | 1393 | 6.7% | 4.1% |
| +1000 to +2000 uu | 1238 | 10.6% | 4.0% |
| +2000 to +3000 uu | 750 | 13.9% | 4.7% |
| +3000 to +4000 uu | 252 | 15.1% | 7.9% |
| +4000 to +5000 uu | 42 | 9.5% | 4.8% |

## Dead-zone retreats: moments to watch (87)

Retreats begun with the ball in their third whose 3 s run ended 2000–4000 uu past halfway without a big pad. In Champion 1+ games what follows these is the worst of any depth, but that can run backwards (a player who sees the pressure breaking goes back), so each is a moment to watch, not a mistake. Judge them in `dead-zone.tsv`.

| player | moments | of their retreats with the ball in their third |
|---|---|---|
| Josh | 35 | 25.7% |
| Jake | 27 | 19.6% |
| Mike | 25 | 19.5% |

The 12 newest, players in turn, step through in `viewer.html`.
