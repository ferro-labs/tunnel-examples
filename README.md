# tunnel-examples

Standalone examples demonstrating how to use [FerroTunnel](https://github.com/ferro-labs/ferrotunnel) in your Rust applications.

## Directory Structure

```
tunnel-examples/
├── basic/              # Getting started
│   ├── embedded_server.rs
│   ├── embedded_client.rs
│   └── auto_reconnect.rs
├── plugins/            # Plugin development
│   ├── custom_plugin.rs
│   ├── header_filter.rs
│   ├── ip_blocklist.rs
│   └── plugin_chain.rs
├── advanced/           # TLS and multi-tunnel
│   ├── tls_config.rs
│   ├── multi_tunnel.rs
│   ├── http2_connection_pooling.rs
│   └── custom_pool_config.rs
├── operational/        # Server lifecycle and observability
│   ├── server_graceful_shutdown.rs
│   └── server_observability.rs
└── scenarios/          # Common usage scenarios
    ├── expose_local_dev.rs
    ├── receive_webhooks_locally.rs
    └── websocket_tunnel.rs
```

## Running Examples

```bash
# Basic
cargo run --example embedded_server
cargo run --example embedded_client
cargo run --example auto_reconnect

# Plugins
cargo run --example custom_plugin
cargo run --example header_filter
cargo run --example ip_blocklist
cargo run --example plugin_chain

# Advanced
cargo run --example tls_config
cargo run --example multi_tunnel
cargo run --example http2_connection_pooling
cargo run --example custom_pool_config

# Operational
cargo run --example server_graceful_shutdown
cargo run --example server_observability

# Scenarios
cargo run --example expose_local_dev
cargo run --example receive_webhooks_locally
cargo run --example websocket_tunnel
```

## License

Licensed under either of [MIT](LICENSE-MIT) or [Apache-2.0](LICENSE-APACHE) at your option.
