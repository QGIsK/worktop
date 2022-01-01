# Example: Basic Deno Worker

> [View in Deno Playground](https://dash.deno.com/playground/early-hedgehog-35)

Defines two `GET` endpoints:

* `GET /` – displays a welcome message (public cache)
* `GET /greet/:name` - displays `Hello, <name>!` message, using the `:name` value provided (no cache)

## License

MIT