# docker-compose-tree

# Want to run it locally?
 - Clone the repo
 - `cd docker-compose-tree`
 - `docker-compose up`
 - Wait some seconds and... http://localhost:8080/node will be up and running!

# It's already running on Google Cloud!
 - Create node: `POST http://35.238.143.151:8080/node`
    - Request body example: `{"code":"Node", "description":"Node description", "detail": "Node detail"}`
 - Find all nodes: `GET http://35.238.143.151:8080/node`
 - Find children by parent id: `GET http://35.238.143.151:8080/node/{id}`
 - Update node: `PUT http://35.238.143.151:8080/node/`
   - Request body example: `{"id": 1, "code":"Node1", "description":"DescNode", "detail": "Some detail"}`
