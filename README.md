# qMINT-qUSD
Intergrated feature in the official qubic wallet that let's you use your qubic as collateral to mint qUSD

## What is qMINT?
qMINT is a **over-collateralized minting protocol** on Qubic that lets anyone:
- Lock QUBIC as collateral at 400%
- Instantly mint **qUSD** (a USD-pegged stablecoin)  
- Stay 100% exposed to QUBIC upside while having liquid USD  

**You never have to sell your QUBIC to get USD liquidity.**

## Core Features (v1)
- Collateral: **QUBIC only** (minimum 400% ratio)  
- Minted asset: **qUSD** – 1:1 USD-pegged stablecoin  
- Mint fee: **0.1% one-time** on new positions only (excluding reinvest)
- Oracle: 30-minute TWAP via Qubic computors  
- Zero gas fees – 100% feeless & instant  
- can top-up – incase collateral gets low you can add more in to keep the position opened
- Full on-chain, non-custodial, immutable smart contracts  

## Simple Use Case – How It Works

1. **You deposit QUBIC**  
   → Lock ~$4,000 worth of QUBIC (400% collateral)  
   → Pay 1.00% mint fee once on the amount you want to mint e.g **1000 qUSD = $10.00 worth of QUBIC in mint fee**
   → Instantly receive **1,000 qUSD**

2. **Use your qUSD to get liquid**  
   → Re-invest, hold as qUSD 
   → Your original QUBIC stays locked and keeps rising with price

3. **When you want your QUBIC back**  
   → Burn/repay your qUSD whenever  
   → Unlock your original QUBIC (less daily fee of .01% which is based of the amount of original mint amount in qubic)

4. **Bonus: re-invest your qubic to cover your original investment and get more liquid**  
   → Every time QUBIC pumps ≥100% → get **the oppunity re-invest easily** 
   → Keep growing your USD balance without any minting fees or any additional collateral and all daily fees reset to 0.

 5. **FEES**
   → There are only 2 fee's
    New positions opened that were not a re-invest are subject to 1%.
      → And .01% daily fee of the principal qubic deposited payed only when you withdraw and deducted from deposit.
    

### 2 types Reserve

1. **Primary Reserve**  
   Your own locked QUBIC. Starts at **400% varaible**.

2. **Secondary Reserve**  
   QUBIC from people who used the re-invest feature **400% varaible**

Only way to lose collateral: you forget to repay and would take over 100years in fees to eat up collateral 
if qubic drops significantly liquidation occurs anywhere where the value of the collateral falls below 100%.

# Fee Distribution & Reserve Mechanics (Simple & Transparent)

### Mint Fees and Daily fees  
(Every time someone mints new tokens or extends a loan — same split for both)

# Fee Distribution & Reserve Mechanics (Simple & Transparent)

| Percentage | Destination                  | Purpose                                      |
|------------|------------------------------|----------------------------------------------|
| 50%        | Treasury                     | Funds development, marketing, audits, rewards, listings, whatever the team needs |
| 50%        | Burned forever               | Permanently removes QUBIC from circulation → pure deflation |

No complicated reserves, no middlemen, no confusion.  
Half fuels growth, half gets torched.

## Why qMINT on Qubic?
- Feeless to send and recieve & instant → no gas anxiety  
- Native QUBIC collateral → perfect for everyone 
- True capital efficiency → be long QUBIC + hold USD at the same time  
- Foundation for future DeFi → qUSD becomes the base USD pair on Qubic  

## Current Status
- Devolopment: looking for dev team
- This is a **proposal only** – open for community review  

## Next Steps (if community wants it)
1. front and back end development  
2. Testnet deployment
3. Intergration with qubic official wallet
4. Community vote / funding  
5. Mainnet launch  

**qMINT = Stay Long QUBIC. Get USD Liquidity.**

The future of collateralised stable coins
