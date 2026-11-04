Senior backend engineer (SDE III) at [Meesho](https://www.meesho.com) in Bangalore. I design and run the event-driven systems behind Meesho's logistics platform, and I build AI tooling for engineers on top of Claude Code and MCP.

Most of my work lives in private repositories, so here is a short summary.

### Work

- Primary owner of the shipment orchestration service: 15M shipments and ~500M events a day at 99.99% availability, on Kafka, ScyllaDB, MongoDB and Redis
- Led the 0-to-1 build of Self-Pickup, a pickup-point delivery mode spanning 19+ services, and wrote its core service in Go from scratch
- Migrated a ~40TB order database from RDS to MongoDB with zero downtime, using CDC and dual writes
- Built an MCP-based on-call agent that cut incident diagnosis from over an hour to under 5 minutes, and a staging-database MCP server used daily by 200+ engineers

### Writing

- [What if your AI coding agents ran like Kubernetes?](https://medium.com/@sparshalkothari2014/what-if-your-ai-coding-agents-ran-like-kubernetes-88c252c81d51) (May 2026). Coordinating many specialised Claude Code sessions using ideas from Kubernetes: service discovery, routing, the context window as a resource, and where the analogy breaks down

### Open source

- prometheus/client_golang [#2005](https://github.com/prometheus/client_golang/pull/2005) (merged): fix a panic in promhttp when instrumenting with observers that don't support exemplars
- prometheus/client_golang [#2006](https://github.com/prometheus/client_golang/pull/2006): opt-in to skip help-text validation in the registry
- langchain-ai/langchainjs [#10935](https://github.com/langchain-ai/langchainjs/pull/10935): fix an unhandled promise rejection on tool-call output
- mem0ai/mem0 [#5177](https://github.com/mem0ai/mem0/pull/5177): truncate long conversations before embedding instead of failing at the 8192-token limit
- claude-code-session-bridge [#5](https://github.com/PatilShreyas/claude-code-session-bridge/pull/5): give multiple sessions in the same repo independent bridges

### Stack

Java, Go, Python, Kafka, ScyllaDB, MongoDB, Redis, PostgreSQL, Kubernetes, AWS, GCP

[LinkedIn](https://www.linkedin.com/in/sparshal-kothari) · [Medium](https://medium.com/@sparshalkothari2014) · sparshalkothari2014@gmail.com
