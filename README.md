# test-task
Test task for full-stack developer position

Create an application which:

1. Connects to Twitter Streaming API and watches for all the tweets matching the keyword "bitcoin"

2. Exposes a GraphQL endpoint where Customer can query the following data:
  * all tweets paginated
  * filtered by user
  * filtered by language

Prerequisites:

  * Code should be strictly typed with TypeScript
  * There should not be any database, all data has to be stored in-memory
  * Configuration and security credentials should not be stored in code.

Nice-to-haves:
  * A simple front-end website using any UI library to make queries
  * A Websocket subscription using GraphQL Subscription type to update the front-end in real-time
