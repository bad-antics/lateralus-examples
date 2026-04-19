# lateralus-examples

> Real-world Lateralus code examples, categorised by domain.

## Categories

| Category | Files | Description |
|---|---|---|
| [algorithms](algorithms/) | 5 | sorting, searching, graph algorithms |
| [challenges](challenges/) | 5 | competitive-programming style problems |
| [cli](cli/) | 4 | command-line tool examples |
| [data-processing](data-processing/) | 4 | CSV, JSON, streaming data |
| [web-api](web-api/) | 5 | REST API, middleware, auth |
| [networking](networking/) | 3 | TCP client, port scanner, DNS resolver |
| [concurrency](concurrency/) | 3 | worker pool, pipeline stages, rate limiter |
| [systems](systems/) | 2 | file watcher, process manager/supervisor |
| [math](math/) | 3 | matrix ops, statistics, FFT/signal processing |
| [functional](functional/) | 3 | monads, parser combinators, transducers |
| [games](games/) | 4 | Snake, Tetris, Game of Life, 2048 |
| [ml](ml/) | 3 | linear regression, k-means, neural network |
| [security](security/) | 4 | hashing/HMAC, JWT, rate limiting, input sanitisation |

**Total: 53 `.ltl` files across 13 categories**

## Highlights

### Games
```lateralus
// Spawn a glider in Conway's Game of Life
let mut grid = Grid.new(40, 20)
grid = glider(grid, 1, 1)
for _ in range(0, 200) { grid = grid.step(); render(grid) }
```

### ML
```lateralus
// Fit a linear model and check R²
let model = LinearRegression.fit(x, y)
print("R² = ${model.r_squared(x, y):.4}")
```

### Security
```lateralus
// Sign and verify a JWT
let token   = encode_jwt(claims, secret)
let decoded = decode_jwt(token, secret)?
assert(decoded.sub == "user:42")
```

### Concurrency
```lateralus
// Bounded worker pool
let pool = WorkerPool.new(8)
let results = pool.map(jobs, process_job).await
```

## Running Examples

```bash
ltl run games/snake.ltl
ltl run ml/linear_regression.ltl
ltl run security/hashing.ltl
ltl run networking/port_scanner.ltl
```

## Contributing

Pick any `.ltl` example, study the style, and open a PR with a new one!
See [lateralus-lang](https://github.com/bad-antics/lateralus-lang) for language reference.
