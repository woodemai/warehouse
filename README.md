# Warehouse
### There are to submodules:
* Server - Spring Boot 
> I'm using Spring Security for >authentication. It's based on JWTs (access and refresh). with one secret key (HS256). It has Onion architecture.
* Client - React
> I'm using Vite as a build tool, (create-react-app is kinda deprecated). State manager MobX, in the future i'm gonna change it to Redux. It has Feature Sliced Design architecture (not completed yet, but i'm trying 🥲). Everything is writing using Typescript, so It's interfaces, types and other pretty things.
For API request i'm  using `axios`.

I'm using Docker and docker-compose to create containers and quickly deploy project.