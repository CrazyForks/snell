# snell

An encrypted proxy service program

## Highlights

* Extreme performance.
* Single binary with zero dependency.
* A wizard to help you start.
* Traffic obfuscating is embedded. (HTTP & TLS)
* Proxy server will report remote errors to client if encounters. Clients may choose countermeasures for different scenarios.
* Protocol is ready for multiple users ACL. (No implementation yet)
* Protocol is ready for cipher/version auto-negotiation. (No implementation yet)

## Quickstart

1. Download the binary from the [Release page](https://github.com/surge-networks/snell/releases/latest).
2. Decompress and execute the binary. A wizard will guide you to generate a new config.
3. Re-execute the binary to start service.
4. Add a proxy line in Surge  (The latest beta version is required)

`Proxy = snell, [SERVER ADDRESS], [GENERATED PORT], psk=[GENERATED PSK], obfs=http`

## Opens Source

We haven't decided whether to open source the project for complicated reasons.
