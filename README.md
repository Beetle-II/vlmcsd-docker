# VLMCSD for Docker

Deploy vlmcsd service on Docker container

```bash
git clone https://github.com/Wind4/vlmcsd-docker.git vlmcsd
cd vlmcsd

# Use docker-compose service
docker-compose up -d

# Show logs
docker-compose logs -f

# or docker build image
docker build -t vlmcsd .
docker run -idt -p 1688:1688 vlmcsd
```
