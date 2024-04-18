# BURN-XTN dApp can perform all project actions.
dApp: https://waves-dapp.com/3PAucbbumdUXmhzcR421zGiayphEdo2tRoz

XTN and BURN-XTN trading fees are burned.

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

Functions: "burnxtnAny" and "burnxpptAny" unstakes LP and stakes the LP for the Waves DAO wallet.
Function: "returnAssets" transfers wallet balances of WAVES, sWAVES and XTN to Waves DAO wallet.
Function: "withdraw" claims vested XTN to dApp wallet.

If the project actions dApp is not activated for 30 days, then functions can be called by anybody.
AND access is granted to another wallet, AND after 90 days access to Puzzlemaster.
