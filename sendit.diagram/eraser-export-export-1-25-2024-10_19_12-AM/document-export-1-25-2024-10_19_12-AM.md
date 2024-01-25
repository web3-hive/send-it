# Cash4Cash Contracts

## Orders Contract
#done #testing

A bank contract that holds the funds from the Sender, locks the funds until the selected agent gets their job done. 

**Functions**

- Create Order: When the Sender chooses an agent in Offers contract, that creates an Order. 
- Finalize Order: The Sender calls to unlock the funds that they sent, in order to be claimed by the agent after job success. 
- Withdraw: Agent calls to claim their payments after the Sender unlocked the funds.  
- Send Network Over Data: Sends tokens to other Order contract that the agent would like to claim their payment from. 
- Receive Network Over Data: Receives tokens and messages from the Order contracts in other networks. 
****

## Charity Contract
WIP

**Functions**

- ...
- ...
- ...


## ~Offers Contract ~
**Deprecated!**

Bidders save their offers in this contract. It is located in zkEVM as the cheapest network to follow up millions of offers as fast enough to operate and with cheapest gas fees. 

**Functions**

- Create Offer: Runs when the bidder/agent send their offer to the app. 
- Get Offer: Client app can get specific offer when needed. 
- Get OffersList: Client app can get all offers. 
- Get OffersList with parameter: Client app can get multiple offers in multiple ranges. 
- Send Over Network Data: Sends an Offer data to Order contract, even if it is in a different network. 
**Done, needs testing.**





