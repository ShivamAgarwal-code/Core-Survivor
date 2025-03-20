# Core Survivor Game: Battlegrounds

## Inspiration

I was once deeply engrossed in a popular game called Vampire Survivors, available on Steam. At one point, I was so addicted to it that I would play for at least half an hour, sometimes even several hours at a stretch. However, when I explored the web3 gaming space, I struggled to find anything similar or even remotely fun. Aside from Dark Forest, most web3 games I encountered were either bland airdrop schemes or overhyped projects. This led me to believe that people might only engage with web3 games to make money and then return to platforms like Steam after work. I firmly believe that only genuinely engaging web3 games can achieve widespread adoption, while those relying solely on token airdrops or "play-to-earn" models will struggle to sustain interest.

## What It Does

Core Survivor Game is a time-based survival game with minimalistic gameplay and roguelite elements. Built using ThirdWeb technology, it allows players to log in through various methods, including social accounts (Google, Apple, Facebook), email, phone numbers, passkeys, and over 350 web3 wallets. The game features a unique algorithm designed to optimize player engagement, keeping them in a constant state of tension and excitement. I developed a custom algorithm within the smart contract and implemented an on-chain leaderboard, which minimizes gas consumption without compromising sorting efficiency. Additionally, I introduced a lottery mechanism for players to draw cards and unlock rewards.

To explain the game's core values, I’ll borrow from the original Vampire Survivors concept: Monsters are everywhere, and there’s no escape. Your only goal is to survive as long as possible until death inevitably claims you. Collect gold during each run to purchase upgrades and aid the next survivor.

## How to Play

Loading Scene

Wait for the progress bar to complete, then select your preferred wallet or log in with a social account to start the game.

Home Scene

The homepage displays various game data, such as gold coins, diamonds, network status, wallet address, and more. You’ll also see game characters, weapons, and a scrolling background with a custom logo I designed for the Core Blockchain network.

The five buttons on the right serve different purposes: Home, Weapons, Characters, Lottery, and Onchain Rankings.

Click the Start Game button, pay 0.01 tCORE as a gas fee, and wait for the transaction to complete before entering the game.

The 0.01 tCORE fee acts as a ticket to participate, and this amount is distributed as rewards to top players on the leaderboard. (Maintaining a high ranking can earn you significant tCORE tokens.)

2.1 Weapon Page

Here, players can select, purchase, and upgrade weapons.

Gold coins can be earned through gameplay, purchases, or lottery draws.

Diamonds and advanced weapons are exclusively obtainable through the lottery, making it the easiest way to acquire high-tier gear.

2.2 Characters/Skins Page

Players can purchase and upgrade characters here.

I’ve designed numerous characters, but due to time constraints, only four are currently available.

2.3 Lottery Page

Players pay 0.04 tCORE to participate in the lottery, with chances to win gold coins, diamonds, or advanced weapons.

A VRF (Verifiable Random Function) ensures fairness and randomness in the draws.

If you’re eager to wield the Howitzer or Gatling, try your luck in the lottery!

2.4 Onchain Ranking Page

This page displays player rankings, including kills and survival times.

At the bottom, you can see the last update time for the leaderboard.

The leaderboard is scrollable and currently shows the top ten players.

## Game Scene

Once in the game, use the "W," "A," "S," and "D" keys to move your character up, down, left, and right. (These controls are displayed in the lower right corner of the screen.)

Your goal is to avoid monsters, use weapons to defeat them, collect experience points, and unlock new skills through upgrades.

Click the avatar in the top-left corner to view your character’s attributes.

The top of the screen shows your character’s level and active skills.

On the right, you’ll find two buttons: one for a bomb attack and another for a magnet that globally collects experience points. Each can only be used once per game!

The rest is up to you to explore! I’ve designed a unique algorithm for monster generation to keep players constantly engaged and on edge.

On the game settlement page, click the Submit button to broadcast your performance to the Core Blockchain network, allowing players worldwide to see your achievements!

## How We Built It

I completed this project in a short timeframe, juggling game design, art, mechanics, algorithms, smart contracts, and integration with the Core Blockchain network.

Logo and Art

I used Photoshop to create the game logo and most of the game assets.

Game Development

I designed the game UI in Photoshop and used Cocos as the game engine to implement mechanics, algorithms, and overall logic. A significant portion of the time was spent on art and gameplay implementation.

ThirdWeb Integration

ThirdWeb technology lowers the entry barrier for web2 players, allowing them to log in with social accounts, email, or phone numbers. It also supports web3 wallets like MetaMask.

Smart Contracts

Using Hardhat, I wrote smart contracts to store game data, including player assets, weapons, and skins, ensuring transparency and security. I also designed algorithms for the leaderboard and lottery system, ensuring fairness and on-chain functionality. The contracts were deployed to the Core Blockchain testnet, which offers fast and seamless performance.

Challenges We Faced

Due to limitations with the game engine, I couldn’t directly use ThirdWeb or Web3 SDKs. After a week of brainstorming, I created a React project to expose APIs to the game engine, enabling ThirdWeb functionality.

## Accomplishments We’re Proud Of

Completed most of the game logic within the tight deadline.

Designed algorithms to keep players immersed and excited.

Successfully deployed smart contracts to the Core Blockchain testnet, which provided an excellent user experience.

## What We Learned

How to use game engines to bring ideas to life.

How to write and deploy smart contracts using Hardhat.

How to integrate with the Core Blockchain testnet.

## What’s Next for Core Survivor Game

Design more engaging and visually appealing game UI.

Refine the reward mechanism to fairly distribute rewards to top players, boosting engagement.

Introduce generative AI to allow players to create their own weapons and character skins, adding randomness and creativity to the game.

Deploy the game on the Core Blockchain mainnet.