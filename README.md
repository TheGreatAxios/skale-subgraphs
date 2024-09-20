# SKALE Subgraphs

## Installation

1. Fork and `git clone git@github.com:TheGreatAxios/skale-subgraphs.git`
2. npm install

## Deploying Subgraphs

1. To deploy token subgraphs, run `npx goldsky subgraph deploy tokens/1.0.0 --from-abi tokens.json`

### Notes
1. You may want to update blocks. For how the CLI is designed would probably write a small util script to generate the config on the fly
2. You have to manually add tokens (for now) haven't tried doing a * wildcard index
