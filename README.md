# Empowering Communities, Enabling Change

With Makana, the relationship and sponsorship agreements between nonprofits and their sponsors will be enhanced, allowing them to focus on their main goal, improving the world for the better. The community will be accredited to vote on the nonprofit's honesty, which will simultaneously increase trust and relieve both companies of most of their extensive verification process.

## Inspiration

In every impactful event where people and companies come together to make an impact, there lies the meticulous task of reporting and verification that agreements had been fulfilled. Having a close connection with Rotary, one of the largest international charity, I've seen and heard firsthand of the lengths that nonprofits go to in creating reports for their sponsors. It encapsulates rigorous documentation, photography, and verification to assure sponsors that their contributons have made a difference. With Makana, a more transparent and trusting community will be made, and much effort and time will be redirected to positive change.

## What it does

Nonprofits first create a new event smart contract, which will be storing all ballot box smart contract addresses and more. In this contract, they create requests of ballot boxes to multiple sponsor addresses.

The sponsor companies can then go ahead and look at the request, and all the paramters that the nonprofit had filled in. If they are satisfied, they then confirm the ballot box, the contract is created, and the clock starts ticking.

In the meantime, different voters can go ahead and mint 1 ballot NFT to use to vote for the different ballot boxes.

There is a setup stage, where no voting takes place, and then a voting period. In this voting period, the voters with ballots (and therefore voting power) and go and vote on whether or not the ballot box is true or not. When the voting period ends (using Chainlink Automation!), the results are shown, and the sponsor can see whether or not the nonprofit did what they requested.

## How Makana was built

Makana was built on the wide expanse of blockchains and smart contracts. It utilizes Chainlink Automation to implement the timing and stages of each ballot box unto the blockchain. OpenZeppelin's library for the ERC721 and governance token standards were used for the ballot in this project.

## Challenges I ran into

Navigating through token standards and the integration of governance NFTs into this project required much commitment and searching. In the end, an NFT system with voting power, snapshots and more was created, and yet there is much room for improvement.

I also find myself at a time crunch to implement the front-end, which proved to be quite the challenge to overcome. Though not as beautiful as it could be, the front-end turned out well.

## Accomplishments that I'm proud of

I've received much learning and experience throughout this hackathon, which I'm proud of. Also, managing to barely complete the project in time for the due date was challenging but rewarding at the end.

## What I learned

The development of Makana throughout this hackathon has been a rich learning experience, for both concepts related to blockchains and how nonprofits operate.

I've learned deeply on how decentralized governance works, and the voting system within DAOs (in which I took inspiration from).

Also, doing this project has given me the oppurtunity to learn more about how nonprofits work with their sponsors, and the challenges they both face.

## What's next for Makana

There lies many, many possibilities and improvements for Makana.

- The NFT system can be greatly improved upon. A plan for the future is to implement dynamic NFTs, where the NFT updates specific to the event and based on if the voter voted correctly or not. This would incentivize the voter to vote correctly.
- Currently, the way to receive a ballot is open to everyone, and is simply hidden away using a different page. In the future, there would be a system where only certain select people who went to the event will recieve the ballot, using something like NFC chips.
