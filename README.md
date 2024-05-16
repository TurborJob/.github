# SetUpTurborJob
A document help you set up project

## Front end
  1. You clone TurborJobFrontEndClient
  2. You using Visual studio code
  3. You using node 18
  4. You run "npm i" or "yarn install" in cmd

## Back end
 1. You clone TurborJobBackEnd
 2. You using IntelliJ
 3. You using Java 17, Gradle 7.4.2, Groovy 3.0.9
 4. You using Docker and Docker compose
 5. cd /core
 6. Run command "docker compose up" to set up container and enviromemt
 7. Using DBear and connect PostgreSQL in file docker-compose.yml
 8. Create some schema : account, history, job, token.
 9. Add enviroment in IntelliJ: --spring.profiles.active=dev (core) run by IntelliJ or run cmd: "gradle bootrun -Dspring.profiles.active=dev"

