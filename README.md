# MediCare 2.O

> MediCare 2.O is a decentralized application workspace where the product interface and smart-contract layer live together.

## The Story

MediCare 2.O starts with a simple goal: connect a user-facing product experience with protocol logic that can be inspected and evolved. Its shape tells the same story: the product interface and the protocol or smart-contract layer live close enough together that a maintainer can see the project as a whole before diving into individual folders.

## What It Includes

- A user-facing surface for the product, demo, dashboard, or static experience.
- Protocol or smart-contract files that anchor the Web3 side of the project.

## How It Is Put Together

| Path | Role |
| --- | --- |
| `.gitattributes` | project file or folder |
| `.gitignore` | ignored local, dependency, and build files |
| `contracts` | smart-contract source |
| `hardhat.config.js` | JavaScript source |
| `package-lock.json` | locked dependency versions |
| `package.json` | Node package scripts and dependencies |
| `public` | static assets and presentation files |
| `scripts` | automation or deployment scripts |
| `src` | project file or folder |
| `test` | project file or folder |

## Local Development

```bash
git clone https://github.com/ENZOMOTIVE/MediCare-2.O.git
cd MediCare-2.O
```

```bash
npm install
npm start
```

## Command Surface

| Area | Commands |
| --- | --- |
| `package.json` | `start`, `build`, `test`, `eject` |
| Smart contracts | `npx hardhat compile`, `npx hardhat test` |

## Configuration

- Keep wallet private keys, RPC URLs, mnemonics, and contract secrets outside version control.

## Quality Checks

- From the repository root, run `npm test`.
- From the repository root, run `npm run build`.
- Run the Hardhat test suite before deploying or changing contract behavior.

## Where To Take It Next

- Add screenshots or a short user flow so visitors can see the interface before running it.
- Record supported networks, deployment addresses, and contract verification steps when they exist.
- Keep setup commands current whenever dependencies, scripts, or deployment targets change.
- Record important product decisions here so the repository keeps its story as the code evolves.

## Project Metadata

| Field | Details |
| --- | --- |
| Repository | `ENZOMOTIVE/MediCare-2.O` |
| Categories | `Full Stack`, `Protocol` |
| Primary stack | React, Hardhat, Node.js, JavaScript, Solidity, HTML, CSS |


## License

No license file is currently committed. Add one before distributing this project publicly.
