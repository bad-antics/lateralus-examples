# lateralus-examples

Real-world Lateralus code examples, organised by category.

## Categories

### Algorithms
- [binary_search.ltl](algorithms/binary_search.ltl) — Binary search with generics
- [fibonacci.ltl](algorithms/fibonacci.ltl) — Fibonacci (recursive, iterative, memoised)
- [graph.ltl](algorithms/graph.ltl) — BFS, DFS, Dijkstra
- [heap.ltl](algorithms/heap.ltl) — Min-heap / priority queue
- [linked_list.ltl](algorithms/linked_list.ltl) — Singly-linked list with generics
- [sorting.ltl](algorithms/sorting.ltl) — Quicksort, mergesort, insertion sort
- [trie.ltl](algorithms/trie.ltl) — Prefix tree with autocomplete

### Challenges
- [advent_01.ltl](challenges/advent_01.ltl) — Advent of Code 2023 Day 1
- [advent_02.ltl](challenges/advent_02.ltl) — Advent of Code 2023 Day 2
- [euler_001.ltl](challenges/euler_001.ltl) — Project Euler #1
- [euler_002.ltl](challenges/euler_002.ltl) — Project Euler #2
- [euler_003.ltl](challenges/euler_003.ltl) — Project Euler #3 (largest prime factor)
- [euler_004.ltl](challenges/euler_004.ltl) — Project Euler #4 (largest palindrome product)
- [euler_005.ltl](challenges/euler_005.ltl) — Project Euler #5 (LCM 1-20)
- [euler_006.ltl](challenges/euler_006.ltl) — Project Euler #6
- [euler_007.ltl](challenges/euler_007.ltl) — Project Euler #7 (10001st prime)

### CLI
- [git_log.ltl](cli/git_log.ltl) — Pretty-print git log with pipelines
- [http_client.ltl](cli/http_client.ltl) — Minimal HTTP client
- [todo.ltl](cli/todo.ltl) — TODO/FIXME scanner
- [watchdog.ltl](cli/watchdog.ltl) — Watch directory and run command on changes

### Data Processing
- [csv_pipeline.ltl](data-processing/csv_pipeline.ltl) — CSV transform pipeline
- [etl_pipeline.ltl](data-processing/etl_pipeline.ltl) — Extract / Transform / Load
- [json_transform.ltl](data-processing/json_transform.ltl) — JSON reshaping
- [log_analyzer.ltl](data-processing/log_analyzer.ltl) — Log file analysis
- [stream_pipeline.ltl](data-processing/stream_pipeline.ltl) — Lazy infinite streams

### Web API
- [graphql_server.ltl](web-api/graphql_server.ltl) — GraphQL-style query resolver
- [rest_api.ltl](web-api/rest_api.ltl) — RESTful HTTP server
- [websocket_server.ltl](web-api/websocket_server.ltl) — WebSocket chat server

## Running an example

```bash
lateralus run algorithms/sorting.ltl
lateralus run challenges/euler_001.ltl
```
