# Logstash with Docker

### Start container
1. Rename `env.example` file to `.env`

2. Update env file with Elastic Host and Credentials. Also modify exposed ports for Totem Beats services

3. Start container
```
docker compose up -d
```