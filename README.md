# Microservices

This repo is meant to be a training ground for building microservices. Since the idea of microservices is that they can be different languages, I will not restrict this repo to any languages.

The following technologies are currently being explored in this repository...

- Golang
- gRPC
- go-micro
- Docker
- Kubernetes

## Current microservices planned

The system will be an internal package and inventory management system that will include...

1. Consignment Service: 
- For consigning the package to be transferred
2. User Service:
- For user related actions
3. Package Service:
- For the packages being consigned

## Services

### Consignment Service

This service will be able to add a consignment to a list of consignments.

The consignment service will also be able to tell whether the current consignment has been created.

#### Methods

CreateConsignment()
- Currently, creates a new consignment based on the file `consignment.json`
-- This is based on the proto file and its defined values

GetConsignment()
- Currently, gets and prints to the console the current list of consignments