# Categories Microservice

Simple Go microservice for managing categories.

## Setup

```bash
# Clone
git clone https://github.com/dxddyxs/go-categories-msvc.git
cd go-categories-msvc

# Install
go mod download

# Run
go run ./cmd/api/
```

## API

- `GET /categories/` - List categories
- `POST /categories/` - Create category
- `GET /healthy` - Health check

## Technologies

- Go 1.24
- Gin Framework

## Requirements

- Go 1.24 or higher
- Git

## Project Structure

```
.
├── cmd/
│   └── api/           # Application entry point
│       ├── controllers/
│       ├── main.go
│       └── routes.go
├── internal/
│   ├── entities/      # Domain entities
│   ├── repositories/  # Repository implementations
│   └── use-cases/     # Application use cases
└── go.mod
```

## Running Tests

```bash
go test ./...
```

## Contribution

1. Fork the project
2. Create a branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
