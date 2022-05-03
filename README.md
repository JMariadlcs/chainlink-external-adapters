# chainlink-external-adapters

This is a workshop used to build an end-to-end DEMO that uses Chainlink Adapters from Chainlink Hackathon Spring 2022.
The workshop followed to complete this repo is [this one](https://www.youtube.com/watch?v=fICFYsN4E74&t=2527s). The used repo that contains some implementations is [this one](https://github.com/smartcontractkit/external-adapters-js) and the cloned repo with the template used is [this one](https://github.com/thodges-gh/CL-EA-NodeJS-Template).

Chainlink External Adapters allows to connect to APIs that are unreachable via de standard [HTTP task](https://docs.chain.link/docs/jobs/task-types/http/). That means that you can connect any API that is avaliable on the Internet to your Smart Contract by using Chainlink nodes through Chainlink external adapters.

- They way it work is like the one in the following figure:
<img src="./images/adapters.png">

- The API we are going to ask for information is [this one](https://developers.halodotapi.com).
1. Create API KEY.
2. Clone [template repo](https://github.com/thodges-gh/CL-EA-NodeJS-Template).
```bash
git clone https://github.com/thodges-gh/CL-EA-NodeJS-Template halo-ea
```
3. Execute:
```bash
cd halo-ea
yarn
```


## Resources
- [Chalink External Adapters](https://docs.chain.link/docs/external-adapters/): Chainlink external adapters documentation.
- [HTTP task](https://docs.chain.link/docs/jobs/task-types/http/): standard HTTP task documentation.
- [HALODOTAPI](https://developers.halodotapi.com): Used API in the example.
- [Extneral-adapters-js](https://github.com/smartcontractkit/external-adapters-js): repo with external adapters implementations.
- [Nodejs Template](https://github.com/thodges-gh/CL-EA-NodeJS-Template): Used Nodjs Template example.