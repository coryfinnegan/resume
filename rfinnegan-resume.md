Ryan Cory Finnegan - Senior Software Engineer - Austin, TX (Remote - US) - rfinnegan@blizzard.com





# SUMMARY

Senior Software Engineer specializing in .NET platform engineering, service integration, and reliability tooling for Customer Support, QA, and Battle.net service teams. Builds APIs, ingestion pipelines, contract-driven test harnesses, and CI/CD gates that shorten feedback loops and make failures visible earlier. Known for translating ambiguous cross-team needs into practical systems, clear documentation, and tools other engineers can extend.



# CORE STRENGTHS

System and API Design · Data Ingestion and ETL Pipelines · Service Virtualization · Integration Test Platforms · OpenAPI / AsyncAPI Validation · Reliability Instrumentation · CI/CD Quality Gates · Developer Enablement · Cross-Team Technical Leadership



# SELECTED IMPACT

- Built a schema-driven execution and validation harness for OpenAPI and AsyncAPI services across HTTP and WebSocket workflows, eliminating per-version client code so spec changes no longer require client rewrites.

- Established a reusable service virtualization and integration test platform (Mountebank, containers, in-process API testing) that was adopted across the Service Tech department and extended by other engineers, reducing external-dependency bottlenecks and exercising failure paths earlier.

- Delivered a Perforce-driven asset ingestion and metadata enrichment pipeline that processes 800+ changes across multiple daily builds, onboarded two game titles in parallel, and created a repeatable model for future teams.

- Delivered an end-to-end analysis solution that scans hundreds of changes per build, performs static analysis across referenced code and asset files, and uses Copilot to surface actionable engineering and quality insights, completing a full-build analysis in 20 minutes versus days of manual review.



# EXPERIENCE

## Blizzard Entertainment - Senior Software Engineer, Quality, Cross Game Engineer Group

### 2025–Present

- Designed and delivered a Perforce-driven asset change ingestion pipeline with metadata enrichment that processes 800+ changes across multiple daily builds, enabling two game teams to onboard in parallel while establishing a reusable integration pattern.

- Added health checks and telemetry instrumentation to CI/CD workflows, surfacing 3 previously silent defects and improving deployment confidence.

- Investigated and drove resolution of 3 additional defects uncovered through the new telemetry over the following year, converting hidden runtime issues into tracked engineering work.

- Led UI/UX iteration for tooling used by 5 teams (Overwatch, Diablo, Hearthstone, Service Tech, Overwatch Rush), gathering feedback from 3 stakeholders, producing UX mocks, and using TDD to ship 20+ quality-of-life improvements without disrupting existing workflows.



## Blizzard Entertainment - Senior Software Engineer, Quality, BNOP SDET Group

### 2024–2025

- Built a schema-driven harness capable of executing OpenAPI and AsyncAPI scenarios across HTTP and WebSocket services without per-version client code.

- Added OAuth JWT support so authenticated end-to-end scenarios could run consistently in automated test workflows.

- Partnered with BNOP technical leads and wrote practical documentation that enabled 5 quality engineers to author scenarios independently during the platform's proof-of-concept phase.



## Blizzard Entertainment - Senior Software Development Engineer in Test, Service Tech SDET Group

### 2018–2024

- Re-architected the nightly regression process across test selection, triage, and stability gating, and spearheaded an aggressive triage approach that drove nightly untriaged failures to zero while surfacing 150+ actionable defects over several years.

- Built a .NET integration test platform with an API layer orchestrating Mountebank stubs, Testcontainers, and Alba in GitHub Actions, adopted across the Service Tech department, which continued extending it.

- Created a scenario authoring layer and supporting documentation that let engineers extend integration coverage without changing framework internals.



# EDUCATION

Associate of Applied Science, Computer Information Technology - Game and Visualization Programming Specialization - Austin Community College



# TECHNICAL SKILLS

C# · .NET · JavaScript · TypeScript · Python · Java · Lua · OpenAPI · AsyncAPI · OAuth2 / JWT · GitHub Actions · Testcontainers · Alba · Mountebank · MSTest · xUnit · Playwright · Selenium · JMeter