# Warehouse

### Two Submodules:

* **Server - Spring Boot:**
  - I'm using Spring Security for authentication, based on JWTs (access and refresh) with one secret key (HS256). The app follows the Onion architecture.

* **Client - React:**
  - I'm using Vite as a build tool (create-react-app is somewhat deprecated). The state manager is MobX, with plans to switch to Redux in the future. The project follows the Feature Sliced Design architecture, although it's not completed yet. Everything is written using TypeScript, incorporating interfaces, types, and other helpful features. For API requests, I'm using `axios`.

I'm utilizing Docker and docker-compose to create containers and quickly deploy the project.