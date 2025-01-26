# [Unisocks](https://unisocks.exchange)

An experiment in dynamically priced merch.

## Environment Variables

The following environment variables are required for the application to run:

- `FAUNADB_SERVER_SECRET`
- `REACT_APP_PROVIDER_URL`
- `REACT_APP_SITE_RECAPTCHA_KEY`
- `Base58`
- `Hex`

## Note

Burned TRX = the amount of bandwidth consumed * the unit price of bandwidth

The amount of bandwidth obtained = the amount of TRX staked for obtaining bandwidth / the total amount of TRX staked for obtaining bandwidth in the whole network  * 43_200_000_000

Free bandwidth balance = freeNetLimit - freeNetUsed

Bandwidth balance obtained by staking TRX = NetLimit - NetUsed

Burned TRX = Energy quantity * the unit price of Energy

The amount of energy obtained = the amount of TRX staked for obtaining energy / the total amount of TRX staked for obtaining energy in the whole network * 180_000_000_000

Energy Balance = EnergyLimit - EnergyUsed

energy_factor = min((1 + energy_factor) * (1 + increaese_factor)-1, max_factor)

energy_factor = max((1 + energy_factor) * (1 - decrease_factor)- 1, 0)

wallet> freezeBalanceV2 1000000 0
