# Lateralus Examples

A collection of example programs written in Lateralus, demonstrating language features across domains from algorithms to distributed systems.

## Categories

**Algorithms** — sorting, searching, graphs, heaps, tries, linked lists

**Audio** — synthesizers, MIDI parsing, beat sequencing

**Challenges** — Project Euler solutions, Advent of Code

**CLI Tools** — todo app, HTTP client, git log viewer, file watchdog

**Concurrency** — worker pools, pipeline stages, rate limiting

**Data Processing** — CSV/JSON/ETL pipelines, log analysis, streaming

**Demoscene** — plasma, starfield, tunnel effects

**Distributed** — Raft consensus protocol

**Embedded** — GPIO and I2C drivers

**Functional** — monads, parser combinators, transducers

**Games** — snake, tetris, 2048, game of life

**Graphics** — mandelbrot, raytracer, L-systems

**Math** — matrix operations, signal processing, statistics

**Machine Learning** — k-means, linear regression, neural networks

**Networking** — DNS resolver, HTTP/2 frames, port scanner, TCP client

**Niche** — broad collection of standalone tools:

- Parsers & formats: YAML parser, TOML parser, SQL parser, regex engine, markdown renderer, ELF parser, protocol buffers, JSON-RPC
- Storage & data: key-value store, Redis client, database engine, blockchain, compression
- Network clients: FTP, SMTP, MQTT, IRC, WebSocket, torrent, proxy server, load balancer
- Tools & UI: hex editor, text editor, terminal UI, shell, package manager, static site generator, task scheduler, cron scheduler
- Engines & VMs: chess engine, ECS, image processing, VM bytecode

**OS** — kernel syscalls, network stack, encrypted messenger, secure boot, process isolation

**Security** — Argon2, ChaCha20-Poly1305, Ed25519, certificate authority, firewall, JWT, Noise protocol, onion routing, Signal protocol, TLS 1.3, TOTP, WireGuard, X25519, zero-knowledge proofs

**Simulation** — cellular automata, fluid dynamics, n-body

**Systems** — file watcher, process manager

**Tooling** — formatter, LSP server, REPL

**Web APIs** — REST, GraphQL, WebSocket servers

## Running an Example

```
ltl run algorithms/sorting.ltl
ltl run games/tetris.ltl
ltl run security/jwt.ltl
ltl run distributed/raft_consensus.ltl
```

Every file includes a `fn main()` with built-in assertions that validate correctness.

## Contributing

See [CONTRIBUTING.md](https://github.com/bad-antics/lateralus-examples/blob/main/CONTRIBUTING.md) for guidelines. Each example should be self-contained with a `fn main()` entry point and test assertions.

## License

MIT
