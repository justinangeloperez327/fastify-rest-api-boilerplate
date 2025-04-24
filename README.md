# Fastify REST API

This project is a REST API built using [Fastify](https://www.fastify.io/), a fast and low-overhead web framework for Node.js.

## Features

- High-performance routing
- JSON schema validation
- Easy-to-use plugin system
- Built-in support for async/await

## Installation

```bash
git clone https://github.com/justinangeloperez327@gmail.com/fastify-rest-api-boilerplate.git
cd fastify-rest-api
npm install
```

## Usage

Start the server:

```bash
npm start
```

The server will run on `http://localhost:3000`.

## Endpoints

### GET /health

Returns the health status of the API.

```json
{
  "status": "ok"
}
```

### POST /data

Accepts JSON payload and processes it.

#### Request

```json
{
  "key": "value"
}
```

#### Response

```json
{
  "message": "Data received successfully"
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
