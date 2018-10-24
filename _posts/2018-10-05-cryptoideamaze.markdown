---
layout: post
title:  "Enter the Crypto Idea Maze"
permalink: /cryptoideamaze/
date:   2018-10-11
image: /maze.jpg
description: "It's early in the game for crypto, and an idea maze helps us dig deeper and discern between compelling adoption paths and dead ends."
categories: crypto
---

**tl;dr**  It's early in the game for crypto, and an idea maze helps us dig deeper and discern between compelling adoption paths and dead ends.  Bitcoin then Ethereum catalyzed excitement for "crypto" broadly, and the industry is debating the merits of "sound money," "web3" and "open finance."  While each share the same ethos of disintermediation, they require different features to succeed and are competing against different alternatives.  Inheriting not only the ethos of decentralization but also the technical tradeoffs of its predecessors has resulted in an underlying cognitive dissonance.  The way to resolve the dissonance is to forget the familiar narratives, and instead to examine: the novel features of the technology, who the core customers are, who is failing to serve them now and why there can be a compelling new product today.  Let's enter the crypto idea maze.

<br/>

![alt text][maze-image]

[maze-image]: http://www.stanstedpark.co.uk/public/images/Grounds/Maze_from_above.jpg

<br/>

#### Table of Contents
1. The Idea Maze
2. Before the Maze: Bitcoin then Smart Contracts
3. Enter the Maze: The Three Theses
4. Cognitive Dissonance
5. The Way Out: Customers, Alternatives and Intermediate Utility
6. Waiting for Catalysts: How Badly Do They Need You?
7. The Timing of It All
8. Assessing What's Next
    1. Sound Money: In Code We Trust
    2. Web3: UX vs Trust
    3. Open Finance: Bearer vs Registered Instruments
9. Exploring Assumptions and Rebuttals
10. How Can We Contribute Today?
11. Right Values + Uncertainty = Opportunity

<br/>

### The Idea Maze

