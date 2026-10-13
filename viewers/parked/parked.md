# Parked at the front post, against matched situations

Our games: 35. Pool: 1,369,736 Champion 1+ states from 1,236 games. An episode is one of us within 800 uu of our ball-side post at or below 500 uu/s with the ball in our half, on the 0.5 s situations grid (RLC-146's rule). Each episode's first moment is matched against the 50 nearest Champion 1+ states (one per game) by **the ball and the three attackers only**; the matched defenders are then read for the same rule.

## What matched Champion+ defenders were doing at the front post

| | episodes | seconds parked | matched states | someone parked there | there, moving | nobody at the post | median speed of a moving one | median match distance |
|---|---|---|---|---|---|---|---|---|
| Josh | 71 | 69 | 3550 | 10% | 33% | 57% | 996 uu/s | 888 uu |
| Jake | 88 | 78 | 4400 | 10% | 30% | 60% | 1021 uu/s | 863 uu |
| Mike | 136 | 122 | 6800 | 10% | 32% | 58% | 1048 uu/s | 892 uu |
| all | 295 | 269 | 14750 | 10% | 32% | 58% | 1027 uu/s | 882 uu |

Base rate, every pool state with the ball in the defending half (684,594): someone parked at the front post 5%, there and moving 19%.

## What happened next

Conceded within 3 s of the matched moment, by what the matched defenders were doing:

| matched defenders | conceded | states | rate | 95% interval |
|---|---|---|---|---|
| someone parked at the post | 97 | 1443 | 6.7% | 5.5–8.1% |
| at the post, moving | 339 | 4719 | 7.2% | 6.5–8.0% |
| nobody at the post | 610 | 8588 | 7.1% | 6.6–7.7% |

Our own episodes: 17 of 295 conceded within 3 s.

These are counts of what other teams did in similar spots, not a verdict on any one moment: a matched team is a Champion+ team that may have conceded, and the three groups above differ in more than where their defenders were. The intervals treat every matched state as independent, which they are not (one of our moments brings 50, and a source game can recur across moments), so the real uncertainty is wider. The matching stays `computed` until a sample of pairs has a `same_situation` verdict.

Step through the longest episodes beside their nearest matches: `viewer.html`.
