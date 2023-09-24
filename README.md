# BURN-XTN dApp can perform all project actions.
dApp: https://waves-dapp.com/3PAucbbumdUXmhzcR421zGiayphEdo2tRoz

Invocations callable by project owner or Puzzle master.
All XTN and BURN-XTN trading fees are burned.
if market price < ATH in wavelets, then price growth = remaining trading fees buyback and burn BURN-XTN.
if market price > ATH in wavelets, then pool growth = remaining trading fees buy BURN-XTN and add liquidity to pool.
dApp is triggered every week manually, besides performing the above project actions, it also tracks:
- ATH price in wavelets
- ATH price in centlets
- TVL project in WAVES excluding BURN-XTN
- TVL pool in WAVES excluding BURN-XTN
- Price growth %
- XTN total burned
- BURN-XTN total burned


# Waves DAO unstake and return funds

dApp: https://waves-dapp.com/3PHLhWPrs1mrpM1ZDUv1VmUnZRwchADJELc

Invocations callable by project owner or Puzzle master.

Every function unstakes LP and transfers to Waves DAO wallet.

unstakeTsunamiXTNvault
Withdraw limit is 25% of total stake, view limit: https://waves-dapp.com/3P7x1gG55wno1Q3kDvVwnmzWWRkMr2nTXLm

Invoke: view_withdrawLimit, string: 3PHLhWPrs1mrpM1ZDUv1VmUnZRwchADJELc, popup error with the amount
