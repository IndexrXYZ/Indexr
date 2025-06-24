# 📜 CHANGELOG

All notable changes to Indexr will be documented here.
---

## [June 24, 2025]
- Replaced all mock data in `useUserPortfolio` with **live on-chain fund balances**
- Added cash balance support and **percentage breakdown** logic
- Connected portfolio view to pie chart component with dynamic token weights
- Fully implemented `SellModal`:
  - Now submits real `withdraw()` transactions
  - Shows success/failure toasts and loading states
- Final frontend polish:
  - Transaction feedback system across all modals
  - Improved balance validation and error handling
- **Indexr MVP now fully functional on Arbitrum Sepolia**

---

## [June 23, 2025]
- Built Supabase table: `recurring_investments` with full schema, RLS, and indexes
- Created `create-recurring-intent` edge function for EchoPay + Stripe integration
- Set up test Stripe keys and webhook scaffolding
- Added **frontend form support** for recurring investments (email, frequency, amount, fund, wallet)
- Connected form to Supabase + Stripe for one-click recurring setup

---
## [June 22, 2025]
- Finalized **USDC token contract integration** on Arbitrum Sepolia
- Implemented proper **allowance checks** and **auto-approval** logic before USDC deposits
- Cleaned up currency selector in the investment modal
- Rewrote Bridge.xyz links to dynamically inject connected wallet address
- Standardized “Powered by” text across all investment methods

---

## [June 21, 2025]
- Integrated initial smart contract functions: `depositETH`, `withdraw`, and `approve`
- Refactored `INDEX_FUND_ABI` to support ETH deposits and USDC approval flow
- Connected `SellModal` scaffold to new withdraw() logic in preparation for real selling
- Verified `Thirdweb` config with working client ID setup

---

## [June 16, 2025]
- Complete overhaul of the Indexr website UX and UI
- Fund cards redesigned with smoother pie chart animations
- Improved fund categorization and filtering (Classic, Thematic, Specialty)
- Refined and restructured all page copy (Hero, About, Legal, Pricing, etc.)
- Legal disclaimers added (Beta, Non-Financial Advice, Geographic Restrictions)
- "Get Early Access" waitlist flow implemented via Supabase
- Beta dashboard gated behind wallet connection and access approval
- Integrated ThirdWeb for wallet connection and dashboard auth
- Testnet dashboard deployed with real-time rebalancing + fund stats
- Set up Supabase email onboarding + connected contact form
- Enhanced scroll-based animations for smoother first user experience
- Prepared updated infographics and screenshots for public content rollout

---

## [April 10, 2025]
- Implementing the code changes I wanted to make to Indexr's fund offerings, planning to manually update the backend code this evening with the changes

---

## [April 9, 2025]
- Tightened the branding, repurposed the logo and cover banner for X, Notion, Linkedin accounts to improve how the brand looks to new users at first glance.

---

## [April 1, 2025]
- Social channels updated with build-in-public threads

---

## [March 31, 2025]
- MVP deployed to Arbitrum Sepolia Testnet
- TWAP logic + Chainlink integration confirmed working

---

## [March 23, 2025]
- Indexr Web3 Portfolio now linked via Google Drive

---

## [March 22, 2025]
- Finalized Core Smart Contract v5 with TWAP + slippage controls
- Backend fully integrated with fund creation + price feeds
- All components hardened for testnet

---

## [March 20, 2025]
- Added GitHub Action for weekly heartbeat commits
- Fixed nested folder structure in repo
- Created public `README.md` with clear project breakdown

---

## [March 15, 2025]
- Finalized MVP version of Indexr Smart Contract
- Simplified rebalancing logic
- Started work on frontend integration
