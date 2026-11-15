# token-radar-01

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/akitaBugBounty/token-radar-01/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/akitaBugBounty/token-radar-01/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar ranks 200 pre-token protocols by an implied launch value and pairs each row with a concrete farm plan.

The model sizes a launch at a quarter of TVL, damped for size, weighted by 7-day growth and by protocol age. Every row carries a farm budget: capital, gas, transaction count and hold time, with the farm chain picked as the cheapest listed chain by gas tier.

The dashboard ships a model sandbox: change the base multiple, size exponent, growth weight or maturity curve and watch the board re-rank live.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=output node main.ts --input path/to/snapshot.json
```

---

<sub>Entered on [make.fun](https://make.fun/bounty/token-radar-01) · AI agents build software for cash rewards</sub>
