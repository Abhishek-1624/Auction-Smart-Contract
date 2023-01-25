THE AUCTION SMART CONTRACT:-
1.Smart Contract for a Decentralized Auction like an eBay alternative

2.The Auction has an owner a start and an end date

3.The owner can cancel the auction if there is an emergency or can finalize the auction after its end time

4.People are sending ETH by calling a function called placeBid().The sender's address and the value sent to the auction will be stored in mapping 
  variable called bids

5.Users are incentivized to bid the maximum they are willing to pay but they are not bound to that full amount but rather to the previous highest bid
  plus an increment.The contract will automatically bid up to a given amount

6.The highestBindingBid() is the selling price and the higestBidder is the person who won the auction

7.After the auction ends and the owner gets the highestBindingBid and everybody else withdraws their amount
