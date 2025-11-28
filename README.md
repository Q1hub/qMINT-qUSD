# qMINT-qUSD
Intergrated feature in the official qubic wallet that let's you use your qubic as collateral to mint qUSD

## What is qMINT?
qMINT is a **over-collateralized minting protocol** on Qubic that lets anyone:
- Lock QUBIC as collateral at 400%
- Instantly mint **qUSD** (a USD-pegged stablecoin)  
- Stay 100% exposed to QUBIC upside while having liquid USD  

**You never have to sell your QUBIC to get USD liquidity.**

## Core Features (v1)
- Collateral: **QUBIC only** (Starting at 400% ratio)  
- Minted asset: **qUSD** – 1:1 USD-pegged stablecoin  
- Mint fee: **0.1% one-time** on new positions only (excluding reinvest)
- Oracle: 30-minute TWAP via Qubic computors  
- Zero gas fees – 100% feeless & instant  
- can top-up – incase collateral gets low you can add more in to keep the position opened
- Full on-chain, non-custodial, immutable smart contracts
- Hard locked after every new mint, top up or reinvest for 72hrs(You cannot unlock the deposit of qubic for atleast 72hrs)

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
   → Unlock your original QUBIC (less daily fee of .01% which is based of the amount of original principle amount in qubic)

4. **Bonus: re-invest your qubic to cover your original investment and get more liquid**  
   → Every time QUBIC pumps ≥100% → get **the oppunity re-invest easily** 
   → Keep growing your USD balance without any minting fees or any additional collateral and all daily fees reset to 0 and only use the colleteral requirement amount needed  of qubic to cover the original position.

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
(Every time someone mints new tokens or withdraw collateral — same split for both)

# Fee Distribution & Reserve Mechanics (Simple & Transparent)

| Percentage | Destination                  | Purpose                                      |
|------------|------------------------------|----------------------------------------------|
| 50%        | Treasury                     | Funds development, marketing, audits, rewards, listings, whatever the team needs |
| 50%        | Burned forever               | Permanently removes QUBIC from circulation → pure deflation |

Burned amount held in a a smart contract if the the qubic value drops below 110% portions of the burn amount allocated to burn each minute until collateral value goes over 150% 

## Why qMINT on Qubic?
- Feeless to send and recieve & instant → no gas anxiety  
- Native QUBIC collateral → perfect for everyone 
- True capital efficiency → be long QUBIC + hold USD at the same time  
- Foundation for future DeFi → qUSD becomes the base USD pair on Qubic

- ### qMINT/qUSD – Burn Fund: Two Jobs, One Fund (Final & Immutable)

**Funding**  
- Receives **50% of every mint fee (0.1%)**  
- Receives **50% of every daily fee (0.01%/day)**  
- Lives in its own dedicated, untouchable smart contract

**Job 1 – Bear-Market Self-Healing (Liquidation Shield)**  
- Activates instantly when **any** position falls **< 110%**  
- Burns its own QUBIC every minute to reduce circulating qUSD supply  
- Keeps burning until the position is back **≥ 125%** (or fund is empty)  
- True open-market liquidation only if ratio drops **< 105%** AND Burn Fund is already exhausted  
→ 99.9% of normal/bear-market liquidations never happen

**Job 2 – Bull-Market Efficiency Engine (Dynamic Mint Ratio)**  
- Constantly calculates global over-collateralization:  
  `(Total QUBIC in Primary + Secondary + Burn Fund) ÷ Total qUSD in circulation`  
- When global ratio hits **≥ 500%** (+100% extra buffer):  
  - Minimum mint ratio for **new mints** drops automatically  
  - Drops **10 percentage points for every additional +100% buffer**  
  - Hard floor = **120%** (can never go lower)  

| Global System Ratio | New User Minimum Ratio |
|---------------------|------------------------|
| 400–499%            | 400%                   |
| 500–599%            | 390%                   |
| 600–699%            | 380%                   |
| …                   | …                      |
| ≥ 1,280%            | 120% (floor)           |

**Result**  
One fund. Zero governance.  
Bear markets → silently saves everyone  
Bull markets → silently unlocks capital efficiency down to 120%  
No other stablecoin has this dual-mode, fully automatic flywheel in 2025.

Pure on-chain magic.

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
