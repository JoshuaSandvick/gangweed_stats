# The shape vocabulary (RLC-149)

Champion 1 and above: 1,236 games; ours: 35 games. Every 0.5 s of live play, from each team's side as the attackers (attacking the goal at +y). Features: `a_first` the nearest attacker's distance to the ball, `a_gap` how much further the second attacker is, `a_last_y` where the deepest attacker is, `a_width` the attackers' spread across the field, `a_past` attackers past the ball; `d_first`, `d_goal_side` defenders between the ball and their goal, `d_last` the deepest defender's distance from their goal line, `d_width`, `d_parked` someone parked at the front post (RLC-146). Outcomes: the attackers score within 5 s; a **clean clear** within 5 s (a defender's touch, the ball out of the defenders' third within 2 s of it, no goal against within 10 s of the touch). One feature at a time, split by where the ball is: RLC-150 combines them and ranks by lift.

*Our share of time* is our team as the attackers for `a_` features and as the defenders for `d_` features.

### Ball in the defenders' third

Champion 1+ states: 431,632; goal for the attackers within 5 s 6.5%, clean clear within 5 s 48.2%.

**a_first**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <500 | 22.6% | 10.3% | 42.0% | 19.2% |
| 500-1000 | 25.8% | 6.8% | 46.6% | 26.7% |
| 1000-1500 | 19.5% | 5.6% | 49.2% | 21.3% |
| 1500-2500 | 21.6% | 4.5% | 51.7% | 23.4% |
| 2500+ | 10.5% | 3.4% | 56.2% | 9.3% |

**a_gap**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <500 | 18.9% | 6.7% | 50.0% | 21.8% |
| 500-1000 | 16.9% | 7.0% | 48.9% | 18.4% |
| 1000-2000 | 28.3% | 6.8% | 47.9% | 28.5% |
| 2000-3000 | 19.4% | 6.5% | 46.8% | 18.6% |
| 3000+ | 16.5% | 5.5% | 47.5% | 12.7% |

**a_last_y**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| own third | 29.2% | 5.3% | 51.1% | 16.2% |
| own half | 29.5% | 5.9% | 48.1% | 28.0% |
| their half | 29.2% | 7.1% | 46.3% | 36.0% |
| their third | 12.0% | 9.5% | 45.9% | 19.8% |

**a_width**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <2000 | 26.8% | 7.6% | 46.7% | 23.3% |
| 2000-4000 | 38.7% | 7.0% | 47.5% | 44.3% |
| 4000-6000 | 23.5% | 5.6% | 49.8% | 23.4% |
| 6000+ | 10.9% | 4.1% | 50.9% | 8.9% |

**a_past**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| 0 | 49.5% | 7.1% | 44.9% | 50.0% |
| 1 | 41.8% | 6.3% | 50.5% | 40.4% |
| 2 | 8.4% | 4.7% | 55.5% | 9.2% |
| 3 | 0.3% | 2.0% | 65.1% | 0.4% |

**d_first**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <500 | 27.0% | 5.2% | 53.0% | 24.7% |
| 500-1000 | 28.9% | 6.6% | 49.7% | 29.4% |
| 1000-1500 | 20.2% | 7.1% | 46.8% | 21.7% |
| 1500-2500 | 19.3% | 7.2% | 43.2% | 19.6% |
| 2500+ | 4.6% | 8.4% | 38.3% | 4.6% |

**d_goal_side**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| 0 | 9.7% | 11.7% | 35.6% | 11.4% |
| 1 | 31.9% | 7.5% | 44.6% | 31.4% |
| 2 | 39.2% | 5.6% | 50.8% | 34.8% |
| 3 | 19.2% | 4.2% | 55.4% | 22.3% |

**d_last**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <500 | 56.8% | 6.3% | 48.2% | 53.4% |
| 500-1000 | 21.4% | 6.2% | 49.9% | 21.2% |
| 1000-2000 | 15.5% | 6.7% | 48.9% | 17.9% |
| 2000-3500 | 5.7% | 8.4% | 43.0% | 6.6% |
| 3500+ | 0.5% | 21.1% | 17.9% | 0.9% |

