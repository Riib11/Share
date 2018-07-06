# ShareCoin

Would you like to _invest_ in promising memes and earn real capital gains? 

Would you like your original content to gain real value through internet popularity?

Then you'll be interested in ShareCoin - the token platform for small digital asset popularity investment!

Once you've registered a link to your digital asset (meme, most likely) on the ShareCoin blockchain, sending its ShareCoin address to friends allows them to access the asset through the blockchain. When they do this, a small amount of ShareCoin is given to your asset for being accessed, and to your friend for participating. Once your viral meme has collected thousands of ShareCoins, you can cash out by withdrawing the coins or sell ownership of the asset to someone else!

## Idea

The goals of ShareCoin are

1. Record the number of times an asset has been accessed by unique sources
2. Reward asset owners when their asset is accessed
3. Reward participants who access assets through ShareCoin

The first goal is important because the reward given to asset owners should be proportional to the popularity of the asset, measured by unique accesses. The accesses need to be unique so that they can't just be spammed endlessly by single sources.

The question this brings up is of the cost to a user for registering a new wallet and sending transactions. Ideally the blockchain will not need any fullnodes, and just being a casual user of this computationally-light blockchain will provide enough hashing power to manage transactions fast. The nice thing is that there doesn't need to be a complicated PoW system with self-regulating difficulty as coins are only minted during a user-activated event: accessing an asset. So, the only mining happens during actual transactions.

When you initiate an 'access' transaction to an asset address, you are presented with a block of transactions to confirm. There will be certain rules that need to be followed by blocks (such as limits on the number of 'access' transactions by a single user address). Additionally, there will be a PoW process that shows that a client has manually reviews and approved the block. The block, with this new 'access' transaction appended, is then posted to the chain.

## Description

A digital currency that connects the popularity of a simple online digital asset to the value of sharing it. The target asset class is memes of course. The asset itself is stored offchain (as storing it onchain would require way to much onchain storage space), but a link to the asset in the form of a url is stored onchain.

The link can be to any url, but the ideal asset types are

| media type | file type       |
|------------|-----------------|
| images     | png, jpg, etc.  |
| animations | gif             |
| audio      | mp3             |
| video      | mp4, mov        |

## How To Use It

There are two basic scenarios where you interact with ShareCoin:

##### Creating a new wallet

This is the first thing you'll do with the ShareCoin blockchain. Like for all other cryptocurrencies, you need a wallet with attached private key and public key to hold your ShareCoins. This wallet is just an address with an attached balance. 

In order to authorize a transaction that removes coin from your wallet, you need to sign the transaction with your wallet's private key (which should be kept very private). In order to authorize a transaction that sends coin to your wallet, you need to sign the transaction with your wallet's public key (which can be shared publicly). Sending ShareCoin between addresses costs a mining fee.

##### Introducing a new asset

This is when you have your brand new meme that you just printed fresh off the sheets and you want to introduce it to the meme economy. To implement ShareCoin, you register your asset on the Asset Chain. This creates an account on the Asset Chain that records a url (of your asset), a wallet, and owner address of the asset and returns to you an address and a public key.

To extract money from the asset's wallet or transfer ownership of the asset, you need the private key of the wallet at the owner's address. When you transfer ownership of the asset, you will no longer have these privelages and the new owner will. The public key attached to the asset is used to sign access requests (explained below).

##### Accessing registered assets

This is when you want to look at a meme (typically sent to you by someone else). To do this, you first must submit an access request to the asset's address, signing it with the meme's public key and you're private key (this is kind of like a send transaction from you to the asset).

This transaction is special, however, in that its completion mints new coins in the asset's own wallet. This transaction between any particular asset address and user address can only mint coins once, for the coins minted are stamped with the two addresses, creating a unique identity that reflects their origin. Additionally, a percentage of the newly minted coins are sent to the transaction initiater, incentivizing them to engage in the system as well.

In this way, having more people access your asset collects coins in your asset's wallet; the asset's popularity earns you money!

Also, the url of the asset you are accessing is publicly avaliable, so to actually access the asset through your browser you just need to visit it. The url is not hidden or hashed because the purpose of ShareCoin is not to be a file service but instead to merely provides a layer that records volunteered information. The actual transaction that is submitted to mint new coins will take some time to process, but that won't inhibit you from accessing the asset.

##### Sharing an existing asset

This is when you have recieved a meme address from a friend.

## How It Works



TODO