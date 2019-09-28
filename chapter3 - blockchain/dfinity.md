# Why Dfinity is going to win? And why are smartwatches so boring?

Typically, I write technical jargon; since I find it more satisfying intellectually. Claiming things as objective require a thinking process - everyone has their own framework. For me, writing things down works. Typically, I restrict myself to pen and paper and scribbling of diagrams - but at other times it's the oral and written form that's ideal.

This post is going to be different in a sense that it'll go into some thesis of mine. I'll restrict myself to my specialty - which is technical infrastructure.

## Lessons from AWS/blockchain

I worked at AWS - for a short while (2017). but during that time, I saw numerous problems at Amazon. it wasn't clear what the infrastructure was. who takes dependency on what? is ec2 relying on internal machines or are internal machines relying on ec2. there were circular dependencies everywhere and when I asked a principal developer who was responsible for a significant part of internal infrastructure - he said that the system just needs to tie together somehow. that baffled me for a long time.

if you look into my previous posts, you'll notice a trend. first its p2p networks and consensus; then the focus is on application of cryptography and later consensus. on twitter im mostly ranting about cryptoeconomics. and finally, i talk about the turing complete solidity.

At first, I was fascinated by the idea of peer-to-peer with consensus. It provided a way of settlement that wasn't initially possible. It captured my attention for a while. Networking is interesting. You are using protocols are all times doing things that are so critical to tying the whole system together. With the birth of microservices, the layer of networking got even more intense. Services started being built out on these layers of networking. That in essence was AWS. yes, it provided hosts to run your long-running tasks, but it also gave way to...

## What happened?

things were so great. apps were being built that kept doing new things - you got uber, you got airbnb, you got postmates. and then suddenly, out of nowhere, the innovation just stopped. ML stopped working. AI started looking like a pipe dream. if we look at the last 5 years, the most captivating things has been bitcoin. is it interesting? absolutely. the most fascinating thing ever. is it exciting. _%\$_ no! anyone who calls it exciting is kidding with himself. its UI sucks. its barely usuable. you buy and hodl. buy and hodl. buy and hodl. and tweet about how its going to take over the world - which is happening btw. and we are all in awe. even those that got relatively early into it.

## Where from here?

so... that's it, huh? the future of the world is tokens and shilling and more tokens and more shillings. i looked at financial markets. its fascinating world of its own - but let's not forget computing. the machinery. the machinery is the real engine that powers the world - it's not finance or biology or politics. those human systems are needed for a collective effort. but improving those systems doesn't achieve anything productive.

we need to improve the core machinery that we rely on. and in today's world, its definition can be very confusing. chips? computers? the internet? cloud? web apps? where is the actual machinery.

## the Internet

the Internet connected everything. all sorts of devices - computers to phones to now even smart watches - through routers, switches, addresses, clients and servers and that powered communication. we stored things on disks, in apps that were stored in disks, in disks that were in the cloud. we ran algorithms on this data to compute super interesting functions that achieved fascinating outcomes. our functions became complex. and then too complex. too complex to store in one single place. while distributing data is easy, but distributing functions is not. this led to problems. on the security side, it led to hacks. on the financial side, it led to high costs. on the governance side, it led to lack of control.

---

## How it differentiates from Bitcoin and Ethereum?

Think of the Bitcoin blockchain as the single source of truth. Transactions get gobbled up by blocks. Those blocks are mined and they get attached to the blockchain. Ethereum blockchain is slightly different - in that it processes transactions to change the state of the universal world. The state is comprised of many contracts, but all of them are persisted on the blockchain. Now, here's a new idea: take the state machine and distribute it across many different shards(true or false?). You still need to the central source of truth that is verified cryptographically. And what you get is: Dfinity.
