# Big 12 Championship Simulator

Phone and desktop app: https://nbullen.github.io/big12-championship-simulator/

Pick a team to theme the entire app with its colors. Lock winners, simulate the remaining conference schedule, then view a labeled horizontal Possible Opponents bar chart, including each team's logo, count and percentage of all50,000 sampled seasons. Additional championship-appearance and pregame charts are expandable.

All24remaining games use dated ESPN Matchup Predictor probabilities. Records are the November9,2026snapshot; probabilities were retrieved November10MST. Independent draws do not update team strengths after hypothetical wins. Source-rounded100.1% pairs are normalized only for drawing, with the original percentages retained and disclosed.

Static GitHub Pages hosting: no home server, login, credentialed backend or runtime API dependency. Picks stay in browser storage. Generated script-hash CSP disallows arbitrary scripts and background network connections; logos are embedded. This does not guarantee the safety of the whole GitHub account, device or network.

Unofficial app, not affiliated with the Big 12 or ESPN. Team logos/trademarks belong to their respective owners. Sources and model limitations are inside the app.

## Simulation count

Each batch runs50,000 ESPN-weighted seasons. Progress and all chart denominators use the same configured total. Short yielding batches keep controls responsive; editing picks cancels stale results. Locked picks remain fixed in every simulation.
