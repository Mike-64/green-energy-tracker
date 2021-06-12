![Logo](https://gblobscdn.gitbook.com/spaces%2F-MbU7GF9p1m1WWm8eWyQ%2Favatar-1622948815179.png?alt=media)

# Green Energy Tracker System

## Goals

The Green Energy Tracker System is a system that creates a blockchain record representing compensated footprint that can be used to show authenticity. It records a timestamp on Ethereum to show the records of compensated footprint and is able to prove ownership from credits of a green energy source.

The stakeholders are trying to achieve a tracker system that can certify the compensation of buyers of the output from a green energy source. There’s no pre-existent software offering this kind of solution to track client’s energy footprint at the moment and the stakeholders want to utilize cutting-edge technology to address that problem.

Using IOTs devices and tokenizing the green credits certificates and programming blockchain smart contracts and encapsulate all that in a mobile interface so the user can fast interact in a secure form will allow companies to buy the credits they need to cover their footprints with easy.

The success of this project will be measured by crypto income provided by the negotiations registered in the blockchain. All the transactions involving the GET Token will provide a cut to the developers.

## Problem

There are companies that need to prove that they compensate their footprints and there is no easy, fast and secure way to do it nowadays. All the process is costly and slow, it’s a lot of steps that demand a lot of effort with a lot of thirty parties involved.

## Solution

Firstly, we intend to measure the footprint using IOTs device that will record the company’s emissions. Those devices will then be connected with Smart Contracts. Companies now will know how many credits they need to buy to compensate its footprint. To allow an easy way to do the transactions, companies will buy the credits in form of tokens, crypto assets that represent the real certificate, from a simple mobile interface. With the tokens in hand, companies will pay for the footprint they need to compensate. All the transactions will be stored in the blockchain. The report events can be followed in real-time again, simply by using a mobile interface.

# Stakeholders

A group of entrepreneurs and blockchain developers, all ex-students from the Blockchain Development program at George Brown College. A small team using cutting edge-technologies that want to revolutionize the way people work with green credit compensations actually.

With a tech background, we have electric engineers, computer engineers, computer scientists. Each one playing an important role in the deployment of this solution bringing accumulated knowledge and experiences.

The project management will be done by Alexandre, the smart contract by Michael, the web interface by Alexei, and quality assurance and test-cases will be Dhruvan responsibility. In fact, they all will act together helping each other since they all have the necessary’s skills to do so but since the task needs to be divided it was decided that.

The main restriction of this project is the short time and the budget. It all will be made in just one sprint (Agile/Scrum) with no resources to cover any paid program. That said, all the frameworks will use open-source solutions.

We will use some dummy contents to measure the result of this project, we will consider it a success if our MVP could do all the transactions intended. With this application validated the stakeholders will then look after venture capital to prepare the solution to the market.

# State Data

* Token representation of green source certificates needed to compensate footprints.

* Data&time, green energy source, footprint emitted, footprint compensated

* The system is tracking all the companies’ compensated footprint.

* We will cover a single company as a client and a single green energy source as a provider.

* No money will be invested at this time, only professionals' teams and efforts.

* We will need to capture the footprint generated by the company and measured by the IOT device. We’re going to use sample data to simulate that in this phase.

* Reports of the footprint compensated will be generated and displayed in a web interface.

* We will provide a mobile interface to buy credits online.

Table: Example of footpint compensation performance

# Restrictions

* Buyers can only buy credits within a 24 hours interval.

* Buyers can buy more than 10 times inside the month.

* Ownership cannot be changed. Clients need to negotiate directly with the Green Energy Source.


# Exceptions (normal flow and special cases)

* The owner can negotiate credits between clients.

* The owner can allow more buys from the client inside each month.

* Can any of the rules be broken under certain circumstances?

* Must be said ahead of time. To overwrite the rules.

* Should any new rules be added in certain circumstances

* What about edge conditions?

## Tech Stack

**Client:** React, Web3.js, Bootstrap 5

**Smart Contract:** Solidity

**Blockchain:** Ethereum

## Run Locally

Clone the project

```bash
  git clone https://github.com/alexeipancratov/green-energy-tracker.git
```

Go to the project directory

```bash
  cd green-energy-tracker
```

Install dependencies

```bash
  npm install
```

Deploy the GreenEnergyToken smart contract to test blockchain (e.g., Ganache) and copy-paste the contract adddress to the "ui/src/contractAbis/greenEnergy.js" file

Switch to the ui folder

```bash
  cd ui
```

Run React UI locally

```bash
  npm start
```

You should be able to interact with the application.

## Authors

- [@AleRapchan](https://www.github.com/AleRapchan)
- [@Alexei Pancratov](https://github.com/alexeipancratov)
- [@Michael Francis Jerome Victor](https://github.com/Mike-64)
- [@Dhruvam Patel](https://github.com/dhruvampatel)

## Documentation

[Full Documentation](https://rapchan.gitbook.io/green-energy-tracker/)

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## Support

For support, email blockchain@alexandrebarros.com or join our Slack channel.

## Appendix

- Web3.js: https://web3js.readthedocs.io/en/v1.2.11/web3-eth-contract.html#contract-events
- Bootstrap 5: https://getbootstrap.com/docs/5.0/getting-started/introduction/
- Metamask: https://docs.metamask.io/guide/
- Remix: https://remix-ide.readthedocs.io/en/latest/
- React: https://reactjs.org/docs/getting-started.html
- Solidity: https://docs.soliditylang.org/en/v0.4.24/
- Ganache: https://www.trufflesuite.com/docs/ganache/overview
