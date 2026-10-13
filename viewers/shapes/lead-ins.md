# What led into the top attacking shapes (RLC-152)

Champion 1+: 8,423 entries into the top 5 attacking shapes of RLC-150 (ball in the defenders' third; 0 games without state files skipped), 14.3% followed by a goal within 5 s. Ours: 117 entries, 19.7% followed by a goal. For each entry, the 10 s before it: where the ball was, and the last 3 touches (runs by one player collapsed), each named by the toucher's role at the entry. Touches are credited to the car that made them when the replay names it, and otherwise to the nearest car on the 0.5 s grid, so roles are approximate. Only lead-ins with at least 150 entries; lift is the goal rate over all entries'. Descriptions of what preceded better teams' best shapes, not plays: choosing one to try is the team's call.

The target shapes:

1. first man on the ball (<1000); second man tight (<1000 behind); last man in their third; narrow (<3500); someone past the ball; first man driving at goal (>500); lined up toward goal (cos > 0.7)
2. first man on the ball (<1000); second man tight (<1000 behind); last man in our half; narrow (<3500); nobody past the ball; first man driving at goal (>500); lined up toward goal (cos > 0.7)
3. first man on the ball (<1000); second man mid (1000-2500 behind); last man in our half; narrow (<3500); nobody past the ball; first man driving at goal (>500); lined up toward goal (cos > 0.7)
4. first man on the ball (<1000); second man tight (<1000 behind); last man in their half; narrow (<3500); someone past the ball; first man driving at goal (>500); lined up toward goal (cos > 0.7)
5. first man on the ball (<1000); second man mid (1000-2500 behind); last man in their half; narrow (<3500); nobody past the ball; first man driving at goal (>500); lined up toward goal (cos > 0.7)

## Where the ball came from

| lead-in | entries | share of entries | goal within 5 s | lift |
|---|---|---|---|---|
| ball in their third 10 s before, our half 5 s before | 802 | 9.5% | 15.6% | 1.09 |
| ball in middle 10 s before, middle 5 s before | 169 | 2.0% | 15.4% | 1.07 |
| ball in their third 10 s before, middle 5 s before | 488 | 5.8% | 15.2% | 1.06 |
| ball in their third 10 s before, their third 5 s before | 1673 | 19.9% | 15.0% | 1.05 |
| ball in our half 10 s before, middle 5 s before | 552 | 6.6% | 14.9% | 1.04 |
| ball in middle 10 s before, their third 5 s before | 590 | 7.0% | 14.7% | 1.03 |
| ball in our half 10 s before, our half 5 s before | 2579 | 30.6% | 13.8% | 0.96 |
| ball in middle 10 s before, our half 5 s before | 532 | 6.3% | 13.7% | 0.96 |
| ball in our half 10 s before, their third 5 s before | 1038 | 12.3% | 12.9% | 0.90 |

## The last touches before the entry

| lead-in | entries | share of entries | goal within 5 s | lift |
|---|---|---|---|---|
| second man → a defender → second man | 164 | 1.9% | 23.2% | 1.62 |
| third man → second man → first man | 197 | 2.3% | 21.8% | 1.52 |
| first man → a defender → second man | 195 | 2.3% | 20.0% | 1.40 |
| first man → second man → first man | 198 | 2.4% | 18.7% | 1.30 |
| a defender → second man → first man | 917 | 10.9% | 15.9% | 1.11 |
| a defender → third man → a defender | 180 | 2.1% | 15.0% | 1.05 |
| third man → a defender → second man | 155 | 1.8% | 14.8% | 1.04 |
| a defender → first man | 382 | 4.5% | 14.7% | 1.02 |
| first man → a defender → first man | 725 | 8.6% | 13.8% | 0.96 |
| second man → a defender → first man | 1044 | 12.4% | 13.8% | 0.96 |
| third man → a defender → first man | 884 | 10.5% | 13.5% | 0.94 |
| a defender → third man → first man | 448 | 5.3% | 12.9% | 0.90 |

## Both together

| lead-in | entries | share of entries | goal within 5 s | lift |
|---|---|---|---|---|
| ball in their third 10 s before, their third 5 s before; touches: a defender → second man → first man | 162 | 1.9% | 16.7% | 1.16 |
| ball in our half 10 s before, our half 5 s before; touches: a defender → second man → first man | 315 | 3.7% | 15.6% | 1.09 |
| ball in our half 10 s before, our half 5 s before; touches: second man → a defender → first man | 235 | 2.8% | 15.3% | 1.07 |
| ball in our half 10 s before, our half 5 s before; touches: first man → a defender → first man | 239 | 2.8% | 15.1% | 1.05 |
| ball in their third 10 s before, their third 5 s before; touches: third man → a defender → first man | 244 | 2.9% | 13.9% | 0.97 |
| ball in our half 10 s before, our half 5 s before; touches: a defender → first man | 153 | 1.8% | 13.7% | 0.96 |
| ball in our half 10 s before, their third 5 s before; touches: third man → a defender → first man | 161 | 1.9% | 13.7% | 0.95 |
| ball in our half 10 s before, our half 5 s before; touches: third man → a defender → first man | 183 | 2.2% | 12.0% | 0.84 |
| ball in their third 10 s before, their third 5 s before; touches: second man → a defender → first man | 268 | 3.2% | 11.6% | 0.81 |
| ball in our half 10 s before, their third 5 s before; touches: second man → a defender → first man | 167 | 2.0% | 10.2% | 0.71 |
| ball in their third 10 s before, their third 5 s before; touches: a defender → first man → a defender | 152 | 1.8% | 7.9% | 0.55 |
| ball in our half 10 s before, our half 5 s before; touches: a defender → first man → a defender | 239 | 2.8% | 5.4% | 0.38 |

## Ours, against Champion 1+

The six most productive lead-ins first, then the most common.

| last touches | Champion 1+ share of entries | Champion 1+ goal within 5 s | our share of entries | our entries |
|---|---|---|---|---|
| second man → a defender → second man | 1.9% | 23.2% | 2.6% | 3 |
| third man → second man → first man | 2.3% | 21.8% | 0.9% | 1 |
| first man → a defender → second man | 2.3% | 20.0% | 1.7% | 2 |
| first man → second man → first man | 2.4% | 18.7% | 0.0% | 0 |
| a defender → second man → first man | 10.9% | 15.9% | 5.1% | 6 |
| a defender → third man → a defender | 2.1% | 15.0% | 1.7% | 2 |
| second man → a defender → first man | 12.4% | 13.8% | 10.3% | 12 |
| third man → a defender → first man | 10.5% | 13.5% | 7.7% | 9 |
| a defender → first man → a defender | 8.9% | 8.7% | 12.0% | 14 |
| first man → a defender → first man | 8.6% | 13.8% | 6.0% | 7 |
| a defender → third man → first man | 5.3% | 12.9% | 6.0% | 7 |
| a defender → second man → a defender | 5.2% | 12.0% | 6.0% | 7 |
| a defender → first man | 4.5% | 14.7% | 4.3% | 5 |
| second man → first man → a defender | 2.8% | 5.0% | 5.1% | 6 |
