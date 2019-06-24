# elasticsearch-cli
Command line tool to use elasticsearch without having to know all the complicated curl get and post requests.

## USAGE

`elastic [alias|cluster|index|master|node|plugin|reindex|search|shard] command parameters`

## EXAMPLES

- `elastic cluster health`                    Display cluster health information
- `elastic allocation explain`                Display problems while allocating shards
- `elastic shard allocation none`             Disable shard allocation before updating a node
- `elastic shard allocation all`              Enable shard allocation

## LICENSE

MIT License

Copyright (c) 2019 [Holger Arndt](https://holger-arndt.com)
