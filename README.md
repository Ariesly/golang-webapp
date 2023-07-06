# My Golang App

This is a simple web application written in Go. It serves as a basic template for building and deploying a Go-based web application using Docker and Kubernetes.

## Features

- Simple HTTP endpoints
- Dockerized for containerization
- Helm chart for easy deployment to Kubernetes

## Prerequisites

- Go 1.16 or later
- Docker
- Kubernetes
- Helm 3

## Local Development

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the application locally using the command `go run main.go`.

## Building the Docker Image

1. Navigate to the project directory.
2. Build the Docker image using the command `docker build -t my-golang-app .`.

## Deploying to Kubernetes

1. Navigate to the project directory.
2. Install the Helm chart using the command `helm install my-golang-app ./my-golang-app`.

## Contributing

Contributions are welcome. Please submit a pull request or create an issue to discuss the changes you want to make.

## License

This project is licensed under the MIT License. See the LICENSE file for details.