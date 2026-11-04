Backend engineer at Meesho in Bangalore. I work on the logistics side. I own the service that orchestrates shipments (around 15M a day), and over the last couple of years I moved a ~40TB order database from RDS to MongoDB without downtime and built a new pickup-point delivery service from scratch in Go.

Lately I've been building internal tools on Claude Code and MCP, mostly for on-call debugging and for giving engineers safe access to staging databases.

Nearly all of that is in private company repos, so there isn't much to see here. The public bits:

- [prometheus/client_golang#2005](https://github.com/prometheus/client_golang/pull/2005) (merged): promhttp panicked when instrumenting with observers that don't support exemplars
- [prometheus/client_golang#2006](https://github.com/prometheus/client_golang/pull/2006): opt-in to skip help-text validation in the registry
- [langchainjs#10935](https://github.com/langchain-ai/langchainjs/pull/10935): unhandled promise rejection on tool-call output
- [mem0#5177](https://github.com/mem0ai/mem0/pull/5177): truncate long conversations before embedding instead of crashing at 8192 tokens

I mostly write Java and Go, on Kafka, ScyllaDB and MongoDB.

[LinkedIn](https://www.linkedin.com/in/sparshal-kothari)
