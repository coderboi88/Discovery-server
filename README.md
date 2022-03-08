# Discovery-server

This is the microservice which is a internal part for movie-catalog-service.
Movie Catalog service use this to define a Eureka Server so that all the microservices can register to it and communicate between each other.

Main Project (Movie Catalog Service) - "https://github.com/coderboi88/movie-catalog-services"

Movie-info-Service - "https://github.com/coderboi88/microservices-springboot"

Rating data Service - "https://github.com/coderboi88/rating-data-service"

we use discovery server (eureka server) for the interconnection of the microservices.
All other repo except discovery server are eureka clients and register at eureka server(Discovery Server)

So to use this service we have to import all the above project also.
