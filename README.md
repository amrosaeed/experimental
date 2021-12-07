# Nakamoto consensus over MANET (Gaza Strip case)

### Abstract:

In this think piece we’re trying to build a blockchain as an interface between theoretical computer science and human behavior exploiting the fact that humans are not infinitely rational and in particular they have computational constraints in what they are able to think (Byzantium) in a finite amount of time specially in highly hostile and rapid congested moving environment (Lipschitz continuity), discovering to what extent we can reach with resembling a Nakamoto consensus within such blockchain constituents leveraging the rationality of Nash equilibrium that can be achieved in a game setting where players ( population & main players ) are under a severe conflict scenario, and force a some kind of consensus over a set of incentives shared among good players and the bad ones being excluded in consequence to their startegies. 

We analyzed the state of art BlockDAG system design (Wayfinder){1} for its unprecedented achievement towards building Tamper-proof Provenance-Aware Storage for Mobile Ad Hoc Networks and charactrized its pros and cons with regard to use it as a medium of cryptocurrency exchange.

We also argue we can enhance Wayfinder BlokDAG with techniques used to Detect Sybil Attacks using Proofs of Work and Location in VANETs{2}, only under the umbrella of a theoretical game based scenario where the players (nodes) play anonymously and share a very hostile Geo-politically pounded environment like in the case of Gaza strip 

### Game setting:

Place: Gaza-strip a Palestinian enclave on the eastern coast of the Mediterranean Sea.

Area: 365 Km2

Population: 2.048 million (2020)

Density: 5000 citizen/Km2 (the densest in the world)

Currency: Israeli New Shekel (ISL = 0.0000062 BTC)

Technology: Only MANET devices (WWW is not reliable)

Hostile/Conflict scenarios: Following the takeover of Gaza by Hamas, the territory has been subjected to a blockade, maintained by Israel and Egypt.


#### Because of the Israeli–Egyptian blockade, the population is not free to leave or enter the Gaza Strip, Israel maintains direct external control over Gaza and indirect control over life within Gaza: it controls Gaza's air and maritime space, and six of Gaza's seven land crossings. It reserves the right to enter Gaza at will with its military and maintains a no-go buffer zone within the Gaza territory. Gaza is dependent on Israel for its water, electricity, telecommunications, and other utilities.

### Introduction:

The concept of Nash equilibrium is paramount in Game Theory. This is because the exacting brand of rationality that it exudes, Another reason is because the existence Nash’s mathematical proof for that it became the standard way of looking at economic problems

Another contender to Nash equilibrium to force players to act honestly and reach consensus on a globally distributed and persistent shared ledger without diminishing security measures from Byzantine nodes to double spending problems in a certain game setting is Nakamoto consensus but unfortunately, MANET devices (backbone of networking infrastructure in suppressed areas) are often deployed in challenging conditions and most of the time in a mobile state, and their connectivity may be intermittent (Additionally, the absence of reliable up/down link to the world wide web itself) which make it impossible to share a decentralized distributed ledger that is tamper-proof to sypil attacks, byzantine fault tolerance and preventing double spending by different bad players.

#### Prototype:

We developed a core concept of game, a Mixed-reality (Metaverse) type of Dapp as a frontend for users and a blockchain solution as the backend, the application prototype originally built by the wayfinder team showing two applications for emergency first response: a Task List for command and control and an Annotative Map (see Figure 2). The Task List app allows users to post and complete prioritized jobs on a shared list. The Annotative Map app allows users to place prioritized annotations on a shared map. Both applications use 2P+ sets (CRDTs, Conflict Free Data Types) and run with or without network infrastructure in a completely disconnected environment. These applications run on smartphones, servers, desktops, and potentially on IoT sensor devices.

#### Code Base:

In order to implement Wayfinder into a framework that could be installed on manet devices as well as on servers, they chose Java for their code base, though we conjecture that the best way to offload computations leveraging validity proofs (e.g. zkSTARKs) to static devices (Desktop servers) cairo language would be the best choice as a code base, their goal was to demonstrate that two concurrently running applications could rely on the same underlying WBD. (without the notion of double spending problem) But in this paper we worked on taking their further, as we noticed in Gaza-strip game setting we can besides creating a shared list for emergency response we provide a stable coin as a cryptographic secure currency and levitate the stakes in the game.
