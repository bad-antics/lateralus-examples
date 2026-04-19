# lateralus-examples

Real-world example programs written in the [Lateralus](https://github.com/bad-antics/lateralus-lang) programming language.

## Categories

| Category | Files | Description |
|----------|-------|-------------|
| `basics/` | 3 | Hello world, fizzbuzz, fibonacci |
| `cli/` | 4 | Argument parsing, file tools, progress bars, interactive prompts |
| `data/` | 3 | JSON, CSV, SQLite |
| `web/` | 4 | HTTP server, REST API, WebSocket, static file server |
| `concurrency/` | 3 | Threads, channels, async tasks |
| `games/` | 4 | Snake, tetris, pong, dungeon |
| `ml/` | 3 | Linear regression, neural net, k-means |
| `security/` | 3 | AES, RSA, JWT |
| `audio/` | 3 | Software synth, beat sequencer, **MIDI parser** |
| `graphics/` | 3 | Ray tracer, L-System fractals, **Mandelbrot set** |
| `embedded/` | 2 | RP2040 GPIO driver, I2C driver |
| `tooling/` | 3 | LSP server skeleton, source formatter, **REPL** |
| `simulation/` | 3 | Cellular automata, N-body, **2D fluid (Navier-Stokes)** |
| `networking/` | 1 | HTTP/2 frame parser/encoder |
| `demoscene/` | 3 | Terminal plasma, tunnel effect, **3D starfield** |

**Total: 66 `.ltl` files**

## Running

```bash
ltl run audio/midi_parser.ltl
ltl run graphics/mandelbrot.ltl
ltl run simulation/fluid.ltl
ltl run demoscene/starfield.ltl
ltl run tooling/repl.ltl
```

## Contributing

All examples follow these conventions:
- `fn main()` or `async fn main()` entry point
- `|>` pipelines where natural
- Structs with `impl` blocks and methods
- Assertions to verify correctness
- Comments explaining key concepts
