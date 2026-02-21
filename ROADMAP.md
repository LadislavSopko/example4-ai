# example4.ai — Roadmap

## Phase 1 — SEED (March 2026)

Prepare 50 popular libraries as initial content, generated with Claude Code. Multi-language mix covering the most widely-used libraries across 6 ecosystems.

### C# (~12 libraries)
| Library | Focus |
|---|---|
| Newtonsoft.Json | JSON serialization/deserialization |
| MediatR | CQRS and mediator pattern |
| AutoMapper | Object-to-object mapping |
| Dapper | Lightweight ORM / micro-ORM |
| FluentValidation | Declarative validation rules |
| Serilog | Structured logging |
| Polly | Resilience and transient-fault handling |
| EF Core | Entity Framework Core ORM |
| Hangfire | Background job processing |
| MassTransit | Message bus / distributed messaging |
| RestSharp | REST API client |
| xUnit | Unit testing framework |

### TypeScript/JavaScript (~12 libraries)
| Library | Focus |
|---|---|
| axios | HTTP client |
| zod | Schema validation |
| prisma | Type-safe ORM |
| express | Web framework |
| next.js | React meta-framework |
| react-query | Server state management |
| lodash | Utility functions |
| date-fns | Date manipulation |
| jest | Testing framework |
| tailwindcss | Utility-first CSS |
| drizzle | TypeScript ORM |
| tRPC | End-to-end type-safe APIs |

### Python (~12 libraries)
| Library | Focus |
|---|---|
| requests | HTTP client |
| pydantic | Data validation |
| fastapi | Web framework |
| sqlalchemy | ORM / SQL toolkit |
| pandas | Data analysis |
| pytest | Testing framework |
| httpx | Async HTTP client |
| celery | Distributed task queue |
| click | CLI framework |
| boto3 | AWS SDK |
| langchain | LLM application framework |
| flask | Lightweight web framework |

### Java (~8 libraries)
| Library | Focus |
|---|---|
| Spring Boot | Application framework |
| Jackson | JSON processing |
| Lombok | Boilerplate reduction |
| Hibernate | ORM framework |
| Kafka | Event streaming |
| JUnit 5 | Testing framework |
| Guava | Core utilities |
| OkHttp | HTTP client |

### Go (~3 libraries)
| Library | Focus |
|---|---|
| gin | Web framework |
| cobra | CLI framework |
| sqlx | SQL extensions |

### Rust (~3 libraries)
| Library | Focus |
|---|---|
| serde | Serialization framework |
| tokio | Async runtime |
| reqwest | HTTP client |

### Deliverables
- 50 example repositories, each with `manifest.json`
- GitHub Actions CI configured for every repo (build + test on push)
- All examples compile and pass tests
- Manifest registry index

---

## Phase 2 — MVP LAUNCH (April 2026, before AI Week Italia May 1)

### Product
- Landing page on **example4.ai**
- Working MCP server connected to all 50 seed libraries
- Semantic navigation via LSAI (search, outline, hierarchy, source, usages)
- Token savings metrics dashboard

### Marketing
- 60-second demo video: AI agent using example4.ai to learn a library
- Comparison benchmarks: example4.ai vs traditional docs vs DeepWiki
- Waitlist / early access signup

### Technical
- MCP server deployed (Docker, cloud-hosted)
- LSAI instance per language ecosystem
- Manifest registry API
- Example repo caching and indexing

### Target Event
**AI Week Italia** — May 1, 2026. Public presentation of the concept and live demo.

---

## Phase 3 — COMMUNITY PLATFORM (Post AI Week, Q2-Q3 2026)

### Platform Opening
Open SaaS platform where anyone can publish example repos. The npm/Docker Hub model applied to code examples.

### Publication Flow
```
Developer creates example repo
        │
        ▼
Adds manifest.json (following spec)
        │
        ▼
Publishes to example4.ai
        │
        ▼
CI automatically verifies: build ✓ test ✓
        │
        ▼
Example enters the catalog (if green)
```

### Participants
- **Library maintainers** publish examples to increase adoption of their library
- **Developers** publish examples to share knowledge and build reputation
- **AI agents** consume examples for productivity and token savings

### Quality Gate
Only examples that build and pass tests get published. No exceptions. CI is the quality gate.

### Growth Model
Organic growth through community contributions. Every published example repo makes the platform more valuable for AI agents, which drives more users, which drives more contributions. Classic network effect.

---

## Phase 4 — NETWORK EFFECTS (Q4 2026)

### Scale
- Thousands of libraries in the catalog
- Coverage across all major ecosystems (C#, TypeScript, Python, Java, Go, Rust, and beyond)

### Integration
- Native integration in AI coding agents (Claude Code, GitHub Copilot, Codex)
- example4.ai becomes the de facto standard for how AI learns libraries
- IDE plugins for direct example navigation

### Competitive Moat
- Nobody rebuilds the example database — too much accumulated content
- LSAI provides semantic navigation that no competitor can replicate (grep-based tools can't match symbol search, type hierarchy, call graph analysis)
- Community contributions create a self-reinforcing flywheel

---

## Phase 5 — MONETIZATION

### Tiers

| Tier | Price | Features |
|---|---|---|
| **Free** | $0 | MCP access to community libraries, rate-limited |
| **Pro** | TBD | Automatic example repo generation for your libraries, priority access, higher rate limits |
| **Enterprise** | TBD | Private example repos, CI/CD integration, SLA, dedicated LSAI instances |

### Revenue Streams
- **Subscription** — Pro and Enterprise tiers
- **Generation** — pay-per-library automatic example generation
- **Partnerships** — GitHub, GitLab, IDE vendors, AI platform integrations

### Value Proposition
- **Free users** drive content and network effects
- **Pro users** (library maintainers) pay for automated generation and maintenance
- **Enterprise users** pay for private infrastructure and support
