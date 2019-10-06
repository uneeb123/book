# How fast does our blockchain need be?

## Review

For those who haven't been keeping up so far, we have gotten an open model for an extremely slow database whereby to write any record, not only do you have to comply with a schema, but you also have to wait for your turn by cracking a math problem based on random shuffling that typically takes about 10 minutes to solve (in Bitcoin). It ensures consistency at the expense of being extremely slow\*. And the open model works in such a way that even if you get quantum machines to crack the problem, the difficulty would automatically readjust itself so that it still takes 10 minutes to crack the puzzle and write the next record. Which obviously makes it an inherently slow process. This mechanism, by the way, is known as proof of work. And it is widely recognized as the most trustless way of sending transactions. It is trustless because there is zero reliance on any trusted intermediary. In that sense, it is purely peer-to-peer money that cannot be attacked by anyone. For most practical purposes, however, most people still choose to rely on a trusted 3rd party (payment processors such as Bitpay or Coinbase).

<img src="speed.jpg" alt="Speed" />

## Criticism

The benefit is of this consistency over speed architecture is that anyone can participate by joining the network. The downside is that the more people join the network, the more energy is consumed. There are debates over utility of such networks. Whether their whole purpose is to simply facilitate illegal activities. There is some amount of truth to that. On visiting old [Bitcoin forums](https://bitcointalk.org/), one can see quite clear that the earliest businesses that were established on Bitcoin attracted further privacy features such as coin mixing or gambling. On top of that, there were tons of scandals. Legitimacy of Bitcoin has been seriously questioned and as we have learnt over years, it is actually incredibly hard to stop Bitcoin. It requires unanimous coordination from all different internet service providers and even then a Bitcoin network might only just stop operating while the curfew is in place. Proponents of Bitcoin admire the technology and argue that in a lot of ways, it is the natural way how technology progresses. At first, you only see illicit use-cases and over time, it become clear how the technology can consumed more usefully. So far, in its 10 year, Bitcoin has only managed to challenge governments and store of value assets such as gold. On top of this, due to the slow speed of transactions, cryptocurrencies aren't well-suited for most daily usage transactions. Volatility is yet another topic of debate. But that is solvable problem.

Since these criticsms, different solutions have developed their own ways to tackle ways to overcome various barriers. In this post, we will examine speed and what limits do we really need.

## Payment processors

## Remittance

## Financial markets

Speed of transactions in MakerDAO/Compound
Speed of transactions in Traditional Finance
Lightning Network

Charts/data to back it up

Payments

[*] Another reason for being slow is that the sequence of records can change depending how aggresively they had been broadcasting on the network. If noone saw it, it doesn't exist. Similarly, if 50% saw one sequence and the other 50% saw the other sequence, then we have divide. Which gets resolved on the next turn. This means that you are advised to wait an hour before the transaction can be considered complete. Interestingly, Ethereum has managed to bring down the block time to 15 seconds - thanks to a more efficient way of dealing with diverging chains (more info here: https://www.reddit.com/r/ethereum/comments/5lzif2/why_are_eth_confirmations_so_much_faster_than_btc/)
