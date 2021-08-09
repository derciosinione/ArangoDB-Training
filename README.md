# ArangoDB

docker run -it --name arangodb -e ARANGO_ROOT_PASSWORD='snirdb@123' -p 8529:8529 arangodb

docker run --name arangodb -p 8529:8529 -e ARANGO_RANDOM_ROOT_PASSWORD=1 arangodb