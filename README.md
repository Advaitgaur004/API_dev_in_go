# API_dev_in_go

A robust REST API implementation in Go, featuring clean error handling and JSON response utilities.

## Features

- Clean JSON response handling
- Standardized error responses
- Content-Type header management
- HTTP status code support

## Usage

### JSON Response Handling

#### Error Handling

```go
// Send error response
WriteError(w, http.StatusBadRequest, err)
```

#### Response Format

**Success Response**

```json
{
    "key": "value"
}
```

**Error Response**

```json
{
    "error": "error message"
}
```

### Technical Details

- Content-Type: application/json
- Response encoding: UTF-8
- Built with standard Go libraries

### Getting Started

1. Clone the repository

    ```sh
    git clone https://github.com/yourusername/API_dev_in_go.git
    ```

2. Navigate to project directory

    ```sh
    cd API_dev_in_go
    ```

3. Run the project

    ```sh
    go run main.go
    ```

## Contributing

Contributions are welcome! Feel free to submit pull requests and report issues.
