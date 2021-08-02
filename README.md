# BitrielSwap Subgraph

## To setup and deploy

For any of the subgraph: `exchange` as `[subgraph]`

1. Run the `yarn run codegen:[subgraph]` command to prepare the TypeScript sources for the GraphQL (src/types/*).

2. Run the `yarn run build:[subgraph]` command to build the subgraph, and check compilation errors before deploying.

3. Run `graph auth https://api.thegraph.com/deploy/ '<ACCESS_TOKEN>'`

4. Deploy via `yarn run deploy:[subgraph]`.
