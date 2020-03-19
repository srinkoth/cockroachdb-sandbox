# cockroachdb-sandbox

This simple docker-compose.yml will setup a three node insecure [CockroachDB](https://www.cockroachlabs.com/product/) sandbox cluster for development and testing. 

## Setup

You will need Docker and Docker Compose installed on your machine. Instructions [here](https://docs.docker.com/install/).

```bash
git clone git@github.com:vipertoothlabs/cockroachdb-sandbox.git
cd cockroachdb-sandbox
docker-compose up -d
```

Run
```bash
docker-compose logs -f
```
to see the logs. 



