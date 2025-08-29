# 📝 Elevantu

## 🌟 Project Overview

![Logo_Spin-ezgif com-resize](https://github.com/user-attachments/assets/89bba8e4-af0b-4fd1-bd32-fe64c0fa0759)

**Tagline:** World First Web3-powered Habit Gym

**Brief Description:** 
Elevantu is a habit tracking platform designed to help individuals achieve goals through consistent real-world challenges. Users participate in **missions**, logging their daily progress which is verified by a group of user-chosen **nominees**. Upon nominee consensus, users are rewarded with a variable amount of '**Core**'—the native digital currency that powers the ecosystem. Users can also stake 'Core' on their mission completion, adding a tangible layer of personal accountability. This gamified system incentivizes long-term engagement; as users consistently complete habits and earn Core, they randomly unlock new functionality and exclusive rewards, providing a tiered reward experience that feels both exciting and valuable. Elevantu fosters genuine accountability and tangible self-improvement.

**Integration with Polkadot:**
Elevantu is not just built on Polkadot — it is architecturally and philosophically aligned with Polkadot. Polkadot enables us to:

✅ Fuel accountability with social pressure
✅ Interact across roll-ups as a commitment oracle 

✅ Evolve to match demand in real time
✅ Engage with users who value meaning over speculation

**Team Interest:**
My first ever web3 hackathon was with you guys two years ago, no-one wanted me on their team and I froze on stage but that started my journey. Since then I've competed in over 25 hackathons across three continents and over time I learnt how to present to 300+ people with ease and charisma. 

We are what we repeatedly do. Excellence, then, is not an act, but a habit.

This project is a direct result of solving a personal problem and so I’ve designed a gamified system designed to empower users to take control of their behaviour and create lasting change.


### 👨🏻‍🏫👨🏻‍🏫👨🏻‍🏫 Pitch and Presentation 👨🏻‍🏫👨🏻‍🏫👨🏻‍🏫

- You can watch my [one minute pitch](https://drive.google.com/file/d/1xN5rfBe8D34J3nxewlFyywLeTh818Z5d/view?usp=sharing)
- and here is my [presentation](https://www.canva.com/design/DAGl7EYWkKs/s0wobtrClDJ76Sg1r1Y5SQ/edit?utm_content=DAGl7EYWkKs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- Elevantu [website](www.elevantu.com)
- [TikTok](https://www.tiktok.com/@elevantu)

### 🔍 Project Details
 
**Technology Stack:**
- **Frontend**: Next.js/react 
- **Smart Contracts:** EVM-compatible contracts, Westend Asset Hub for challenge submission and NFT minting
- **Wallet integration:** Polkadot.js
- **Deployment:** Custom domain already purchased

**Main Components:**
- **Frontend Pages:** Landing Page, Mission Discovery Page, Group Page
- **Smart Contracts:** Mission Management, Habit & Verification, Core Token, Juice Betting, NFTs
- **Nominees & Verification:** 
- **Juice and Variable Ratio Reward Schedule:** 
  
1. **Frontend Pages:**
* **Landing Page** (All-in-One Hub): This will be the main hub a user lands on after logging in. It will combine the functions of the profile page, mission dashboard, open bets, and rewards page. This single page will show a user's progress, current streak, and all their open missions and bets.
* **Mission Discovery Page**: This page functions like Duolingo's course selection screen. It will be a visually organized list or grid of all available missions that a user can browse and select to participate in.
* **Group Page**: This will show a list of all the accountability groups a user is a part of. Tapping on a group will take the user to a more detailed group-specific view.

2. **Smart Contracts:**
* **Mission Management** This contract acts as the definitive registry and rulebook for all missions. Its primary responsibility is to define mission parameters and manage the full mission lifecycle.
     - **Create Mission**: Allows a new mission to be set up with its specific rules, duration, and reward structure.
     - **Join Mission**: Enables a user to officially join a mission and be added to the participant list.
     - **End Mission**: Finalizes a mission and triggers the reward distribution for all participants who successfully completed it.
       
* **Habit & Verification**: This is the main engine for accountability, responsible for recording daily progress and facilitating the nominee voting process
    - **Submit Proof**: Records a user's daily check-in as an immutable, on-chain record.
    - **Cast Vote**: Allows a nominee to cast their binding "pass" or "fail" vote on a user's submission.
    - **Check Consensus**: An internal function that determines if the required number of nominee votes has been reached to verify a user's progress.
      
* **Core Token**: This contract is the sole manager of the Core currency. It handles the entire token supply and is the definitive source of truth for all Core transactions.
    - **Mint**: Creates new Core tokens, primarily for rewarding users who successfully complete a habit.
    - **Burn**: Destroys Core tokens, typically when a user fails a mission they have placed a bet on.
      
* **Core Betting**: This contract is dedicated to the personal accountability layer, handling the staking and distribution of Core bets
    - **Place Bet**: Securely locks the two parties Core in the contract as a bet on a specific users' performance on a specific mission.
    - **Payout Winnings**: Upon successful mission completion, releases the staked Core to the winning party.
      
* **NFTs**: This contract handles the creation and management of all non-fungible assets, such as unique titles and collectible badges.
    - **Mint Collectible**: Creates a new, unique token (an NFT) for a user to represent a rare reward they've unlocked.
    - **Assign Ownership**: Records the ownership of the new NFT to the user's wallet

3. **Nominees & Verification:**

Elevantu's core accountability engine is a human-driven system that leverages social pressure and verifiable on-chain consensus. The process works as follows:

* **Human-Driven Accountability**: The system is powered by a small, trusted circle of nominees, selected by the user to provide personal accountability.

* **User-Controlled Media**: To ensure a lightweight and user-centric system, users retain full control of their media by storing their progress proof (e.g., a photo or video) on their own personal drives or cloud storage. Only a secure link is submitted for verification

* **Consensus for Completion**: Nominees review the proof and cast their votes on-chain. An immutable record of completion is created only when consensus is reached among the group.

Bet Finalization: The outcome of any Core bets is directly determined by the accumulated consensus reached by the group.

This reliance on human consensus and trusted social dynamics makes the system powerful for driving long-term behavioral change, creating an on-chain record that represents a genuine, peer-validated commitment.
  
5. **Core and Variable Ratio Reward Schedule:**
   
* **The Core Token**: A Quantified Commitment


The Core token is the native digital currency of the Elevantu ecosystem. Its primary purpose is not speculative but rather to serve as a quantified representation of a user's commitment and effort over time. 

* **Reward Utility**: Core is the core reward for long-term consistency. Users earn a variable amount of Core upon the successful completion and verification of their daily habits, which incentivizes repeated engagement.

* **Mission Participation**: Users buy into mission participation using Core, and are rewarded back in Core proportionally to their commitment after minimum commitment quotas are achieved. If they successfully complete the mission, their Core is returned perhaps in surplus. If they fail, the user forfeits the Core, reinforcing the cost of a lack of commitment.

* **Access & Unlocking**: Core acts as the key to unlocking the platform's features. As users accumulate Core, they randomly unlock new functionality, exclusive mission templates, and unique collectibles.

**Mock-Up:**
This is only a quick chatgpt mockup based on the pages required on the dapp.
![ChatGPT Image Apr 26, 2025, 09_11_32 PM](https://github.com/user-attachments/assets/8944ec26-4dbe-4c0a-ae30-519efd99fdc5)

### 🧩 Ecosystem Fit

**Where and how does your project fit into the ecosystem?**

Long term I see the ecosystem using this predominantly for skill development and community social missions but also as consideration for hiring purposes and creating events with curated event participants. This is a novel intersection between gaming and self-improvement, which so far I've only seen vaguely exploited in web2. The usage of tokens and verifiable actions redefines what rewards and incentive strength the application can have.
  

**Who is your target audience?**
The self-teaching unemployed who are improving their craft everyday without any incentive structures around them would be my ideal customer base because with the app they can simultaneously improve their skill and become more attractive to the job market at the same time. 
* Unemployed who need to improve skills and demonstrate commitment
* Individuals willing to invest in measurable personal growth
* Polkadot community members interested in verifiable achievements

**What needs does your project meet? Why are there no competitors**
We meet three unmet needs:
1) Reputation and Accountability in self-improvement: It provides a tangible, verifiable system of accountability. By using on-chain records and a "nominee" verification process, the application ensures that a user's progress and commitment are transparent and immutable, which is more powerful than simple self-reporting.

2) Motivation & Incentives: The application is geared towards maintaining long-term motivation. It uses a gamified system of rewards, including a native token, on-chain NFTs and prizes, to provide continuous incentive for consistency and habit-building.

3) Meaningful Rewards: Rather than just earning digital points, users receive a meaningful, verifiable representation of their effort. Elevantu transforms abstract concepts like consistency into tangible assets. The most challenging missions even offer physical prizes, adding another layer of reward. 

There are currently no direct competitors because the combination of elements we're bringing together - skill building challenges powered by Web3 — doesn’t exist in this specific form yet. While there are platforms for self-improvement and personal development, none have successfully leveraged blockchain to create an incentivized ecosystem with the focus on real-world challenges that Elevantu offers.

## 👥 Team

- **Team Name:** Elevantu Ltd
- **Contact Name:** Agustin Schiariti
- **Contact Email:** agustin@elevantu.com
- **Website:** www.elevantu.com

### Team members

Agustin Schiariti

#### Social Media Profiles

- https://www.linkedin.com/AgustinSchiariti
- https://x.com/The_Game_2030

### Team's experience

* Self-Taught FPV drone pilot - Ran a luxury marketing company for two years.
* Competed in over 25 hackathons, over 15 wins, 10k+ earned
    * EthGlobal Cannes - 1st Place Avail
    * SmartCon Barcelona – Double 1st place Chainlink
    * EthGlobal NYC – 2nd Place Lit Protocol
    * EthGlobal Paris – 2nd Place ZetaChain Bounty
    
  
## 📊 Development Status

The foundation of this project emerged from extensive real-world testing of rejection therapy challenges as a means to rapidly build entrepreneurial confidence. Originally derived from vocal warm-up exercises before hackathon pitches and startup presentations, these challenges evolved into a structured, repeatable procedure for reducing social anxiety, improving communication skills and enlarge ones comfort zone, Quickly. 

Realising the system of repeatable actions can be applied to any skill gave birth to the idea of supporting people to achieve their skill development goals with the same techniques the gaming industry uses to improve consistency.

Over the past year, I’ve documented and refined these challenges through consistent content creation—recording video demonstrations, sharing guides to my close friends, and sharing insights with entrepreneurial communities. Personally I have been documenting in public the completion of 4 habits everyday for the past 3 weeks. Observing friction points and theorising where and how users can be supported through their own journeys. This has heavily influenced the mechanism design.

## 📅 Development Roadmap

### Overview

- **Estimated Duration:** Three months
- **Full-Time Equivalent (FTE):**  One
- **Total Costs:** $7790

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can log in and set up mission participation|
| 0c. | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Article | We will publish an **article** that explains what was done/achieved as part of the grant.|
| 1a. | Frontend Structure | Landing Page, Mission Discovery Page, Group Page. Basic skeleton layout will be the priority at this stage |
| 1b. | Wallet login integration | Wallet login integration, for grant development timeline will be Polkadot.js|
| 2a. | Smart Contract: Core Token Minting & Decay Mechanism | Handles the creation and management of the ecosystem's core token supply. |
| 2b. | Smart Contract: Mission Lifecycle Management | Manages the full lifecycle of a mission, from creation and start to completion and finalization. |
| 2c. | Smart Contract: Verification and Nominee Module | Facilitates the on-chain verification of mission progress through a decentralized nominee consensus system |
| 2d. | Smart Contract: Core Token based P2P Betting Engine | Enables users to engage in peer-to-peer betting on their mission outcomes using the core token |
| 2e. | Smart Contract: NFT Streak Rewards Contract| Distributes unique, on-chain NFT rewards to users for completing consistent challenge streaks |
| 3. | Bespoke Mission Templates| Designing the first missions designed for early testers|
| 4. | Updating user guide | Instructional guide for new users so onboarding is smooth |
| 5. | UI/UX polish  | This is where the perception of the frontend will be prioritised with animations or media being included. |
| 6. | Error Handling/Bug fixing | fix as many bugs as possible |
| 7. | Comprehensive testing  | unit/manual for functions |
| 8. | Deployment at purchased domain | Deployment at purchased domain |

### 💰 Budget Breakdown

Please provide a breakdown of your budget by milestone:

| Milestone 1| Deliverable| Title  | Hours | Rate/hr | Cost (USD) | 
| --- | --- | --- | --- |--- |--- |
| 1 |1a| Frontend Structure & UI Framework Setup |30|25|750| 
| 1 |1b| Wallet Login (DOT Asset Hub)|3|30|90| 
| 1 |2a| Smart Contract: Core Token Minting & Decay Mechanism|28|30|840| 
| 1 |2b| Smart Contract: Mission Lifecycle Management|28|30|840| 
| 1 |0c| Testing & Test Guide |10|30|300| 
| 1 |0a| License|0|0|0| 
| 1 |0b| Documentation|7|20|140| 
| **M1 Total** | **7 deliverables**|**Core Infrastructure**|**106**  |--- |**2960**|

| Milestone 2| Deliverable| Title  | Hours | Rate/hr | Cost (USD) | 
| --- | --- | --- | --- |--- |--- |
| 2 |2d| Core Token based P2P Betting Engine | 28 | 30 | 840 | 
| 2 |2c| Verification and Nominee Module | 28 | 30 | 840 | 
| 2 |2e| NFT Streak Rewards Contract | 16 | 30 | 480 | 
| 2 |3| Bespoke Mission Templates | 12 | 25 | 300 | 
| 2 |0c| Testing & Test Guide | 10 | 30 | 300 | 
| 2 |0b| Documentation| 7 | 20 | 140 | 
| **M2 Total** |**6 deliverables**|**Functional Core**|**101**|--- | **2900** |

| Milestone 3| Deliverable| Title  | Hours | Rate/hr | Cost (USD) | 
| --- | --- | --- | --- |--- |--- |
| 3 | 5 | UI/UX polish | 20 | 25 | 500 |
| 3 | 6 | Error Handling/Bug fixing | 10 | 30 | 300 |
| 3 | 7 | Comprehensive testing | 8 | 30 | 240 |
| 3 | 8 | Deployment & Setup on Domain | 8 | 25 | 200 |
| 3 | 4 | Updating user guide | 6 | 25 | 150 |
| 3 | 0c | Testing & Test Guide | 10 | 30 | 300 |
| 3 | 0b | Documentation | 7 | 20 | 140 |
| 3 | 0d | Article | 5 | 20 | 100 |
| **M3 Total** |**8 deliverables**|**Polish & Testing**|**74** |--- | **1930** |

| **Final Total** | **21 deliverables** | **281 hours** | **$7790** |

## 🔮 Mechanism Design

This system is designed to maximize user engagement, fairness, and retention while maintaining predictable unit economics.  
It replaces traditional high-stake monetary penalties with a **decaying in-game currency** (“Juice”), creating an intrinsic urgency to participate without introducing excessive financial risk.

### 1. Juice as a Decaying Asset
- **Minting & Purchase:** Users acquire Juice through an upfront purchase or by earning it via habit completion.
- **Decay Function:** Juice loses value over time if unused, encouraging continuous participation in missions rather than hoarding.
- **Monetary Risk Control:** Because Juice is purchased in small increments and cannot be redeemed for cash, users face minimal direct monetary loss while still valuing it due to its functional utility in the ecosystem.

---

### 2. Mission Entry & Proposed Reward Structure
Missions are time-bound challenges with an upfront Juice entry cost. Rewards scale with performance:

| Completion Rate | Reward Payout (Juice) | Description |
|-----------------|-----------------------|-------------|
| 75%+            | 50% of entry cost     | Maintains partial value, softens loss aversion |
| 85%+            | 100% reimbursement    | Risk-free participation for solid performance |
| 100% (Easy)     | 110% reimbursement    | Small surplus for perfect performance |
| 100% (Medium)   | 150% reimbursement    | Moderate surplus for perfect performance |
| 100% (Hard)     | 300% reimbursement    | Large surplus, creating aspirational “jackpot” missions |

This tiered system:
- Rewards consistent effort (partial reimbursement tiers).
- Encourages perfectionism in higher-stakes missions.
- Keeps non-perfect completion attractive enough to maintain engagement.

*Note:* The reward payout schedule is subject to change depending on effectiveness.
---

### 3. P2P Betting on Performance
Beyond mission rewards, users can **wager Juice directly against peers** on the likelihood of their completion percentages.  
This mechanic is highly engaging because:
- It adds **skin-in-the-game** without requiring fiat money.
- Betting outcomes are **settled automatically** via smart contracts, preventing disputes.
- Users can offset potential Juice decay by winning bets.
- It creates **social pressure and visibility**, amplifying accountability within groups.

Example:  
Two friends both enter a 7-day mission. Each bets 20 Juice that they’ll outperform the other in % completion. The winner not only gains bragging rights but also their opponent’s Juice — which can be reinvested into new missions.

---

### 4. Why This Design Works
- **Urgency without Punishment:** Decay encourages action without the resentment caused by losing large cash stakes.
- **Short Feedback Loops:** High-cost, short-duration missions provide fast results, keeping users hooked.
- **Predictable Economics:** Juice sales fund all prizes, ensuring sustainability.
- **Intrinsic + Extrinsic Motivation:** Users are motivated both by personal progress and the competitive thrill of outperforming others.
- **Scalable Reward Sourcing:** Non-monetary prizes (gear, books, subscriptions) can be acquired cost-effectively at scale, stretching each Juice payout.

---

### 5. Expected Behavioral Dynamics
- **Habit reinforcement:** Low-barrier missions encourage onboarding, while “jackpot” missions incentivize mastery.
- **Increased retention:** P2P betting adds replay value and personal stakes.
- **Positive-sum perception:** Even in failure, partial reimbursements reduce churn.
- **Community formation:** Groups evolve into micro-economies where Juice circulates through missions and bets.

## 🔮 Future Plans

* Personally continue performing rejection therapy challenges and grow my comfort zone extensively
* Organically growing a social media presence will take minimum 6 months of regular posting I suspect, will use repurpose.io to automate posting across all socials with a post schedule. 
* Onboard people I meet at hackathons, conferences and hostels
* Commence 1-1 consultations and build mentoring expertise 
* Hold Bootcamps where I physically accompany students with their challenges
* Either integrate further into polkadot as a confidence layer where the streak NFTs signify special access/perks OR expand vertically with pitching/raising capital specific exercises/bootcamps. This will depend on the user feedback through the first 6 months of development.
* I want this to affect the creators of the protocols and roll-ups on polkadot, if I can help improve the communication ability of web3 leaders then that has a disproportionate influence on the industry as a whole.