The [idea maze](http://cdixon.org/2013/08/04/the-idea-maze/) metaphor stems from the fact that a technology trend has various adoption paths that lead to varying levels of success (h/t Balaji Srinivasan & Chris Dixon).

> Good startup ideas are well developed, multi-year plans that contemplate many possible paths according to how the world changes.

**In an exuberant time, it's often tempting to run straight for the entrance to take the lead, but chances of success will be much greater for teams that have a rough map that guides them.** Being a student of the technology, its history as well as learnings from other mazes will help us map out the maze.  It will give teams more clarity in pursuing or avoiding certain target customers, product features, and to market strategies.

> A good founder is capable of anticipating which turns lead to treasure and which lead to certain death. A bad founder is just running to the entrance of (say) the “movies/music/filesharing/P2P” maze or the “photosharing” maze without any sense for the history of the industry, the players in the maze, the casualties of the past, and the technologies that are likely to move walls and change assumptions.

For example, a sports fan and an experienced coach are both watching a game and see the same inputs, but they notice vastly different levels of detail.  While a sports fan can be excited about what's happening, the good coach can see how to navigate the opposing team, how certain changes of the roster or formation could be effective, and reliably affect the course of the game.  Technology and adoption seem no different.

This feels especially salient for crypto because it is multidisciplinary and requires cooperation among many stakeholders across industries and geographies.  Also, mapping the idea maze seems especially more important early in the lifecycle of a platform (*e.g.* web, social media, mobile).  Because vision and ethos are currently leading ahead of adoption, it is not clear from this vantage point which approaches are headed towards a market with strong demand and sustainable economics vs a dead end (*i.e.* early).

With that, I'd like to share the beginnings of my crypto idea maze (open source all the things!).  We will focus on challenges in reconciling core assumptions of various crypto theses, and we will save specific adoption paths (go to market + geo) and deep-dives on applications for another time.  **As such, this is not the "full maze," but I hope you'll reach out to continue constructing the maze together.**

<br/>

### Before the Maze: Bitcoin then Smart Contracts

#### In the beginning**, there was Bitcoin.

The *initial intent* for Bitcoin is very clear.

> A purely peer-to-peer version of electronic cash would allow online payments to be sent directly from one party to another without going through a financial institution.

It was an experiment in creating a payment network that removed the need for mediation, in order to (1) reduce the fees of digital commerce and (2) remove the need for sharing more identity information than required.

> Completely non-reversible transactions are not really possible, since financial institutions cannot avoid mediating disputes. The cost of mediation increases transaction costs, limiting the minimum practical transaction size and cutting off the possibility for small casual transactions, and there is a broader cost in the loss of ability to make non-reversible payments for non-reversible services. **With the possibility of reversal, the need for trust spreads**. Merchants must be wary of their customers, hassling them for more information than they would otherwise need. A certain percentage of fraud is accepted as unavoidable. These costs and payment uncertainties can be avoided in person by using physical currency, but no mechanism exists to make payments over a communications channel without a trusted party.

Bitcoin was created to provide a way to transact without identity or a trusted intermediary.  It began as the currency of choice for technologists & hackers, libertarians, black market users, cross-border remittances, and the oppressed (*i.e.* Venezuela).  This was especially timely given the government bail out of banks that took on excess risk.

Prominent features that came from having no trusted intermediary were censorship resistance (very expensive to change or stop a transaction) and immutable monetary policy (can't "print" more resources unilaterally).  In order to do so, it uses a peer-to-peer architecture and a novel economic incentive mechanism (proof of work).

It is important to note that **the innovation explicitly traded off efficiency** in order to provide censorship resistance and flexible membership set of participants (anyone can join or leave the network at any time).  We will come back to this, but in the meanwhile something else captured the attention of the community.

*** To be fair, Bitcoin was preceded by Digicash (Chaum 1989) and Bit Gold (Szabo 1998).*

<br/>

#### Then there were smart contract platforms.

> A smart contract is a computerized transaction protocol that executes the terms of a contract. The general objectives of smart contract design are to satisfy common contractual conditions (such as payment terms, liens, confidentiality, and even enforcement), minimize exceptions both malicious and accidental, and minimize the need for trusted intermediaries. Related economic goals include lowering fraud loss, arbitration and enforcement costs, and other transaction costs.

The idea of smart contracts have been around for quite some time ([coined and popularized by Nick Szabo in 1994](http://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/smart.contracts.html), quoted above), and the demand to implement smart contract capability had a resurgence through the Bitcoin community ([RSK](https://www.rsk.co/), [Colored Coins](https://en.bitcoin.it/wiki/Colored_Coins), [Mastercoin](https://blog.omni.foundation/2013/11/29/a-brief-history-of-mastercoin/)). [One person working on Mastercoin was Vitalik Buterin](https://vitalik.ca/general/2017/09/14/prehistory.html), who thought the idea of extending the Bitcoin protocol was exciting yet a limited implementation of the full potential of smart contracts.  His ideas diverged enough from the priorities of the Mastercoin team that it wasn't being implemented in Mastercoin, and [Ethereum was born](https://web.archive.org/web/20131219030753/http://vitalik.ca/ethereum.html).

While Bitcoin achieved consensus over the state of a transaction ledger (*i.e.* accounting), this branch of the movement began experimenting with consensus on the state of a computer replicated in a distributed network around the world (*i.e.* distributed virtual machine).

It's worth noting that, while cloud computing focused on getting distributed computers to do things quickly and efficiently to serve demanding applications within a trusted setting (*i.e.* datacenter controlled by one party), decentralized computing focuses on allowing computers that don't necessarily trust each other to agree on a shared state of a computer.  While adding computers to a cloud infrastructure makes the network more computationally productive (in varying degrees depending on technical architecture), decentralized infrastructure is instead optimized to maintain a certain level of "trustlessness" (or threshold for bad actors).  Therefore, adding computers to a decentralized network–while adding complexity–doesn't add much, if any, computational throughput of the network.

Despite those limitations, Ethereum was attractive for many reasons but in particular: (1) it was now very easy to create and deploy uncensorable smart contracts into production (the awareness around Bitcoin mining certainly was an added catalyst for building a lively early mining community) and (2) people could now imagine, "if it's possible to transact without intermediaries, what other interactions could we also manage without intermediaries?"  The simple analogy evolved from a digital "vending machine" that is owned by one party (and could thus be taken down, *i.e.* Paypal) to one that is not owned by anyone, is unstoppable and still accessible to anyone in the world with an Internet connection.

As Bitcoin was timely for the zeitgeist of the financial crisis, Ethereum was timely for consumers losing trust in various intermediaries, namely banks ([1](https://money.cnn.com/2016/09/08/investing/wells-fargo-created-phony-accounts-bank-fees/index.html), [2](https://www.usatoday.com/story/money/2016/06/23/bank-america-pay-430m-settlements/86284438/)) and Internet giants ([1](https://www.nbcnews.com/business/consumer/trust-facebook-has-dropped-51-percent-cambridge-analytica-scandal-n867011), [2](https://www.wired.com/2015/02/why-im-saying-goodbye-to-apple-google-and-microsoft/)).  This distributed computer concept generated excitement because the architecture has deep implications on possibilities to rearchitect those trust-required intermediary industries.  Some representative early ideas/examples were decentralized Uber and Airbnb ("web3") as well as decentralized platforms for lending, derivatives and startup investing ("open finance").

We now have experiments that replace the simple transaction ledger in Bitcoin with various forms of distributed computation (*e.g.* Ethereum, EOS, Dfinity, Tezos, Stellar).  This sets the stage for the Crypto Idea Maze (2018 vintage).

<br/>

### Enter the Maze: The Three Theses

We are in a fascinating part of the crypto idea maze in 2018; we have the proliferation of smart contract platforms, excitement around web3 & open finance, and the Bitcoin & privacy coin communities coalescing around the sound money narrative.

So what are the crypto theses?

**Sound money** – "Trustless money" that cannot be inflated by any trusted authority such as a central bank.

**Web3** – "Trustless internet" where Internet architecture is free of trusted centralized data & service monopolies.  Users have more control over their data and Internet usage.  These networks also compensate participants for economic value generated in the network.

**Open finance** – "Trustless financial systems" that extend cryptocurrency to provide open software primitives for equities, debt, derivatives, checking accounts, remittances, work contracts, retirement accounts, property *etc*.

*(Open to feedback).*

As such, the term "crypto" means different things to different people, and yet we all refer to this one word as a catchall (sorry, cryptographers! :\ ).  This has been a boon for a budding interdisciplinary community but also much miscommunication among [blind men describing an elephant](https://en.wikipedia.org/wiki/Blind_men_and_an_elephant).

While they all share the same ethos of disintermediation (respectively of government banks, big Internet giants, and commercial banks/fintechs), we will find that there is significant cognitive dissonance in having a shared set of technical tradeoffs across implementing disparate theses with different needs.

<br/>

### Cognitive Dissonance

> *Cognitive dissonance* – The state of having inconsistent thoughts, beliefs, or attitudes.

Over time, many have come to realize that it is not easy to reconcile winning forms of sound money, web3 and open finance under one technology. This is likely due to divergent underlying assumptions of the theses.

**Problem:** Adding a feature on top of a platform optimized to remove said feature.

**Cause:** Inheriting tradeoffs designed for another need.

Specifically, **we are building identity and "censorship abilities" on top of a platform optimized for not having identity and censorship**.  The potential problem here is: intuitively, that's far from resembling the most efficient architecture (this is an uncontroversial statement, even to core devs of these technologies).

At a more fundamental level, this dissonance exists because many smart contract public blockchains inherit tradeoffs made by Bitcoin: the network architecture, replication scheme, incentive mechanisms.  Those tradeoffs absorbed many orders of magnitude of replication inefficiency and "SLAs" (*e.g.* throughput, availability, predictable pricing) to make it difficult to (1) not require identity and (2) remove the need for a central entity that can censor.

Now the question becomes why should things with disparate user end goals (*i.e.* web3 / open finance) share the infrastructure tradeoffs of another product need (*i.e.* sound money).  There still may be compelling reasons why (as even one change in assumption can quickly change the outcome), but it's definitely not a gimme.

<br/>

#### A Means to an End

For the use case of money, those were excellent new features.  No one can change the rules of the game on you, doesn't matter who you are, where you are, the value you have won't be diluted by unforeseen increase in money supply, is unstoppable by a single party and doesn't require to know who you are.

**However those features are not inherently valuable; they are valuable due to serving a specific user need.** In fact, those features are good or bad depending on what service one is trying to provide.  For example, the downside of introducing identity is discrimination, but the upside is reputation.  Analogously, the downside of having central entity is censorship/liability, but the upside is quality service and convenience.

While the various theses share technological primitives and ethos of disintermediation, we will explore what this means in the context of the diverging needs of their end users.  This is the crux of the maze today.

<br/>

### The Way Out: Customers, Alternatives and Intermediate Utility

As such, there's never been a higher premium for the ability to think independently.  We ingest narrative after narrative on a daily basis on Twitter, and conflicting assumption sets of these narratives are exactly what made this maze more complicated (be skeptical of this post too!).  The only way out of the maze is to think independently about the customer need and what features those needs will demand.

We will discuss in more detail in the section below, but let's first take a look at the criteria in the rubric.

<br/>*Customer-centric compass*

Who is the customer and the stakeholders in their experience?

1. Customer
- Who is the core customer? (define personas / markets)
- What % of the world is affected?
- What is the level of "pain" per person affected?
- How do people join the network and why do they stay in the network?

2. Customer's counterparty
- Is it a one-to-one?  Is it one-to-many?
- Does the counterparty need to have the same product need as the primary customer?

3. Trusted intermediary
- Who do you depend on to enforce the rules?  Who could rule against you?

<br/>*"Atomic unit of success"*

For an ambiguous and multi-faceted product like crypto, it's important to explicitly define the fundamental metric for customer satisfaction.  For Google, it's a completed search.  For Uber, it's a completed ride.  For owning a share of Apple, it might be return on equity and earnings per share.

But for USD, what is it?  For crypto networks, what is it?  We will discuss below.

<br/>*Next best alternative*

Ethos-agnostic customers (aka "most people") will be driven largely by **a new feature's benefit over its next best alternative**.

For example, web search provided a convenient and fast alternative to seeking information from distant places. Google search provided a simpler and faster Internet search experience than Alta Vista, which was powerful and customizable but slower (perhaps optimized for the wrong feature given the early average user).  An early version of Uber provided a convenient way to call a black car to a location other than your usual office and travel in style.  Uber pool now provides an alternative to driving day-to-day or taking the bus/subway (in SF).

The tangible advantage over the next best alternative in serving a user need is exactly the forward momentum a product needs to improve and expand into adjacent services.

<br/>*Intermediate Utility*

Intermediate utility refers to the usefulness of a network before it is sufficiently saturated ("if it takes over just 5% of a target market, do those 5% of users still derive utility in the meanwhile?").

Two things help the creation of a network at an early stage: (1) the discovery of active peers despite small network size and (2) how compelling those experiences are before the network fully matures.  Those are crucial factors in the "intermediate utility" of an early network.  Early adoption paths with intermediate utility are often the only ways to achieve a desired end state.  Contrapositive: certain desired end states are impossible/expensive to achieve because it's difficult to have intermediate utility to bootstrap the network.

What is an example of intermediate utility?  For example, Facebook was fun to use when I was in school (to communicate, signal and stalk within the school setting).  I didn't use it too heavily but enough to keep me engaged.  That continued engagement of its early users for the early use case allowed Facebook to have a chance to further serve those users as well as expand into new markets.  If we had to wait years (or even just months) to get that initial usefulness, we never would have given it a shot–making more successful end states out of reach.

So the fact that small portions of the broader target network can get utility from the early iterations of the technology is a huge benefit, allowing it to sustain intermediate size of networks without having to reflexively and virally grow all at once (check out [Tony Sheng's recent post](https://www.tonysheng.com/price-flywheel) on reflexivity in crypto).  

Intermediate utility serves as a "checkpoint" for the network to "save progress" as it grows.
 More broadly, a series of step-function gains in intermediate utility will ultimately set the stage for main stream adoption / "crossing the chasm."

<br/>

### Waiting for Catalysts: How Badly Do They Need You?

While the theses are justifiably motivated by ethos, customer need and external catalysts will be the largest drivers of how this idea maze unfolds.  Let's see how the criteria above map to the three crypto sub-theses.

<br/>

#### Sound money

- **Value Proposition**:  Money that can be used to buy goods and store value, unaffected (and unprotected) by idiosyncratic government policy.  For example, shields user from incremental monetary easing, poor economic policy, corruption, and any other sovereign risk (issuer risk).
- **Core Innovation**:  "Internet money" in general made it possible to be unbound by physical realms (Digicash and Paypal still had this property, but had centralized settlement).  Proof of work distributed that settlement layer, making it unstoppable by any one jurisdiction.
- **Core Customer**:  People that don't have access to stable store of value (e.g. Venezuela/Argentina/Zimbabwe inflation. Another example is large number of Chinese investors buying up prime U.S. real estate to "park their money.")
- **Counterparty**:  Person who is providing them the good/service they need (rent, food, other).
- Next best alternatives**:**  SWIFT/ACH/Western Union and cash (transfer of wealth).  Gold and USD (store of wealth).
- **Provider of next best alternatives**:  Government-registered banks, money transmitters, independent off-shore banks (store and transfer of wealth).  Central bank + enforcing government (provides the instrument and trust).
- **Tradeoff**:  Between acceptance by peers (merchants/peers) and trust of issuer.
- **Atomic unit of success**:  (1) Ability to pay for good/service, (2) Peace of mind around saving for future goods/services (no loss, low volatility)
- **Intermediate utility**:  Transactions only require two parties at a time.  Storing value requires everyone to be bought in passively (other people believe it), but requires only "single player mode" actively (you hold it).
- **Challenge**:  Game theoretic deadlock in getting merchant and supply chain buy in for accepting a new currency.  Lack of stability due to difficulty in matching monetary policy (supply) to predicted adoption curve (demand).

<br/>

#### Web3

- **Value Proposition**:  Users have more ownership over their digital data.  Users are less vulnerable to value misalignment with service providers such as Google and Facebook.
- **Core Innovation**:  An Internet where users rely less on centralized services that custody our data to provide the fastest, smoothest, most convenient experience, and an Internet where data ownership and service provision are decoupled (*e.g.* public p2p blockchain architecture: Ethereum (+IPFS), "BYOData": Blockstack, gossip protocol: Secure Scuttlebutt).
- **Core Customer**:  People underserved by the current Internet:  people that cannot express what they want ([China's Internet](https://en.wikipedia.org/wiki/Censorship_in_China)), people that cannot access all of the information due to censorship/obfuscation ([Catalonia censorship](https://ooni.torproject.org/post/internet-censorship-catalonia-independence-referendum/)), and people that don't trust their service providers with their data ([Facebook's Cambridge Analytica scandal](https://www.nytimes.com/2018/03/19/technology/facebook-cambridge-analytica-explained.html)).
- **Counterparty**:  Other peers consuming and producing data online.
- **Next best alternatives**:  Google, Facebook, Twitter, Instagram (the products).
- **Provider of next best alternatives**:  Google, Facebook, Twitter, Amazon, Tencent, Alibaba, Baidu (the profit maximizing entities behind the products).
- **Tradeoff**:  Between UX and trust.
- **Atomic unit of success**:  To be able to reach a broad audience without being stopped (censorship resistant).  The user ultimately having more control over their data and its privacy/commercialization.
- **Intermediate Utility**:  Closed loop networks with core customer base ("we're all censored") is likely small.  More interesting would be somehow to distribute web3 *write* demand to the existing *read* traffic of web2.  A strong indicative metric would be to see how much the web3 community is able to dogfood its own tech and derive utility (people in working in crypto full-time still use Twitter and Venmo).
- **Challenge**:  (1) Web3 is not just percentages or few multiples more expensive but in fact many orders of magnitude more expensive to store and serve, which means that price parity may come but is not imminent and (2) getting average users to choose web3 over convenience and familiarity of web2.

<br/>

#### Open Finance

- **Value Proposition**:  Financial tools and products available today to high net worth individuals and large corporations becoming available and affordable to everyone (or financial products/access available in developed markets becoming available in frontier markets).  Ability to take your wealth / assets with you smoothly across financial service providers.  Ability to frictionlessly participate in foreign economic growth by participating in their financial markets, just as easy as you share data/information across borders today.
- **Core Innovation**:  Unified data sources and protocols across financial institutions. Compliance, back office, repeated ledger management cost cutting via shared data structure/source and management.  Better underwriting of financial products via making the financial system more interoperable with the rest of the Internet.  This will help unlock cost of capital and cost of living arbitrage opportunities, which will transfer wealth from rent seekers to network participants.
- **Core Customer**:  People that don't have access to core financial products for wealth generation (out of price, no access, no awareness).
- **Counterparty**:  Other people who are trying to bet on the future with you and want to exchange resources and risk/reward.
- **Next best alternatives**:  Existing financial and banking services (marked by higher fees, stronger lock ins, slower service, trust and little incentive to improve service quickly).
- **Provider of Next Best Alternative**:  Regional Banks, National Banks, Multinational Banks, specialized fintechs (SoFi, Robinhood, Simple).
- **Tradeoff**:  Between (a) legal protection, enforceability and compliance versus (b) lower cost, lighter touch intermediation, more access, and more openness.
- **Atomic unit of success**:  Ability to receive money today for promise of returning more money tomorrow.  Ability to lend/invest money today and to be able to receive it back with financial return in the future within the agreed risk parameters.
- **Intermediate utility**:  While rates and counterparty discovery becomes significantly better as markets develop, one party receiving a loan from another party is immediately useful to both parties involved without a whole network being bootstrapped already.  That's great for generating intermediate utility.
- **Challenge**:  Most use cases require reputation/identity (recourse for bad actions, benefit for good history) and legal enforcement (guarantee property, enforce payment / penalty).
 Specifically, wrapping with legal enforceability means that it needs to have capital controls and identity (AML/KYC).  It also requires ability to change record of truth upon arbitration ("That's actually legally mine, but I lost it / was hacked, can you restore it?").

*** Future version may have to split this section into crypto-native vs fiat-native open finance.  ("Crypto-native open finance" is the intersection of web3 and open finance.)*

<br/>

### The Timing of It All

#### Long-term: It's not a competition.

On a long enough time horizon, these theses will ultimately coalesce.  As a quick mental exercise from the lens of each thesis:

1. Sound money: "Money is software."
2. Web3: "Own data; get money for data →  Data is money."
3. Open finance: "Financial services are software."

There's no doubt that software continues to [eat the world](https://a16z.com/2016/08/20/why-software-is-eating-the-world/) over the next few decades.

<br/>

#### Medium-term: Repeating musical chairs.

Of course, the decentralization ethos can catalyze adoption by creating a beachhead with a more accommodating user base ("I like privacy, so I'll use Signal over iMessage despite lacking features", "I like local businesses, so I'll pay more at the bookstore than buy on Amazon"), but to get mainstream adoption, **the traction on the beachhead has to fuel technological and product innovation that can target an ethos-neutral mainstream audience**.

The early use cases with product-market fit will account for the vast majority of the early usage, and in turn will get the most customers, mindshare and resources.  The early wins that share significant infrastructure with the next wave of intermediate utility will become strong incumbents (*e.g.* Coinbase building decentralized exchanges or custody solutions).  This pattern of early winners serving as the breadmaker for the entire space (*e.g.* Binance has a ten-figure war chest and is reinvesting in the ecosystem) will repeat until mainstream adoption.

Since the target end user changes while [crossing the chasm](https://www.amazon.com/Crossing-Chasm-Marketing-High-Tech-Mainstream/dp/0060517123), it's like a repeated game of musical chairs where previous round winners have an advantage, but nothing is won until the final version of usefulness is achieved.

<br/>

#### Short-term: Embracing timing ambiguity.

Because of the entropic adoption path, ethos-charged black/white challenges of asking, "you don't think Bitcoin is better than fiat?", "you don't think web3 is more trustworthy than Google?", "you don't think decentralized finance is better than JP Morgan?" are not productive to seeking the truth.

So instead of asking what will come true vs not come true, it may be more fruitful to ponder which path may catalyze the others?  It's probably just a matter of timing.  1 year vs 4 years vs 10 years vs 25 years are *significantly* different outcomes in building/investing, so this is the name of the game.

<br/>

### Assessing What's Next

The conceptual framework above should help any of us begin to assess the value proposition, the customer and their needs.  From there, it is up to the each of us to interpret the potential size of each market and how compelling each thesis is.  I'd love to see more analytical follow ups, but the below is my intuitive take:
<br/>

#### Sound Money: In Code We Trust

Sound money is here to stay.

(1) Money is simply a ledger of who owns how much of something.  And weirdly enough what it fundamentally requires is that others are willing to exchange goods/services with it and hold it.  (2) Perhaps more importantly, we've built incredibly efficient and borderless information sharing and consumption platforms over the past two decades (such as search, social media and instant messaging).  **Those two points combined has made now a uniquely compelling time to experiment with a concept of decentralized digital money.**  It is now faster and more inexpensive than ever to create an idea and to share it virally with the world, and now that money can be money.  Still mind-boggling to me.

Unlike web3 or open finance, the money use case only requires belief and reasonable scalability to succeed.  As such, the ingredients for success are already within reach.  The rest is up to what consumers decide, what regulators decide and how the community decides to communicate the product.

That is why one of the few high conviction beliefs available today is that the concept of a non-sovereign (or perhaps pan-sovereign) digital money is here to stay (whether that is Bitcoin, Ethereum or something else entirely).  The hurdles here around scalability, awareness, wealth distribution, regulatory framework seem reasonable compared to the demand of the expanding core customer base.

If hypothesis above is correct, **crypto-enabled businesses that support adjacent services for the decentralized store of value will be highly valuable** (insurance, custody, security and any other UIs and managed services on top of the core protocol).

One aspect of this thesis I'm passionate about is wealth distribution (and surprisingly one of my most contrarian positions).  **Because the value of money changes throughout its adoption cycle, I believe that wealth distribution is in fact an evolving feature of any money.**  Wealth distribution is one of the largest sources of long-term fragility for any monetary system.  The converse is also true: **when guided correctly, it be a source of unstoppable growth and [antifragility](https://en.wikipedia.org/wiki/Antifragility)**.  I believe this will be one of the most productive areas for experiments in crypto going forward (more on this on another post).

<br/>

#### Web3: UX vs Trust

Web3 faces a high bar for adoption.

While the social need for an Internet without abuse of centralized control must absolutely recognized, **the customer-focused framework paints a challenging view of the adoption path today**.  It has a (very important but) small customer base with a strong need, trying to reach an audience that is already satisfied by (addicted to?) incumbent platforms.  This was one of the difficult realizations, especially as someone who is passionate about the tenets of web3.

**At feature parity, people will choose trust, but most people are not likely to sacrifice the convenience they have today for "trust insurance"** (unless there's an high-profile event that eventually turns the pubilc narrative).  The fundamental challenge here is the asymmetric cost/benefit for the censored vs their target audience.  The broader audience is used to the benefits of a smooth, quick and managed experience that delivers the information that they enjoy (*i.e.* dopamine hits, [worldview corroborating information](https://www.theguardian.com/politics/2017/feb/04/twitter-accounts-really-are-echo-chambers-study-finds)) quickly and effortlessly.  While people all claim they enjoy "good" ethos and "healthy" things, behavior tends to indicate otherwise (vices and impulses dominate internet services).  So the people that are censored want web3, but the people that aren't censored are already on web2, and––despite potential issues (of fake news, irresponsible data custody etc)––it unfortunately works well for most people on most days.

Furthermore, intermediate utility may be more difficult to achieve here due to the nature of the atomic unit of success for a network participant.  Money interactions are comprised of independent one-to-one transactions being offered and settled, whereas data interactions (web, Internet usage) are often comprised of many concurrent one-to-many data consumption feeds happening at once.  More specifically, money (sound money / open finance) interactions are focused on *write operations* (making a transaction changes state) and business model scales with writes (% of transaction value or # of transactions), whereas Internet/data interactions are focused on *read* *operations* (serving an Instagram photo or an article to a user) and the business model scales with reads (eyeballs → ads, subscriptions or equivalent).

**It's worth considering if and why the web3 ethos must be coupled with blockchain technology**;  having a clear articulation of this would certainly be helpful regardless of one's views on the topic.  For example, it's fascinating to see (a) the "bring your own data" approach of [Blockstack](https://blockstack.org/) and (b) the no blockchain & pure gossip protocol approach of [Secure Scuttlebutt](https://www.scuttlebutt.nz/) getting much less attention than Ethereum.  There's also an open question of whether compensating participants for economic value generated in the network requires a blockchain or if incumbents can serve that user demand without employing a public blockchain (will think more about this).

From a social/public goods point of view, this is an incredible movement that should be supported in continuing to experiment with different architectures for information organization and propagation.  It's also possible that there is an alternate architecture that could compete with today's "fullstack" approach (decentralize all the layers, apps, infra).  For example, a sound money + centralized services that is compatible with a non-blockchain web3 solution using a p2p gossip protocol is entirely technically possible.

This all said, I believe that the companies that are working on web3 are fighting for an important ethos of empowering the user and building public utilities that serve everyone.  **That is undoubtedly an ethos worth fighting for**, and I'm hopeful that the mission will help these teams navigate the idea maze to the right place, even if the path isn't crystal clear today.  The teams working hard on valuable infrastructure R&D will always have an essential role to play in the broader ecosystem, no matter what the future holds.

*(edit: In a future post, will write more about alternate definitions of web3 that extend beyond "rip-and-replacing" web2–with a focus on participant-owned networks. May be worth updating the piece to reflect this important distinction.)*

<br/>

#### Open Finance: Bearer vs Registered Instruments

And within in a maze, there's another maze.  Welcome to the recursive crypto maze.

<br/>*Bearer Instruments vs Registered Instruments*

The key to articulating the value proposition and challenges of open finance comes down to understanding the concept of bearer instruments vs registered instruments.

A [bearer instrument](https://en.wikipedia.org/wiki/Bearer_instrument) gives legal claims over the provided rights (voting, yield, etc.) to whomever holds the instrument. A registered instrument's legal claims are managed by a trusted intermediary who administers the rights of the instrument on behalf of the legal holder (and those registered owners simply hold a certificate).

With a bearer instrument, you don't need to trust anyone, with a registered instrument, you need to trust that they will stand by your interests in good times and bad.  On the flip side, with a bearer instrument, if you lose it, there's no one you can go to for help.  With a registered instrument, losing a certificate means you just go to the intermediary and get another one.

<br/>*Bitcoin*

Bitcoin is a non-reversible digital bearer asset, essentially like cash; whoever holds it owns it.

Bitcoin was beautifully designed in the sense that the features that it prioritized made it uniquely fit to serve well as a digital bearer asset.  No identity requirement, no charge backs. **Instant settlement.**  The digital bearer asset use case has the unique quality that all components of the transaction are present at one moment in time (no future promises to fulfill).

<br/>*Debt, Equity & Open Finance*

Debt and equity capital are driving forces of the economy.

With credit, we can stake our reputation to get resources today and pay someone back tomorrow.  If we're successful and honest, we pay the lender back with interest.  However, if we're either not successful or not honest, we are held accountable by some other authority at a later date.

With equity, we can give/sell part ownership of an enterprise to get resources today, and in return we promise it will be a more valuable asset tomorrow.  If we fail and were honest, no harm, no foul.  However, if we're a bad actor in our role as a fiduciary, we're held accountable by some other authority at a later date.

Most such securities are registered instruments, not bearer instruments.

<br/>*Money vs Securities*

Because credit and equity retain value over specific scenarios over a period of time, reputation and identity are far more important than in an instant settlement instrument such as cash or Bitcoin, which are intended for use cases where all terms of transaction are known and present at the time of the transaction.

The value of money does not depend on the action of the previous holder or transaction (*i.e.* the previous holder of your $100 bill cannot somehow affect the value of the note once it's in your hands), but only on the action of the one central authority that manages your entire economy.  So money is a unique bearer asset that depends on only one thing to retain value: trust in the money's administrator.

In contrast, registered securities (equities, credit, property) require not only the faith in the law (property rights, security laws etc of the issuing jurisdiction) but also the good faith of their counterparty.  This is likely why users will continue to demand registered instruments that provide that protection as a service for the security owner.  Therefore, while sound money doesn't require active participation from a government, most forms of real asset on a blockchain require integration of credible enforcement (examples include binding legal contracts that refer to Colored Coins or ERC20 tokens that represent property title).

<br/>*Finding the right markets*

Another consideration here is that meaningful adoption will most likely happen first in frontier markets and not developed markets.  Developed markets have fairly mature financial infrastructure, which makes the bar for change much higher.  Compelling open finance use cases will be enabling basic forms of lending, commerce, identity in frontier markets that lack identity systems and already use foreign currency as store of value.

<br/>*Bottoms up vs incumbent consortiums*

As a thought exercise, the alternative outcome can be studied by what happened with Visa.  Visa started as a non-profit owned by banks as credit card infrastructure for that consortium, and now it's more valuable than all but one of the individual banks (Visa $323B, JPMorgan $385B).  As such, an open-finance consortium led by various banks and Internet giants (anyone with distribution and regulatory edge) would be a credible player to compete for a version of the open finance vision.

This is not ideal solution from the "crypto native" point of view.  However, we cannot ignore the possibility of banks and Internet giants raising the bar for minimum viable usefulness just enough to make the upstarts less compelling on a relative basis (the bar for fintech in the US is becoming higher as we speak with [same day ACH](https://www.nacha.org/rules/same-day-ach-moving-payments-faster-phase-1), [high-yield savings acct by Goldman](https://www.marcus.com/us/en), various [mobile-first banks](https://www.varomoney.com/)).  In fact, some giants are considering competing on blockchain technology directly ([Facebook](https://www.recode.net/2018/5/8/17329696/facebook-blockchain-crypocurrency-david-marcus-crypto-messenger-app), [Goldman](https://www.coindesk.com/goldman-sachs-is-reportedly-mulling-a-cryptocurrency-custody-service/)) or by tapping into its ethos ([Airbnb shares for top hosts](http://tomtunguz.com/airbnb-shares/)).  This argument extends to sovereign states as well (China could launch RMBCoin faster than US launches TreasuryCoin), and try and take a crack at creating the open standard for identity & financial infrastructure in countries that don't have it yet (SEAsia and Africa).

As such, open finance represents some of the most complex parts of the crypto maze today.   It will be interesting to discuss startups vs giants, developed vs frontier market components of the infrastructure/adoption in another post.

This section does not seek to argue the merits of one thesis over another but instead is an exercise in clarifying my own thinking.  I'm curious to hear what you think, but before you get too excited or offended, let's discuss (1) assumptions that could significantly change the intuitions above and (2) how we can contribute from here.

<br/>

### Exploring Assumptions and Rebuttals

It's worth discussing what assumptions could change and change the implications of the cognitive dissonance discussed above.

1. *"Tech reaches feature/SLA parity over time."*  This argues that tradeoffs at base layer could become much less expensive due to technological breakthroughs.  This will certainly be directionally correct at most points in time as research continues; effective replication factor of data, cost/time of nodes discovery, and data routing will most certainly decrease over time.  However, the more important question is if and when it can come down enough to make up for the UX gap for even the motivated user (then further down for the average user).
2. *"Modularity of services and checks & balances provide value to the participant."*  For example, a version of the US that is run by one dictator that runs all three branches of government would certainly be more efficient than the checks and balances we have today, but more importantly it would be a fragile equilibrium.  Perhaps the decentralized base layer provides a way for the trusted intermediary services on top to have checks & balances, resulting in a net improvement for the user.  This is vague at the moment, but would like to revisit this concept as the infrastructure and products mature.
3. *Decreased compliance and human cost.*  The tech itself maybe less efficient than the centralized counterpart, but perhaps reducing the recurring operational cost of intermediation (i.e. compliance backend, and various back office functions of banks)  will provide a net savings.  Cloud infrastructure is optimized for efficiency and lower cost, so the main way to have lower total cost is by tapping into underutilized hardware (zero capex, minimal opex) or by reducing repeated human administration cost of non-core / supporting services.  This is an interesting line of argument worth keeping an eye out for; not enough data points to confirm yet, but it's possible and if true, significant.

<br/>

### How Can We Contribute Today?

Looking at the challenges above and being discouraged is like writing off the Internet in 1990 and saying "this won't work."  The productive response is to "[be a hyperrealist](https://inside.bwater.com/publications/principles_excerpt)" and approach the solvable problems today.  For example:

1. *Experimentation.*  Continue experimentation on different set of tradeoffs ([decentralization, scalability, security](https://github.com/ethereum/wiki/wiki/Sharding-FAQs#this-sounds-like-theres-some-kind-of-scalability-trilemma-at-play-what-is-this-trilemma-and-can-we-break-through-it)), level of abstraction for user interaction, as well as different markets, niches, distribution channels with the goal of mainstream usage.
2. *Building products that can get ethos-neutral users.*  The first step is to build for ethos-aligned users that are willing to sacrifice UX and evangelize, but the goal should be to build products that can get ethos-neutral users.  People don't use Google for its algorithm; they use it for its speed in retrieving information they were looking for.  Analogous to [how privacy for requires opt-in from people that care for privacy](https://www.tonysheng.com/privacy-freedom-crypto-anarchy), decentralized tech requires broad buy-in to compete with incumbents meaningfully.
3. *Experiment* *outside "meatspace."*  Purely digital assets and experiences may serve as an excellent early beachhead for experimentation.  They have the advantage of not requiring physical or legal enforcement.  For example, the virtual building you built on SimCity could be built with borrowed digital currency secured by another digital building you own in a different part of the game universe.  While this example is purely digital, there could be a path where the infrastructure that powers this economy could be an early test bed for future real estate transactions in the physical realm.
4. *Experiment in friendlier regulatory environments.*  Singapore and Malta are examples of much friendlier regulatory environments than say the U.S., Japan, China or Korea.  Another example is that certain jurisdictions may treat cryptocurrency related gains/losses differently with respect to taxes, which may inadvertently create tailwinds for adoption in favorable jurisdictions.  [ I should find a link for implications of positive law––"these are the things that are legal" (and everything else is not)––vs negative law––"you must not do this" (but everything else is ok). ]
5. *Frontier/developing markets.*  Places such as Nigeria, Indonesia, Malaysia, Argentina are attractive environments that have potential for reaching core customers.  Some indications include: more cash-based, less established financial infrastructure and access to products, use of non-native sovereign currency for better stability.  Look for these fundamental indicators of finding core customers (side note: don't read articles from crypto news sources, too much hype to give you a fair gauge of the traction level).
6. *Do research*. build the most efficient and powerful primitives for privacy, decentralized computation etc that makes the correct tradeoffs.  For example:
    - Storing data.  Decrease replication factor / compute overhead of decentralized architecture.
    - Retrieving data.  Improve data availability and routing schemes.
7. *Better comms*.  Less fluff, hype, ideology (unless you're creating base layer money, in which case, meme away my friend) and more product.  Pinpoint which tech feature you are using.  What is new about this feature?  What technical tradeoff or innovation is enabling this new feature?  What product is uniquely enabled by this feature?  Why is this product clearly better than the next best alternative?  How is data encrypted and distributed in plain sight more secure than data stored at Facebook's data centers?
 Excellent comms is vastly underrated today.
8. *Identify customers and markets.*  [Markets are king](http://firstround.com/review/future-founders-heres-how-to-spot-and-build-in-nonobvious-markets/), so identify one where the product can serve deep customer needs (2017 was ideology, curiosity, speculation and promise of riches).  Articulate how a new feature unlocked a new service for a user that outperforms the customer's current next best alternative.  Now try and pitch it to a skeptical friend.  If it makes sense to them, it's time to build it and attack that market.

<br/>

### Right Values + Uncertainty = Opportunity

The crypto community is working incredibly hard to bend the arc of technological adoption towards openness, economic mobility, and networks that serve (rather than extract from) participants.

I believe that technologies that (1) reduce our reliance on data/value intermediaries and (2) increase the access of financial products that enable wealth generation and global socioeconomic mobility are undoubtedly good, but also valuable for the world.  And when public value is created, it makes it an intrepid time to be an adventurer (*i.e.* technologist, entrepreneur or investor).  It will be a fun decade or two as these hypotheses unfold.

No one knows what will happen, but these are some frameworks that help me think about how the future will unfold.  Uncertainty and lack of consensus can be frustrating or confusing, but that exactly is the opportunity for us to contribute.  I hope the idea maze above helps you in deciding where we should focus our collective energy in order to generate the most promising opportunities for mainstream adoption.

If you have any questions/ideas/responses/challenges, let's chat!  If you want to collaborate in building and navigating this future, I would love to journey down the crypto maze together. Thanks for reading!

<br/>

#### Footnotes

*Many thanks to Martin Becze for discussions that led to this post.  Shout out to Jill Carlson, Tony Sheng, Linda Xie, Tom Ding, Sizhao Yang, Lily Liu for conversations that helped articulate these thoughts.  Thank you Vitalik Buterin for review of historical accounts.  Thank you Lakshman Sankar, Jordan Cooper for feedback.*
