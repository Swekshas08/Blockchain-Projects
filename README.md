# Blockchain-Projects

Here some of the experiments of final year Blockchain subject:

# Crowd Funding Smart Contract in Solidity
Things used in the project :-
Solidity programming language.
Ethereum.
Remix IDE.
Architecture of the project :-
Global Variables :-

owner -> owner of the contract
minimumContribution -> minimum contribution required for contributor to do crowd funding.
deadline -> Final Time to do crowdfunding.
target -> crowd funding target (How much funds is targeted to be completed in the deadline);
raisedAmount -> Keep track of the total raised amount.
totalContributors -> total contributors who have contributed to crowd funding.
numRequests -> keep track of requets done by owner.
contributors -> key value pair of contributor to keep track of their address and funds they have contributed.
allRequests -> All requests done by owner for tranfering money to a perticular address for a perticular reason.
Functions :-

getBalance
contribute
refund
createRequest
voteRequest
Make payment
