# Writing RESTful APIs Using gRPC-Gateway

gRPConf India 2025, 19th November 2025

- Rajiv Ranjan Singh

## About

The protoc plugin that generates a reverse proxy in front of a gRPC service, the ways
to map HTTP onto it, and a hello world serving both protocols from a single protobuf
definition — with the OpenAPI documentation that comes out of the same source for free.

## Slides

[`main.slide`](main.slide) — Go present format. Run locally with `present -http=:3999`,
or view the published deck at https://iamrajiv.github.io/grpconf-india-2025/.

## Examples

[`examples`](examples) — `hello` for the basic service, `mapping` for the four ways to
bind HTTP routes, and `advanced` for custom URLs, streaming, and error handling.

## Recording

[Watch on YouTube](https://www.youtube.com/watch?v=hWhmhvje-pE)

## License

[MIT](LICENSE)
