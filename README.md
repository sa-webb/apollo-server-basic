# Apollo-Server Intro Tutorial

Schema - defines the structure of data that clients can query.
Resolvers - tell Apollo Server how to fetch the data associated with a particular type.

Navigate to <http://localhost:4000/>

Paste this query into GraphQL Playground.

query GetBooks {
  books {
    title
    author
  }
}
