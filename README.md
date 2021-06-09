# KILT DID substrate seminar demo

<p align="center">
  <img src="docs/media/kilt.png">
</p>

This repo contains the code used for the live demo at the [01/06/2021 Substrate Seminar](https://www.crowdcast.io/e/substrate-seminar/40).

> The code and the SDK in the demo were using a version of the KILT blockchain that is different from the one currently publicly depoloyed, hence using the default URL will most likely result in an unhandled failure by the demo script. To run the exact same node version that was used during the demo, please refer to the commit [f0fbbc86ada7a273a3a6af740afc963bdb8f16ab](https://github.com/KILTprotocol/mashnet-node/commit/f0fbbc86ada7a273a3a6af740afc963bdb8f16ab) of the [KILT mashnet node repo](https://github.com/KILTprotocol/mashnet-node), and configure the demo script to use the right node endpoint.

## How to run

Install the needed dependencies with `yarn install` and then run the demo script with `yarn run demo`.