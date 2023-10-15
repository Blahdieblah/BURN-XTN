# BURN-XTN dApp can perform all project actions.
dApp: https://waves-dapp.com/3PAucbbumdUXmhzcR421zGiayphEdo2tRoz

All XTN and BURN-XTN trading fees are burned.

if market price < ATH in wavelets, then PUMP = remaining trading fees buyback and burn BURN-XTN.

if market price > ATH in wavelets, then GROW = remaining trading fees buy BURN-XTN and add liquidity to pool.

dApp is triggered every week manually, besides performing the above project actions, it also tracks:
- ATH price in wavelets
- ATH price in centlets
- TVL project in WAVES excluding BURN-XTN
- TVL pool in WAVES excluding BURN-XTN
- Price growth %
- XTN total burned
- BURN-XTN total burned

## If dApp is not activated by project owner
After 8 days, then dApp function: PumpByAnybody, becomes callable by anybody.
This function performs tokenomics mode: PUMP

# Waves DAO unstake and return funds

dApp: https://waves-dapp.com/3PHLhWPrs1mrpM1ZDUv1VmUnZRwchADJELc

Every function unstakes LP and transfers to Waves DAO wallet.

If the project actions dApp is not activated for 30 days, then functions: _byWavesDAO, can be called by Waves DAO address: 3PEwRcYNAUtoFvKpBhKoiwajnZfdoDR6h4h

unstakeTsunamiXTNvault
Withdraw limit is 25% of total stake, view limit: https://waves-dapp.com/3P7x1gG55wno1Q3kDvVwnmzWWRkMr2nTXLm

Invoke: view_withdrawLimit, string: 3PHLhWPrs1mrpM1ZDUv1VmUnZRwchADJELc, popup error with the max withdrawable amount

unstakeTsunamiWAVESvault
Withdraw limit is 25% of total stake, view limit: https://waves-dapp.com/3P8nCfN4vnzDp6twckBEs29g95eR3RKQdGd 

Invoke: view_withdrawLimit, string: 3PHLhWPrs1mrpM1ZDUv1VmUnZRwchADJELc, popup error with the amount
