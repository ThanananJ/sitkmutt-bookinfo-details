# How to run details service

## How to run

* Ruby 2.7

```bash
ruby details.rb 8081
```
## How to run with Docker

```bash
# Build Docker Image for Detail service
docker build -t details .

# Run details service on port 8081
docker run -d --name details -p 8081:8081 details
```
* Test with path `/details/{id}` and `/health`

```