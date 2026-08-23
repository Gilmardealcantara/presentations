# Architecting Observability in Go

**GopherCon LATAM 2026** — Gilmar Alcantara (Hotmart)

## About

This talk covers how to architect observability in Go microservices, focusing on context propagation, structured logging, and telemetry strategy. It's based on a real-world observability migration (Datadog → New Relic) at Hotmart/Teachable.

## Key Topics

- Why observability in Go is different from auto-instrumented runtimes (Java, Ruby)
- Using `context.Context` as the backbone of distributed tracing
- Structured logging with `slog` and automatic trace correlation
- Building a shared telemetry library for consistent instrumentation across services
- HTTP middleware patterns for clean, layered observability
- Manual instrumentation for databases, SQS consumers, and HTTP clients
- Governance and sustainability of observability standards in polyglot environments
- The future: OpenTelemetry compile-time instrumentation (`otelc`)

## Running

```bash
npm install
npm run dev
```

## Exporting

```bash
npm run export
```

## Built With

- [Slidev](https://sli.dev/) — Presentation slides for developers
