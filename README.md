# ANS Subgraph

This Subgraph sources events from the ANS contracts. This includes the ANS registry, the Auction Registrar, and any resolvers that are created and linked to domains. The resolvers are added through dynamic data sources. More information on all of this can be found at [The Graph Documentation](https://thegraph.com/docs/developer/quick-start/).

# Example Queries

Here we have example queries, so that you don't have to type them in yourself eachtime in the graphiql playground:

```graphql
{
  domains {
    id
    labelName
    labelhash
    parent {
      id
    }
    resolver {
      id
    }
    ttl
  }
  resolvers {
    id
   
      }
    }

```
