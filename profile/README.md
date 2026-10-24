# Miyo Explorer

Building open-source tools and infrastructure for the Stellar ecosystem.

## About Miyo Explorer

Miyo Explorer builds open-source developer tools and infrastructure for the
Stellar ecosystem. Our work emphasises JSON-RPC endpoint diagnostics,
developer experience, and network reliability — the practical problems that
developers hit when their tooling breaks against a specific RPC provider.

We believe diagnostics should be deterministic, reproducible, and safe to run
in CI. Every tool we ship is designed so that a failure can be traced to a
specific cause rather than an ambiguous "the endpoint is down".

## Featured Project

### [Miyo RPC Labs](https://github.com/Miyo-explore/miyo-rpc-labs)

A lightweight Rust CLI for diagnosing, testing, and comparing Stellar
JSON-RPC endpoints. It runs a deterministic set of checks against any
Soroban-compatible RPC URL and produces a structured report that classifies
which capabilities an endpoint supports, which return errors, and which could
not be tested.

- **Repository:** https://github.com/Miyo-explore/miyo-rpc-labs
- **Documentation:** see the project
  [README](https://github.com/Miyo-explore/miyo-rpc-labs#readme)
- **License:** Apache License 2.0

Verified capabilities include HTTP connectivity checks, JSON-RPC method
checks (`getHealth`, `getNetwork`, `getLatestLedger`, `getVersionInfo`),
arbitrary JSON-RPC method probing with custom parameters, network identity
validation, repeated-run latency statistics, cross-endpoint comparison,
multi-endpoint batch diagnosis, and human-readable or JSON output. See the
project README for the current feature list and documented limitations.

## Our Focus

- **Stellar developer tooling** — CLI utilities that make protocol-level
  problems easier to reproduce and report.
- **JSON-RPC endpoint diagnostics** — deterministic checks that classify
  endpoint behaviour instead of guessing.
- **Network reliability and observability** — reports that are stable enough
  to gate CI pipelines on.
- **Open-source collaboration** — focused, well-scoped issues and pull
  requests that welcome external contributors.

These are areas of active focus, not a claim that every capability is already
implemented.

## Contributing

Contributions are welcome. Start by exploring the repositories, reporting
bugs, suggesting improvements, or submitting focused pull requests.

- [Miyo RPC Labs contribution guide](https://github.com/Miyo-explore/miyo-rpc-labs/blob/main/CONTRIBUTING.md)
- [Open issues](https://github.com/Miyo-explore/miyo-rpc-labs/issues)

Please keep pull requests focused on a single issue, include regression tests
for behaviour changes, and run the repository's formatting, lint, and test
checks before opening a PR.

## License

- **Miyo RPC Labs** — Apache License 2.0
  ([LICENSE](https://github.com/Miyo-explore/miyo-rpc-labs/blob/main/LICENSE))

## Community

- Organization: https://github.com/Miyo-explore
- Bug reports and feature requests belong in the relevant repository's issue
  tracker.
