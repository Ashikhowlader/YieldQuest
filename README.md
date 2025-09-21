YieldQuest

Gamified Yield Vault with AI Copilot on Kaia Kairos Testnet.
Stake mock USDT, complete quests, unlock APY boosts, and claim rewards — all while being guided by an in-app AI advisor.

Features
EarnQuestsVaultV3.sol

Deposit & withdraw USDT

Claim staking rewards

Special quests: Hold 24h, Stake 1000+, 7-Day Loyalty, Active User

Dynamic APY multiplier system


FakeUSDT.sol

ERC-20 mock USDT token for Kaia Kairos Testnet

Lets users test staking without real funds


Gamified UX

Confetti & quest completion indicators

AI copilot to explain yields, balances, and quests

Simple dashboard to track wallet, vault, pending rewards


Deployment (Kaia Kairos Testnet)
EarnQuestsVaultV3.sol:
0xC3A0B5304456EaC195BE12984EC1cc30d3319760

FakeUSDT.sol:
0xb9D271c9d205c1e94EBFfed8583F3FF3Ca3831E8

Chain ID: 0x3e9 (1001 decimal)
Explorer: https://kairos.kaiascan.io/

Contract ABIs (summary)

EarnQuestsVaultV3.sol

function deposit(uint256 amount) external
function withdraw(uint256 amount) external
function claim() external
function completeHold24hQuest() external
function completeStake1000Quest() external
function completeLoyalty7dQuest() external
function completeActiveUserQuest() external
function balanceOf(address user) view returns(uint256)
function pendingRewards(address user) view returns(uint256)
function hasCompleted(address user, string quest) view returns(bool)
function getCurrentBaseAPY() view returns(uint256)
function getUserMultiplier(address user) view returns(uint256)

FakeUSDT.sol

function approve(address spender, uint256 amount) returns (bool)
function balanceOf(address) view returns (uint256)
function decimals() view returns (uint8)

Demo & Assets
Frontend (Live dApp): [Insert Netlify/Vercel link]
Demo Video: [YouTube or Loom link]
Pitch Deck (PDF): [Insert link]

Build & Run Locally

git clone https://github.com/<your-handle>/YieldQuest.git
cd YieldQuest
npm install
npm start

Smart contracts (via Hardhat):

npx hardhat compile
npx hardhat test

Roadmap

Core staking + quests deployed (testnet live)

NFT Quest badges (on-chain proof of completion)

Mainnet deployment (Kaia)

Multi-asset support


Contact
Founder: Ashikur Rahman
Telegram: @Ashikhowlader
GitHub: https://github.com/Ashikhowlader/YieldQuest/tree/main
