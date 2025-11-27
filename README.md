# qMINT-qUSD
Intergrated feature in the official qubic wallet that let's you use your qubic as collateral to mint qUSD

## What is qMINT?
qMINT is a **decentralized, feeless, over-collateralized minting protocol** on Qubic that lets anyone:
- Lock QUBIC as collateral  
- Instantly mint **qUSD** (a USD-pegged stablecoin)  
- Stay 100% exposed to QUBIC upside while having liquid USD  

**You never have to sell your QUBIC to get USD liquidity.**

## Core Features (v1)
- Collateral: **QUBIC only** (minimum 1000% ratio)  
- Minted asset: **qUSD** – 1:1 USD-pegged stablecoin  
- Mint fee: **0.1% one-time** on new positions only  
- Oracle: 30-minute TWAP via Qubic computors  
- Zero gas fees – 100% feeless & instant  
- No top-ups – each new deposit creates a brand-new position  
- Full on-chain, non-custodial, immutable smart contracts  

## Simple Use Case – How It Works

1. **You deposit QUBIC**  
   → Lock ~$10,000 worth of QUBIC (1000% collateral)  
   → Pay 0.1% mint fee once on the amount you want to mint e.g **1000 qUSD = $1.00 worth of QUBIC in mint fee**
   → Instantly receive **1,000 qUSD**

2. **Use your qUSD to get liquid**  
   → Re-invest, hold as USD 
   → Your original QUBIC stays locked and keeps rising with price

3. **When you want your QUBIC back**  
   → Burn/repay your qUSD during the open window  
   → Unlock your original QUBIC (minus fees if late)

4. **Bonus: re-invest your qubic to cover your original investment and get more liquid**  
   → Every time QUBIC pumps ≥100% → get **the oppunity re-invest easily**  
   → Keep growing your USD balance without any minting fees or any additional collateral.

 5. **FEES**
   → There are only 2 fee's
    New positions opened that were not a re-invest are subject to .1%
    Extensions past day 30 of locking period requires .01% fee of Qubic value based on base amount recieved to stay active if not received liquidation occurs.

 6. **First 30 of locking** 
   →  Days 0-3 collateral is hard locked unable to withdraw.
   → Day 4-30 colletral is to Re-payed
in full using the qUSD minted or by if available the Re-invest feature or by intiating extensions 
   → if none of the above been applied
full position gets liquidated and you keep the full amount recieved from minting

### The 3 types Reserves

1. **Primary Reserve**  
   Your own locked QUBIC. Starts at **1000 % varaible**. Price drop? No panic yet.

2. **Secondary Reserve**  
   QUBIC from people who forgot to repay.  
   Auto-used to keep everyone’s Principal **≥1000% varaible**.

3. **Tertiary Reserve**  
   Filled by mint fees + extension fees + 100 % of Secondary’s extra gains.  
   Final safety net — guarantees no price-crash liquidations ever.

Only way to lose collateral: you forget to repay.  
Crashes can’t hurt you — the reserves eat the loss instead.

# Fee Distribution & Reserve Mechanics (Simple & Transparent)

### Mint Fees and Extension Fees  
(Every time someone mints new tokens or extends a loan — same split for both)

| Percentage | Destination                  | Purpose                                      |
|------------|------------------------------|----------------------------------------------|
| 75%       | Tertiary Reserve             | Builds the giant long-term safety buffer    |
| 15%       | Burned forever               | Reduces total token supply → helps price     |
| 10%        | Treasury                     | Funds development, marketing, rewards, etc.  |

→ **75 / 15 / 10** split every single time.

### Secondary Reserve (day-to-day backing)
- Target: **1000% collateralization varaible** 
- If the requirements dectease the system automatically send excess collateral that is released gets split **100%**:
  - 100%% → Tertiary Reserve
    

### Tertiary Reserve (the big rainy-day / war-chest fund)
- Keeps growing with incoming fees
- Once its value reaches **850%**:
  - Everything **above that** is automatically distributed:
    - **75%** → Treasury (real usable funds to grow the project)
    - **25%** → Burned forever (ongoing deflation)

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
