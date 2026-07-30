# Leucine

Leucine is an AI-powered software platform for pharmaceutical manufacturing, quality, and laboratory operations, helping drug manufacturers plan, execute, and optimize every batch. The platform spans a Manufacturing Execution System (batch execution, batch intelligence, production logbooks, batch release, shop floor monitor, material management), a Quality Management System (AI Investigator, FDA Tracker, cleaning validation, market complaints, change control, CAPA, supplier quality, audit and deviation management), and a Laboratory Execution System (environmental monitoring, instrument logbooks, QC planning).

Backed by: techstars — https://www.leucine.io/

## API surface

Leucine is an enterprise SaaS vendor with **no public developer API program** — no developer portal, OpenAPI definition, API reference, SDKs, CLI, webhooks, or public package-registry libraries were found during enrichment. The GitHub organization [LeucineTech](https://github.com/LeucineTech) exists but publishes no public repositories. Spec-dependent artifacts (openapi, overlays, errors, data-model, mcp, skills, scopes, authentication, agentic-access) are therefore not applicable.

Note: "API" throughout Leucine's own content refers to *Active Pharmaceutical Ingredient*, not a web API.

## Artifacts

| Artifact | Method | Notes |
|---|---|---|
| `llms/leucine-llms.txt` | searched | Published verbatim at https://www.leucine.io/llms.txt |
| `well-known/leucine-well-known.yml` | searched | No `/.well-known/` documents; records Cloudflare Content-Signal directives on leucine.ai |
| `security/leucine-domain-security.yml` | probed | TLS/HSTS/DNSSEC/CAA/SPF/DMARC across leucine.io, leucine.ai, leucinetech.com |

## Domains

Leucine is mid-migration across three domains: `leucinetech.com` (legacy, 301s to `www.leucine.io`), `leucine.io` (primary content host), and `leucine.ai` (migration target). `leucine.ai` is Cloudflare-fronted and its robots.txt disallows `ClaudeBot` and other AI agents, so it was not crawled.
