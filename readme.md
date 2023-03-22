# Steps to Run a Full Node

## Download Required Files

Download bonerium and bonerium.json from https://github.com/boneriumtech/node

```bash
wget https://raw.githubusercontent.com/boneriumtech/node/master/bonerium
wget https://raw.githubusercontent.com/boneriumtech/node/master/bonerium.json
```

## Set node permissions

```bash
chmod +x ./bonerium
```

## Run the Nodes

```bash
./bonerium server --data-dir=./data/ --chain=./bonerium.json
```

# Connect to the node

The node will put up a webservice and json rpc on 0.0.0.0:8545 by default

```
http://127.0.0.1:8545
ws://127.0.0.1:8545/ws
```

Please refer to polygon edge doucmentation for more options https://wiki.polygon.technology/docs/edge/get-started/cli-commands#server-flags
