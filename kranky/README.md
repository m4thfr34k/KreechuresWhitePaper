---
description: Krank around and find out
---

# ⚙️ Kranky

* Tired - Giveaways
* Expired - Raffles
* Wired - KAFO, URL [here](https://kranky.kreechures.com/)

\_\_\_

Kranky is a game you can win based on your attention and patience.&#x20;

Today's options:

* Giveaways - ginormous number of random accounts, bots, come out of nowhere to spoil the fun & contribute nothing
* Raffles - like the lottery. Thinking about winning is the fun ... not the actual raffle
* Auctions - boring until the end

It's time for something better.

### Concept

Pretty simple rules. You've got some prizes and a timer.

* Every Krank has a time buffer, an NFT prize, and a bonus
* The last person to push the krank while there is still time wins the NFT
* The first person to push the krank after time expires wins the bonus
* For every push of the krank, a small amount of time is added to the time buffer and a small amount of $SOL is added to the Krank bonus

Winning an NFT for 0.006 SOL, cost of a single Krank, sounds pretty cool.

There's no limit to how big the Krank bonus can get. Winning that Krank bonus for 0.006 SOL sounds pretty damn cool too lol

### Time buffer

At the very beginning, 5-seconds is added to the time buffer for every krank with a maximum time buffer of 5-minutes.

* After 60 clicks, 4-seconds is added per Krank
* After 120 clicks, 3-seconds is added
* After 180 clicks, 2-seconds is added
* After 240 clicks, 1-second is added

If a Krank lives long enough, the krank bonus could be worth more than the NFT prize.

It will be interesting to see if players change their strategy once the flippening happens.

### Krank creators

A portion of every Krank, 0.002 SOL every time a user pushes the Krank button, is reserved for the Krank creator.&#x20;

This is the same amount that goes into the Krank bonus. The final 0.002 is reserved for Kreechures.

A Krank creator can look at the Krank bonus to see how much they will receive once the Krank ends.&#x20;

Krank cost will be configurable in the future.&#x20;

The Krank creator is set as the default for the initial krank. What this means is, if no other player pushes the krank button then the NFT can be claimed by the creator after the time expires. If a single other player pushes the krank button then "the game is on".

It costs 0.1 SOL to create a new Krank.

### Final thoughts

Creating a Krank is better than running the typical giveaway, raffle, or auction.

Giveaways attract an enormous number of pro giveaway players with account and bot farms that take advantage of your events and your community. Raffles and auctions are pretty krankin' boring until the very end.

Creating a Krank gives your community a real opportunity to win without having to battle account and bot farms and keeps the excitement going throughout.

What community will create the most kranks for an item? How long will the longest krank live? It's going to be fun finding out.

### Tech stuff

All of this is managed via an on-chain Solana program, Kranky, and the corresponding front-end to interact with the program.

Kranky program address: 8dHvqkRQbh1FBo9Ez2QkJ2LoWa3616j5zUHKjECXGFpM

The IDL for the program is on-chain

The program manages the escrow of the NFT and bonuses in addition to tracking all kranks.

#### Tools

* Blockchain - Solana - [https://docs.solana.com/developing/intro/programs](https://docs.solana.com/developing/intro/programs)
* Seahorse - [https://seahorse-lang.org/](https://seahorse-lang.org/)
* RPC - [https://www.helius.dev/](https://www.helius.dev/)
* Front-end - Next.js - [https://nextjs.org/](https://nextjs.org/)
