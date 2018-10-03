#Build dev
 - docker build -f Dockerfile.dev .
---
#To run test in split terminal
 - docker exec -it id_of_container npm run test
---
#Build prod
  docker build . 

---
#Prod usage
docker run -p 8080:80 id_of_container