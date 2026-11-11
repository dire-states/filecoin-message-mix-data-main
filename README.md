# filecoin-message-mix data: mainnet

Messages on the Filecoin **mainnet**, counted by receiving actor type and method, for the
[filecoin-message-mix](https://dire-states.github.io/filecoin-message-mix/) site
([source](https://github.com/dire-states/filecoin-message-mix)). This file is generated on every update.

Covered: height 6530801 (2026-11-09 13:20 UTC) to 6536008 (2026-11-11 08:44 UTC).
Last update: 2026-11-11 08:54 UTC.

## Last 30 days

| Day (hourly CSV) | Messages | Top methods |
|---|---|---|
| [2026-11-11](days/2026/11/2026-11-11.csv) | 15,833 | miner.SubmitWindowedPoSt 5,335, evm.InvokeContract 4,147, account.Send 2,829 |
| [2026-11-10](days/2026/11/2026-11-10.csv) | 45,101 | miner.SubmitWindowedPoSt 14,642, evm.InvokeContract 13,220, miner.ExtendSectorExpiration2 5,880 |
| [2026-11-09](days/2026/11/2026-11-09.csv) | 18,415 | miner.SubmitWindowedPoSt 6,529, evm.InvokeContract 6,279, miner.ExtendSectorExpiration2 1,654 |

Months: [2026-11](days/2026/11)

## Files

- `daily.csv`: `date,actor,method,messages` for the whole history, one row per day and method.
- `days/YYYY/MM/YYYY-MM-DD.csv`: `hour,actor,method,messages`, hourly rows for one UTC day.
- `index.json`: covered heights, gaps, days, and totals per method (read by the site).

Messages count at the height of the tipset that includes them; hours and days are UTC. `actor` is the
receiver's actor type (`unknown` if it no longer exists), and method `Send` is a plain transfer.
Methods that are not in the current builtin actors show as `#<number>`.
