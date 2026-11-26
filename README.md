# filecoin-message-mix data: mainnet

Messages on the Filecoin **mainnet**, counted by receiving actor type and method, for the
[filecoin-message-mix](https://dire-states.github.io/filecoin-message-mix/) site
([source](https://github.com/dire-states/filecoin-message-mix)). This file is generated on every update.

Covered: height 6530801 (2026-11-09 13:20 UTC) to 6580915 (2026-11-26 22:57 UTC).
Last update: 2026-11-26 23:07 UTC.
Gaps (heights the node no longer had): 6538639-6551200.

## Last 30 days

| Day (hourly CSV) | Messages | Top methods |
|---|---|---|
| [2026-11-26](days/2026/11/2026-11-26.csv) | 44,137 | miner.SubmitWindowedPoSt 13,782, evm.InvokeContract 9,608, miner.ExtendSectorExpiration2 8,601 |
| [2026-11-25](days/2026/11/2026-11-25.csv) | 43,260 | evm.InvokeContract 14,334, miner.SubmitWindowedPoSt 14,326, account.Send 8,845 |
| [2026-11-24](days/2026/11/2026-11-24.csv) | 45,502 | evm.InvokeContract 15,624, miner.SubmitWindowedPoSt 14,417, account.Send 8,169 |
| [2026-11-23](days/2026/11/2026-11-23.csv) | 42,496 | evm.InvokeContract 15,184, miner.SubmitWindowedPoSt 14,460, account.Send 7,432 |
| [2026-11-22](days/2026/11/2026-11-22.csv) | 38,895 | miner.SubmitWindowedPoSt 14,463, evm.InvokeContract 11,375, account.Send 8,374 |
| [2026-11-21](days/2026/11/2026-11-21.csv) | 44,695 | evm.InvokeContract 15,813, miner.SubmitWindowedPoSt 14,462, account.Send 10,664 |
| [2026-11-20](days/2026/11/2026-11-20.csv) | 53,197 | evm.InvokeContract 20,921, miner.SubmitWindowedPoSt 14,476, account.Send 10,636 |
| [2026-11-19](days/2026/11/2026-11-19.csv) | 52,775 | evm.InvokeContract 15,976, miner.SubmitWindowedPoSt 14,427, market.SettleDealPayments 10,320 |
| [2026-11-18](days/2026/11/2026-11-18.csv) | 50,979 | miner.SubmitWindowedPoSt 14,489, evm.InvokeContract 12,572, account.Send 11,794 |
| [2026-11-17](days/2026/11/2026-11-17.csv) | 52,613 | miner.SubmitWindowedPoSt 14,484, evm.InvokeContract 13,965, account.Send 10,670 |
| [2026-11-16](days/2026/11/2026-11-16.csv) | 16,338 | evm.InvokeContract 5,460, miner.SubmitWindowedPoSt 5,267, market.SettleDealPayments 2,061 |
| [2026-11-12](days/2026/11/2026-11-12.csv) | 21,695 | miner.ExtendSectorExpiration2 10,244, miner.SubmitWindowedPoSt 4,066, account.Send 3,615 |
| [2026-11-11](days/2026/11/2026-11-11.csv) | 38,959 | miner.SubmitWindowedPoSt 14,612, evm.InvokeContract 12,391, account.Send 5,245 |
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
