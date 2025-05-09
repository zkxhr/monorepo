# zkxhr: Zenith Kit X Hypermedia Relay

A powerful, extensible chat communication platform with a rich API surface.  
Built as a full-stack monorepo: TypeScript client + Rust server.

## Overview

`zkxhr` is a API-rich, developer-friendly chat platform focused on modularity and extensibility.

- Real-time messaging (WebSocket)
- TypeScript reference client for frontend and bots
- Rust-based high-performance server

## Getting Started

### Prerequisites

1. Use [mise](https://mise.jdx.dev).  
    Don't have mise? Check `mise.toml` and install them manually.
2. Install yarn: `npm i -g corepack && corepack enable && corepack install -g yarn`.

### Build and Run

#### 1. Clone the repository
```bash
git clone https://github.com/your-org/zkxhr.git
cd zkxhr
````

#### 2. Run the server

```bash
cargo run
```

#### 3. Start the client (in another terminal)

```bash
yarn start
```

## Documentation

* [API Reference (WIP)](docs/api.md)

## License

MIT © 2025-present
