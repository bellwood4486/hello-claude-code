# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Go project located in the traditional GOPATH structure. The repository is currently empty and ready for initial development.

## Development Commands

Since this is a Go project, the following commands will likely be useful once code is added:

```bash
# Build the project
go build

# Run tests
go test ./...

# Run tests with verbose output
go test -v ./...

# Run a specific test
go test -run TestName

# Format code
go fmt ./...

# Vet code for potential issues
go vet ./...

# Install dependencies
go mod tidy

# Run the application (once main.go exists)
go run main.go
```

## Notes

- This repository follows the traditional GOPATH structure
- Update this file with specific project architecture details once code is added
- Add any project-specific build, test, or deployment commands as needed