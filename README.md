# Supinfo blockchain project

Remainder: this project has to be realized by groups of 4 students max.

For this project, you will have to produce a decentralized voting platform that leverage the benefits of the blockchain technology.

Note: Electronic voting systems are still in the research stage so we will assume that topics like verifiability, coercion-resistance and receipt-freeness won’t be important for the implementation of this project.

During this project, you will learn how to create smart contracts on Ethereum with Solidity.

Your application must comply with the following requirements:

    The responsible of the election defines the list of the candidates, defines the electoral roll and set the end date of the election.
    The voters of the electoral roll are able to vote for one candidate as long as the election is available. A voter can delegate his vote to a member of the electoral roll.

Technical requirements:

    You must use Geth to build your private Ethereum network. Obviously, you will write your smart contracts with Solidity.
    The network must contain three nodes.
    The voters must vote using a web-UI. They can watch the current state of the election with the number of votes for each candidate.

You can add functionalities to the previous requirements, those are the minimum.

You are free to define a background context for your application (representative election, presidential election, etc.). It could be helpful to design your web-UI.

In addition to your application, you will provide a technical and user documentation.

## Additional requirements

- Replace this `README.md` with a presentation of your team and project. It should include all necessary information to run the project locally
- Docker Compose **must** be used to start the Geth nodes locally and the web UI on port 3000
- Before implementing, make a sketch of your UI
- Web UI **must** use metamask
- Smart contract **must** be unit tested
- A blockchain explorer **can** be added locally
- Submit the `.git` folder in your final `.zip` 


## Grade

Smart contract /20
- Create election /5
  - List of candidates /2
  - Electoral roll /2
  - End date of election /1
- Vote /2
- Vote delegation /4
- View election /2
- Code quality /3
- Unit tests /5

UI /10
- Sketch /2
- Create election /1
- Vote /1
- Delegate vote /1
- Connection to metamask /1
- Code quality /2
- UI Design quality /2

Docker Compose /4
- Geth /2
- UI /1
- Blockchain explorer /1

Misc /6 
- Readme with presentation /3
- /3
