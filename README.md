# Apollo-Server Intro Tutorial

Schema - defines the structure of data that clients can query. \\
Resolvers - tell Apollo Server how to fetch the data associated with a particular type.

1. `npm install` or `yarn install` to install dependencies.
2. `<package_manager> start` to start the server.
3. Navigate to <http://localhost:4000>
4. Paste this query into GraphQL Playground to view the data.

query GetBooks {
  books {
    title
    author
  }
}
