# Rinkeby

- [Permissions](./permissions.yml)
- [APM publish history](./deploys.yml)

## Artifacts

- ENS: `0x98df287b6c145399aaa709692c8d308357bc085d`
- DAOFactory: `0x2298d27a9b847c681d2b2c2828ab9d79013f5f1d`
- APM: `0xda897630fa0f1902f99623bc00e18acd12657d4f`

## Deployments

-----------

- Version: Aragon client 0.6.3
- Start date: Jan 29th, 2.50am CET
- Finish date: Jan 29th, 4.00am CET
- Deployer: Aragon One testnet cold wallet [`0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff`](https://rinkeby.etherscan.io/address/0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff)

Deployment done with `@aragon/cli@5.2.3`.

### Aragon Client

Commands:
```
aragon apm publish minor --only-content --files build/ --environment rinkeby --build-script build:rinkeby --use-frame

aragon apm publish patch --only-content --files build/ --environment rinkeby --build-script build:rinkeby --use-frame
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `aragon.aragonpm.eth`: `1.3.1`

### Aragon Apps

Deployed: `finance`, `voting`, `token-manager`

Command:
```
aragon apm publish patch --environment rinkeby --files app/build --use-frame
```

**Note**: the `artifact.json` for `finance` was regenerated using:
```
aragon apm publish patch --environment rinkeby --only-artifacts --no-build
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `finance.aragonpm.eth`: `1.1.4`
- `token-manager.aragonpm.eth`: `1.1.5`
- `voting.aragonpm.eth`: `1.1.6`

-----------

- Version: Aragon client 0.6.2
- Start date: Dec 21st, 8.10am CET
- Finish date: Dec 21st, 9.06am CET
- Deployer: Aragon One testnet cold wallet [`0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff`](https://rinkeby.etherscan.io/address/0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff)

### Aragon Client

Command:
```
npm run publish:rinkeby:minor
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `aragon.aragonpm.eth`: `1.2.0`

### Aragon Apps

Deployed: `finance`, `voting`, `token-manager`

Command:
```
aragon apm publish patch --environment rinkeby --files app/build
```

**Note**: the `artifact.json` for `voting` was regenerated using:
```
aragon apm publish patch --environment rinkeby --only-artifacts --no-build
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `finance.aragonpm.eth`: `1.1.3`
- `token-manager.aragonpm.eth`: `1.1.4`
- `voting.aragonpm.eth`: `1.1.5`

-----------

- Version: Aragon client 0.6.1 (AGP-1 support)
- Start date: Nov 12th 2018, 4.55pm CET
- Finish date: Nov 15th 2018, 1.24am CET
- Deployer: Aragon One testnet cold wallet [`0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff`](https://rinkeby.etherscan.io/address/0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff) + [@bingen](https://github.com/bingen)

### Aragon Client

Command:
```
npm run publish:rinkeby:patch
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `aragon.aragonpm.eth`: `1.1.4`

### Aragon Apps

Deployed: `voting`

Command:
```
aragon apm publish patch --environment rinkeby --files app/build
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `voting.aragonpm.eth`: `1.1.4`

### AGP-1 Kit

AGP-1 kit hasn't been published to APM, as it is a one time use kit only.

```
AGP1Kit with ENS 0x98Df287B6C145399Aaa709692c8D308357bC085D, owner 0x590e1ac49666ec8024dc0c6620eed6916a18f27e
Using ENS 0x98Df287B6C145399Aaa709692c8D308357bC085D
Using DAOFactory: 0x2298d27a9b847c681d2b2c2828ab9d79013f5f1d
Using MiniMeToken: 0xad0f1afea49a46a8409bf4863070631fec2cedc6
APM 0xda897630fa0f1902f99623bc00e18acd12657d4f
0x8870044ea0ba46dda0b1ce165936cf9a31240ad2
Kit address: 0x9276b52565888d541b03fcc74ae686c15a5e21a7
=========
# AGP1Kit:
Address: 0x9276b52565888d541b03fcc74ae686c15a5e21a7
Transaction hash: 0xcde6a97c80b69eded849e8ac9c2e432ffa86f1675a8aad83dd519a4b17b7673c
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-11-10T22:58:13.955Z
=========
Gas used: 4882338
AGP1 DAO address:  0x383037ad4e2341835bfe719e4bddc5936c271409
Finance:  0x11de0e9390598cfe7d1600dadff9abd9647c8a6e
Vault:  0x3f49a91cc34a6b765cffa2fc898f961cfd4f759b
Voting:  0x93b1900fa5b4ea74263e6ac0682f0e50c90ac98f
Meta Track Voting:  0x469741ced03d2bb94bc6e744cb56a72e767054b3

```

-----------

- Version: Aragon client 0.6.0-hotfix
- Start date: Nov 5th 2018, 9.05pm CET
- Finish date: Nov 5th 2018, 9.35pm CEST
- Deployer: Aragon One testnet cold wallet [`0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff`](https://rinkeby.etherscan.io/address/0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff)

### Aragon Client

Command:
```
npm run publish:rinkeby:patch
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `aragon.aragonpm.eth`: `1.1.3`

### Aragon Apps

Deployed: `finance`, `voting`, `token-manager`

Command:
```
aragon apm publish patch --environment rinkeby --files app/build
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `finance.aragonpm.eth`: `1.1.2`
- `token-manager.aragonpm.eth`: `1.1.3`
- `voting.aragonpm.eth`: `1.1.3`

-----------

- Version: Aragon client 0.6
- Start date: Oct 29th 2018, 11.36pm CEST
- Finish date: TODO
- Deployer: ([@izqui](https://github.com/izqui)) [`0x4cB3FD420555A09bA98845f0B816e45cFb230983`](https://rinkeby.etherscan.io/address/0x4cB3FD420555A09bA98845f0B816e45cFb230983) and Aragon One testnet cold wallet [`0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff`](https://rinkeby.etherscan.io/address/0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff)

### Aragon Apps

Deployed: `vault`

Command:
```
aragon apm publish major --environment rinkeby --files assets
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `vault.aragonpm.eth`: `2.0.0`

-----------

- Version: Aragon client 0.6 RC 2
- Start date: Oct 25th 2018, 5.42pm CEST
- Finish date: Oct 26th 2018, 7.40pm CEST
- Deployer: ([@izqui](https://github.com/izqui)) [`0x4cB3FD420555A09bA98845f0B816e45cFb230983`](https://rinkeby.etherscan.io/address/0x4cB3FD420555A09bA98845f0B816e45cFb230983) and Aragon One testnet cold wallet [`0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff`](https://rinkeby.etherscan.io/address/0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff)
- aragonOS commit hash: [`b5c0a98be5e404bb252e88efc65123c2db650839`](https://github.com/aragon/aragonOS/tree/b5c0a98be5e404bb252e88efc65123c2db650839)
- aragon-id commit hash: [`e33d18d6a78dbcb97bef02b4df52a7dff60b3ef2`](https://github.com/aragon/aragon-id/tree/e33d18d6a78dbcb97bef02b4df52a7dff60b3ef2)

### ENS

Commands:
```
npx truffle compile --all
npx truffle exec --network rinkeby scripts/deploy-test-ens.js
```

Output:
```
No OWNER environment variable passed, setting ENS owner to provider's account: 0x4cb3fd420555a09ba98845f0b816e45cfb230983
Deploying ENSFactory...
=========
# ENSFactory:
Address: 0xcad0d7a5be19065e067353801373cac6f3a97de5
Transaction hash: 0x99aaa57f55048eab22c693f9089cc90e57bfd7f2454d5f99c3d69cf1515d2b1e
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T15:41:50.466Z
=========
====================
Deployed ENS: 0x98df287b6c145399aaa709692c8d308357bc085d
0x98df287b6c145399aaa709692c8d308357bc085d
```

Creating `aragonpm.eth` and `aragonid.eth` names:
- `aragonpm.eth`: [`0xa0702d19d3752abf884d9b76a68ab12b7cd304a004ebf9ab62c7e911af708d62`](https://rinkeby.etherscan.io/tx/0xa0702d19d3752abf884d9b76a68ab12b7cd304a004ebf9ab62c7e911af708d62)
- `aragonid.eth`: [`0x2beb33bda5c80b649932d8792947dbdd648f4048794f7769ce2d8e3efea1a100`](https://rinkeby.etherscan.io/tx/0x2beb33bda5c80b649932d8792947dbdd648f4048794f7769ce2d8e3efea1a100)


### aragonOS

Commands:
```
npx truffle compile --all
npx truffle exec --network rinkeby scripts/deploy-daofactory.js
```

Output:
```
=========
# Kernel:
Address: 0x3e79ec0f5e60d305fe8d774c2484da701e778c3d
Transaction hash: 0x6407cab7081b07b99199ea0e4fc542fff537f67fb1e54386ba1c57e72ee2e360
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T17:18:44.492Z
=========
=========
# ACL:
Address: 0x3ae935e863984ecffc980bf67bd73f56a41b94ea
Transaction hash: 0x6e407efca7e3defe0fa310a915d7e2d4fe0fffa981d06def0f7ec2986eae9dc9
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T17:18:44.465Z
=========
=========
# EVMScriptRegistryFactory:
Address: 0xce25afae0ca1fb66fc14585e575fce6e202673e6
Transaction hash: 0x1c255ae3791b133aa1fd0b105fbbe4eb88de8a0e21524b499bc96a339eb0db42
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T17:18:44.491Z
=========
=========
# DAOFactory:
Address: 0x2298d27a9b847c681d2b2c2828ab9d79013f5f1d
Transaction hash: 0xe53de8ab834af2fa757d8795ad21b742c9398fc49a6eae7ad83867da2baeb077
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T17:18:44.490Z
=========
```

### APM

Commands:
```
DAO_FACTORY=0x2298d27a9b847c681d2b2c2828ab9d79013f5f1d ENS=0x98df287b6c145399aaa709692c8d308357bc085d OWNER=0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff npx truffle exec --network rinkeby scripts/deploy-apm.js
```

Output:
```
Deploying APM...
Owner: 0xbA2bAdbbB8224e1966f33bf08d667Ddc09b720ff
ENS: 0x98df287b6c145399aaa709692c8d308357bc085d
TLD: eth (0x93cdeb708b7545dc668eb9280176169d1c33cfd8ed6f04690a0bcc88a93fc4ae)
Label: aragonpm (0x1542111b4698ac085139692eae7c6efb632a4ae2779f8686da94511ebbbff594)
=========
Deploying APM bases...
=========
# APMRegistry:
Address: 0xdda8dc1bc20e2900a5aad4cb2c64e976086c9d50
Transaction hash: 0x4ef5362b4121869d4cc16dcd668ccbb6770ff10a03ac6ffe41df1ca2341cf62a
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T17:18:44.475Z
=========
=========
# Repo:
Address: 0x9be2515f7b3a5bdf0f41bea9c3b58a61ca0a2c8c
Transaction hash: 0x69e42377f2558f916fdf626df06ee88b84def612944ab63704c9bc1be51dc65c
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T17:18:44.477Z
=========
=========
# ENSSubdomainRegistrar:
Address: 0xd02358c9788ab5aba5bd1ee32272c46d73afe65d
Transaction hash: 0xcd841911e22dad1f7e2829d4f9f35039062cd3f10a0565668565103dc38139b3
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T17:18:44.483Z
=========
Using provided DAOFactory (with EVMScripts): 0x2298d27a9b847c681d2b2c2828ab9d79013f5f1d
Deploying APMRegistryFactory...
=========
# APMRegistryFactory:
Address: 0x47c0beb14860eed8f9d83388f9b2c66fe50d848c
Transaction hash: 0x088ef5d6bdba2c319dcc2a6e3c2124a9ada4fd214f49294a3a69e224de45ba07
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T17:18:44.488Z
=========
Assigning ENS name (aragonpm.eth) to factory...
Transferring name ownership from deployer to APMRegistryFactory
Deploying APM...
=========
# APM:
Address: 0xda897630fa0f1902f99623bc00e18acd12657d4f
Transaction hash: 0x9e9184fc3a5257e5450e32f29192f79a78056271e65c19b2e0a15fb1adfaef33
=========
```

### Aragon ID


```
ENS=0x98df287b6c145399aaa709692c8d308357bc085d npx truffle exec --network rinkeby scripts/deploy-beta-aragonid.js
```

Output:
```
Deploying AragonID with ENS: 0x98df287b6c145399aaa709692c8d308357bc085d and owner: undefined
=========
# FIFSResolvingRegistrar:
Address: 0x3665e7bfd4d3254ae7796779800f5b603c43c60d
Transaction hash: 0x425bbff845d9379b35b4c59a62b0e34d1a6a1ebdc06e65522acd6e0016c00d6b
Compiler: solc@0.4.24+commit.e67f0147.Emscripten.clang (Optimizer: 10000 runs)
Compiled at: 2018-10-25T19:03:35.101Z
=========
assigning ENS name to AragonID
Transferring name ownership from deployer to AragonID
===========
Deployed AragonID: 0x3665e7bfd4d3254ae7796779800f5b603c43c60d
```

### Aragon Apps

Deployed: `finance`, `vault`, `voting`, `token-manager`
Command:
```
rm -rf build
rm -rf app/build
aragon apm publish 1.0.0 --environment rinkeby --files app/build
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

- `token-manager.aragonpm.eth` had to be republished twice as `1.0.0` had an incorrect artifact.


Final versions:

- `finance.aragonpm.eth`: `1.0.0`
- `token-manager.aragonpm.eth`: `1.0.2`
- `vault.aragonpm.eth`: `1.0.0`
- `voting.aragonpm.eth`: `1.0.0`

### DAO kits

Deployed: `democracy-kit`, `multisig-kit`
Command:
```
DAO_FACTORY=0x2298d27a9b847c681d2b2c2828ab9d79013f5f1d npm run publish:rinkeby
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `democracy-kit.aragonpm.eth`: `1.0.0`
- `multisig-kit.aragonpm.eth`: `1.0.0`

### Aragon Client

Command:
```
npm run publish:rinkeby:major
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `aragon.aragonpm.eth`: `1.0.0`
