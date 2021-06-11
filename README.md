# KILT DID substrate seminar demo

<p align="center">
  <img src="docs/media/kilt.png">
</p>

This repo contains the code used for the live demo at the [01/06/2021 Substrate Seminar](https://www.crowdcast.io/e/substrate-seminar/40).

## How to spin up a KILT node

At the time of the demo, the code and the SDK in the demo were using a version of the KILT blockchain that is different from the one currently publickly deployed. For this reason, for the demo to work properly, a local blockchain node with the same version used in the demo must be started.

To download the Docker image and start the node, please [install Docker](https://docs.docker.com/engine/install/) and then run the following:

```bash
docker run -p 50000:50000 --rm kiltprotocol/mashnet-node:f0fbbc8 --dev --tmp --ws-port 50000 --ws-external
```

The command will pull and start a Docker container containing the right blockchain node version ([f0fbbc86ada7a273a3a6af740afc963bdb8f16ab](https://github.com/KILTprotocol/mashnet-node/commit/f0fbbc86ada7a273a3a6af740afc963bdb8f16ab)) and expose the Websocket port `50000`.

## How to run the demo code

Install the needed dependencies with `yarn install` and then run the demo script with `yarn run demo`.