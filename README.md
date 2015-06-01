# LoyaltyLedger
Loyalty Ledger using BlockChain 2.0

APIs
I think what we’re thinking of is using a coloured coin API http://coloredcoins.org/ for attaching assets to the blockchain.
 
CoinSpark
One suggestion is to go with coinspark (site css is broken) http://coinspark.org/
Richard, I think you mentioned that you know someone in their team? Perhaps that can provide us with an API key?
Technically, we could run their server locally.
 
Coin Prism
I’ve also registered with CoinPrism. https://www.coinprism.com/ I’ve registered with them. They have a nice apiary doc site. http://docs.coinprism.apiary.io/ I’m trying to transfer some BTC there from my Ripple account …
 
VM
I think we have common denominator of Java (with some of us being polyglot).
Can I suggest JDK 8?
The bitcoind server basically accepts JSON RPC which there are ample libraries around for various platforms. I think some of us are Java only. So I think it best we stick with that.
Server stack – shall we continue our use of vertx? That will be able to house any Java specific code we write. But also can host any front-end assets that the UI developers want.
We may also use node+npm if the UI guys think it best.
For IDE: my personal choice is IntelliJ for java development and sublime text for text editing.
 
Bitcoin Network
I’m wondering if we should plug straight into the dev bitcoin network or try to host our own network (a regtest network) network for demonstration purposes.
I would suggest downloading the server and having it handy in case. https://bitcoin.org/en/download
