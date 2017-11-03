This is _extremely_ experimental software... just a sandbox for testing at the moment. First step is to get everything working in one Ubuntu-based docker container and then docker-compose will be brought in to properly support the use case as well as allow for configuration!

```
git clone https://github.com/MatthewVita/cTAKES.git
cd cTAKES
docker build -t ctakes-rest .
docker -d -p 80:8080 ctakes-rest
```
