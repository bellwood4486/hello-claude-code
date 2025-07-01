# hello-claude-code

A Go project for exploring and testing Claude Code functionality.

## Overview

This repository demonstrates the capabilities of Claude Code (claude.ai/code) in a Go development environment using the traditional GOPATH structure.

## Getting Started

### Prerequisites

- Go 1.x or later installed
- Git for version control

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/bellwood4486/hello-claude-code.git
   cd hello-claude-code
   ```

2. Install dependencies (once added):
   ```bash
   go mod tidy
   ```

## Development

### Build

```bash
go build
```

### Run Tests

```bash
# Run all tests
go test ./...

# Run tests with verbose output
go test -v ./...

# Run a specific test
go test -run TestName
```

### Code Quality

```bash
# Format code
go fmt ./...

# Vet code for potential issues
go vet ./...
```

### Run Application

Once a main.go file is created:

```bash
go run main.go
```

## Project Structure

This project follows the traditional GOPATH structure. More details will be added as the project evolves.

## Contributing

1. Create a feature branch
2. Make your changes
3. Run tests and ensure code quality
4. Submit a pull request

## License

[Add license information]