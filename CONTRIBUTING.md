# Contributing to Lateralus Examples

Thanks for contributing! Every `.ltl` file you add helps the Lateralus ecosystem grow. 🚀

## How to Contribute

1. **Fork** this repo
2. **Create** your example `.ltl` file in the appropriate folder
3. **Follow** the format below
4. **Open** a pull request

## File Format

Every example should start with a comment header:

```lateralus
// example_name.ltl — Brief description
// ──────────────────────────────────────────────
// What: What this example demonstrates
// Concepts: pipeline, pattern matching, etc.
// Run: lateralus run category/example_name.ltl
```

## Guidelines

- ✅ **Real-world, useful code** — not just "Hello World"
- ✅ **Comments explaining key concepts** — teach as you show
- ✅ **Runnable** — should work with `lateralus run`
- ✅ **Self-contained** — no external dependencies if possible
- ✅ **Demonstrate Lateralus features** — pipelines, pattern matching, structs, etc.
- ❌ No generated/AI-written filler code
- ❌ No copyrighted code from other sources

## Folder Structure

| Folder | For |
|--------|-----|
| `algorithms/` | Classic algorithms and data structures |
| `data-processing/` | Parsing, transforming, aggregating data |
| `cli/` | Command-line tools and utilities |
| `web-api/` | HTTP servers, REST APIs, middleware |
| `challenges/` | Coding challenges (Euler, Advent of Code, etc.) |

Want a new category? Propose it in your PR.

## Example Template

```lateralus
// my_example.ltl — What it does in one line
// ──────────────────────────────────────────────
// What: Longer description
// Concepts: list the Lateralus features used
// Run: lateralus run category/my_example.ltl

// Your code here...

fn main() {
    // Demonstrate the concept
    // Print results so it's clear what happened
}

main()
```

## License

By submitting a PR, you agree that your code is licensed under MIT.
