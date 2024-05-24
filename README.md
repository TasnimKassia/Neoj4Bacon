# Neoj4Bacon
EECS3311-Six Degrees of Kevin Bacon

- Using Neo4j to compute relationships between actors and movies, illustrating the connections leading to Kevin Bacon. The project includes functionality to add actors and movies, establish relationships, and compute paths (degrees of separation) between actors. The backend is implemented in Java, and the application can be interacted with via endpoints using Postman. 

- Make sure java version is 1.8 while running

- Check the port number whether its already in bind or not

- Go on postman, Enter: http://localhost:8080/api/v1/computeBaconPath
or any other end point such as addActor,addMovie,getRelationship,computeBaconNumber, etc

- Add data as json in the raw section- should be something like:

{ 
  "actorId":"1", "movieId":"2"
}

or name for name while adding actors or movies