**d_width**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <2000 | 24.3% | 6.9% | 46.9% | 25.4% |
| 2000-4000 | 45.2% | 6.2% | 48.5% | 45.8% |
| 4000-6000 | 23.3% | 6.4% | 48.9% | 21.3% |
| 6000+ | 7.3% | 7.3% | 48.4% | 7.5% |

**d_parked**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| no | 93.1% | 6.5% | 48.6% | 92.2% |
| yes | 6.9% | 7.5% | 42.7% | 7.8% |

### Ball in the middle third

Champion 1+ states: 370,065; goal for the attackers within 5 s 3.1%, clean clear within 5 s 60.5%.

**a_first**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <500 | 24.0% | 5.0% | 52.8% | 21.8% |
| 500-1000 | 24.6% | 3.6% | 57.4% | 24.4% |
| 1000-1500 | 18.9% | 2.5% | 61.6% | 19.4% |
| 1500-2500 | 22.9% | 1.8% | 65.9% | 24.8% |
| 2500+ | 9.5% | 1.1% | 72.9% | 9.5% |

**a_gap**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <500 | 21.3% | 2.7% | 61.8% | 24.6% |
| 500-1000 | 19.1% | 3.1% | 60.8% | 20.8% |
| 1000-2000 | 30.7% | 3.3% | 60.3% | 29.5% |
| 2000-3000 | 17.7% | 3.3% | 59.2% | 15.6% |
| 3000+ | 11.2% | 3.0% | 60.1% | 9.5% |

**a_last_y**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| own third | 76.3% | 2.8% | 62.0% | 70.8% |
| own half | 19.5% | 3.8% | 55.8% | 23.3% |
| their half | 4.1% | 4.9% | 54.4% | 5.7% |
| their third | 0.1% | 0.0% | 71.9% | 0.1% |

**a_width**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <2000 | 22.1% | 3.7% | 58.4% | 19.8% |
| 2000-4000 | 42.0% | 3.1% | 60.0% | 46.9% |
| 4000-6000 | 25.4% | 2.7% | 62.4% | 25.3% |
| 6000+ | 10.5% | 2.5% | 62.5% | 8.0% |

**a_past**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| 0 | 39.2% | 3.8% | 57.8% | 41.2% |
| 1 | 41.2% | 3.0% | 61.2% | 38.5% |
| 2 | 17.7% | 1.8% | 64.4% | 17.2% |
| 3 | 1.8% | 0.3% | 65.6% | 3.2% |

**d_first**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <500 | 20.7% | 1.9% | 72.2% | 19.2% |
| 500-1000 | 23.1% | 2.9% | 64.8% | 23.1% |
| 1000-1500 | 19.9% | 3.3% | 59.3% | 20.6% |
| 1500-2500 | 25.3% | 3.6% | 54.0% | 26.4% |
| 2500+ | 11.0% | 4.2% | 46.7% | 10.7% |

**d_goal_side**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| 0 | 2.0% | 14.2% | 26.9% | 3.7% |
| 1 | 19.5% | 5.4% | 52.1% | 19.5% |
| 2 | 42.3% | 2.8% | 61.9% | 38.4% |
| 3 | 36.2% | 1.5% | 65.3% | 38.5% |

**d_last**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <500 | 8.3% | 3.1% | 55.3% | 5.3% |
| 500-1000 | 14.6% | 2.8% | 58.3% | 11.5% |
| 1000-2000 | 23.9% | 2.7% | 59.5% | 22.5% |
| 2000-3500 | 28.5% | 2.9% | 62.1% | 29.1% |
| 3500+ | 24.7% | 3.9% | 62.6% | 31.5% |

**d_width**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| <2000 | 21.7% | 3.1% | 61.1% | 19.5% |
| 2000-4000 | 41.5% | 2.8% | 61.0% | 45.6% |
| 4000-6000 | 25.9% | 3.3% | 59.4% | 26.2% |
| 6000+ | 10.9% | 3.7% | 60.1% | 8.7% |

**d_parked**

| bin | Champion 1+ share of time | goal within 5 s | clean clear within 5 s | our share of time |
|---|---|---|---|---|
| no | 99.6% | 3.1% | 60.5% | 99.7% |
| yes | 0.4% | 4.6% | 47.7% | 0.3% |
