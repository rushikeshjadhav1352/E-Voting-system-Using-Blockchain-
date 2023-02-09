# BlockChainVoting

1)Decentralization and Transparency: The use of blockchain technology enables a decentralized and transparent voting system where each vote is recorded as a unique transaction in a decentralized ledger, making it difficult to manipulate the results.

2)Increased Security: The use of blockchain technology provides a secure platform for voting, reducing the risk of fraud, tampering or manipulation of the voting results. The immutability of the blockchain ensures that the results cannot be altered or deleted.

3)Improved Accessibility: An online e-voting system using blockchain technology can make the voting process more accessible for eligible voters, as they can cast their vote from any location with an internet connection, reducing barriers to participation and increasing voter turnout. Additionally, blockchain technology enables real-time counting and reporting of the results, making the process more efficient and transparent.

## Build Setup

```bash
# install dependencies
npm install

# serve with hot reload at localhost:3000
npm start
```

Create your own <b>.env</b> file and the file should contain:
```bash
EMAIL=YOUR_EMAIL_ID
PASSWORD=YOUR_PASSWORD_FOR_EMAIL_ID
```
Install MetaMask extension (https://metamask.io/download.html) and make sure to have some Ether to test the application locally. Ether can be fetched from Rinkeby Faucet (https://faucet.rinkeby.io)

#### Note:
- Make sure to install Node.js v11.14.0 to make sure the app runs fine. Testing for other node versions is yet to be done.
- MongoDB must be working in background on localhost:27017

###### Please star the repo if it helped you in any way!

## Tech Stack:

- Solidity/Web3 (for writing/connecting the Blockchain contract)
- Next.js & Semantic UI React (front-end)
- MongoDB/ExpressJS/Node.js (back-end)
- IPFS (file storage for images)

## Screenshots of the app:

Homepage of the application:

![](screenshots/homepage.PNG)

Company registers/logs in:

![](screenshots/company_login.PNG)

Company creates an election if not created:

![](screenshots/create_election.PNG)

Dashboard on successful election creation:

![](screenshots/dashboard.PNG)

List of candidates for the election (here, you can add candidates):

![](screenshots/candidate_list.PNG)

Candidate has been notified on the mail:

![](screenshots/candidate_registeration_mail.PNG)

List of voters for the election (here, you can add voters):

![](screenshots/voterlist.PNG)

Voters have been sent their secure usernames and passwords on the mail:

![](screenshots/voter_registeration_mail.PNG)

Voter login page:

![](screenshots/voter_login.PNG)

Successful voting scenario:

![](screenshots/successful_voting.PNG)

Unsuccessful voting scenario:

![](screenshots/unsuccessful_voting.PNG)

Notification to each candidate and voter for the winner of candidates:

![](screenshots/winner_candidate_mail.PNG)
