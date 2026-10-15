# REQUEST: New membership for atharvamhaske

### GitHub Username

atharvamhaske

### Requirements

- [x] I have reviewed the community membership guidelines (https://github.com/open-telemetry/community/blob/main/guides/contributor/membership.md)
- [x] I have enabled 2FA on my GitHub account. See https://github.com/settings/security
- [x] I have subscribed to the [Slack channel](https://cloud-native.slack.com/archives/CJFCJHG4Q) (use https://slack.cncf.io/ to get an invite)
- [x] I am actively contributing to 1 or more OpenTelemetry subprojects
- [x] I have two sponsors that meet the sponsor requirements listed in the community membership guidelines. Among other requirements, sponsors must be approvers or maintainers of at least one repository in the organization and not both affiliated with the same company
- [x] I have spoken to my sponsors ahead of this application, and they have agreed to sponsor my application

### Sponsors

- @darccio
- @amazingakai

Each sponsor should reply to this issue with the comment "*I support*".

### List of contributions to the OpenTelemetry project

**PRs authored, opentelemetry-go-compile-instrumentation (merged):**

- open-telemetry/opentelemetry-go-compile-instrumentation#1451 — fix: Fail Builds for Invalid Append Arguments
- open-telemetry/opentelemetry-go-compile-instrumentation#1423 — fix(pkg/runtime): add telemetry.sdk resource attributes
- open-telemetry/opentelemetry-go-compile-instrumentation#1421 — refactor(instrumentation/redis): pre-size request attribute slice
- open-telemetry/opentelemetry-go-compile-instrumentation#1407 — fix(instrumentation/openai): set error.type on streaming abort
- open-telemetry/opentelemetry-go-compile-instrumentation#1402 — docs(adr): migrate instrumentations to contrib
- open-telemetry/opentelemetry-go-compile-instrumentation#1369 — fix(instrumentation/redis): skip Conn hook after go-redis v9.9.0
- open-telemetry/opentelemetry-go-compile-instrumentation#1349 — feat(instrumentation/amqp): add rabbitmq/amqp091-go producer and consumer spans
- open-telemetry/opentelemetry-go-compile-instrumentation#1342 — chore(ci): add .tools/go.mod to lint-actionlint path filter
- open-telemetry/opentelemetry-go-compile-instrumentation#1340 — feat(instrumentation/elastic): add olivere/elastic v7 client spans
- open-telemetry/opentelemetry-go-compile-instrumentation#1339 — feat(instrumentation/zap): inject trace_id and span_id into zap logs
- open-telemetry/opentelemetry-go-compile-instrumentation#1330 — feat(instrumentation/anthropic): instrument POST /v1/messages/count_tokens
- open-telemetry/opentelemetry-go-compile-instrumentation#1326 — fix(tool): FuncArgumentOfType fails on aliased imports in call and raw rules
- open-telemetry/opentelemetry-go-compile-instrumentation#806 — chore(tool): addition of `govulncheck` scanning in ci workflows

**PRs authored, opentelemetry-go-compile-instrumentation (open):**

- open-telemetry/opentelemetry-go-compile-instrumentation#1488 — fix(setup): Resolve Symlinks Before Cleaning Rule Paths
- open-telemetry/opentelemetry-go-compile-instrumentation#1422 — refactor(instrumentation/kafka-go): pre-size request attribute slice
- open-telemetry/opentelemetry-go-compile-instrumentation#1408 — feat(instrumentation/mux): add gorilla/mux route enrichment
- open-telemetry/opentelemetry-go-compile-instrumentation#1367 — feat(instrumentation/echo): add labstack/echo/v4 route enrichment

**PRs authored, opentelemetry.io (merged):**

- open-telemetry/opentelemetry.io#10965 — Move Go compile-time "how-to" from blog into docs

**PRs reviewed:**

- open-telemetry/opentelemetry-go-compile-instrumentation#1409 — fix(instrumentation/openai): guard StreamingReader against a concurrent Close/Read race
- open-telemetry/opentelemetry-go-compile-instrumentation#1405 — fix(instrumentation/linodego): record error types on spans and duration metrics
- open-telemetry/opentelemetry-go-compile-instrumentation#1404 — fix(tool/setup): tolerate transient ERROR_ACCESS_DENIED during Windows build lock wait
- open-telemetry/opentelemetry-go-compile-instrumentation#1377 — fix(instrumentation/log): avoid false trace_id correlation matches
- open-telemetry/opentelemetry-go-compile-instrumentation#1358 — fix(tool/internal/instrument): only strip ignore build constraints in add_file rules
- open-telemetry/opentelemetry-go-compile-instrumentation#1245 — fix(instrumentation/github.com/anthropics/anthropic-sdk-go): detect SSE responses case-insensitively

**PRs commented on:**

- open-telemetry/opentelemetry-go-compile-instrumentation#1472 — refactor(tool/internal/setup): reuse buildFlags and share rule-file loading
- open-telemetry/opentelemetry-go-compile-instrumentation#1461 — fix(instrumentation/net/http): client hook writes trace headers into the caller's request
- open-telemetry/opentelemetry-go-compile-instrumentation#1459 — fix(instrumentation/openai): stop silently dropping telemetry on oversized bodies
- open-telemetry/opentelemetry-go-compile-instrumentation#1426 — feat(instrumentation): add compile-time instrumentation for modelcontextprotocol/go-sdk (MCP)

**Issues reported:**

- open-telemetry/opentelemetry-go-compile-instrumentation#1406 — bug(instrumentation/openai): streaming abort span missing error.type
- open-telemetry/opentelemetry-go-compile-instrumentation#1366 — New Instrumentation Request for github.com/labstack/echo/v4
- open-telemetry/opentelemetry-go-compile-instrumentation#1331 — New Instrumentation Request for go.uber.org/zap
- open-telemetry/opentelemetry-go-compile-instrumentation#1325 — bug: missing instrumentation for Anthropic count_tokens endpoint
- open-telemetry/opentelemetry-go-compile-instrumentation#793 — Add govulncheck vulnerability scanning to CI

**Issues responded to:**

- open-telemetry/opentelemetry-go-compile-instrumentation#1397 — bug(instrumentation/grpc): DialContext installs duplicate client stats handlers
- open-telemetry/opentelemetry-go-compile-instrumentation#1361 — bug(tool): duplicated go:linkname definition when more than one package in a link unit receives otelc.runtime.go
- open-telemetry/opentelemetry-go-compile-instrumentation#1314 — bug(instrumentation/openai): requests over 1 MB produce no span at all
- open-telemetry/opentelemetry-go-compile-instrumentation#766 — fix(ast): stripGenericTypes fatals on qualified pointer receivers
- open-telemetry/opentelemetry-go-compile-instrumentation#758 — Allow applications to use auto-instrumentation and manual instrumentation at the same time
- open-telemetry/opentelemetry-go-compile-instrumentation#756 — Signature filters fatal on functions with slice/chan/map params instead of no-match
- open-telemetry/opentelemetry-go-compile-instrumentation#695 — Spec-correct messaging instrumentation: shared layer + kafka-go up to spec + IBM/sarama
- open-telemetry/opentelemetry.io#10846 — docs: migrate Go compile-time instrumentation how-to into /docs/zero-code/go/compile-time/
- open-telemetry/opentelemetry-go-build-tools#1528 — New tool: grater

**Community activities I organized/ran:**

- Talks on OpenTelemetry and Go compile-time instrumentation at CNCG Pune meetups

**SIG projects I am involved with:**

- Go Compile-time Instrumentation SIG (`opentelemetry-go-compile-instrumentation`)
- Communications SIG, docs (`opentelemetry.io`)
