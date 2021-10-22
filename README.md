# How to run details service

## Prerequisite

* Ruby 2.7

```bash
ruby details.rb 9080
```
## How to run with Docker

```bash
# Build Docker Image for this service
docker build . -t details

# Run this service on port 8081
docker run -d -p 8081:8081 --name details details 

```