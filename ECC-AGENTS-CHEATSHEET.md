# ECC Agents — Cheat Sheet

**How to use any agent:** just say *"use the `<name>` agent to …"* in Claude.
(All 64 ship with the installed `ecc@ecc` plugin and load every session.)

---

## 🌟 Everyday workhorses — start here

| Agent | Call it when… |
|---|---|
| **architect** | About to build a feature or refactor and you want a plan first. |
| **code-reviewer** | You just wrote/changed code — catches bugs, security, quality. |
| **code-explorer** | New codebase; need to understand how something actually works. |
| **build-error-resolver** | The build fails or you have type errors. Minimal-diff fixes. |
| **code-simplifier** | Code works but is messy. Cleans it up without changing behavior. |
| **security-reviewer** | You touched login, user input, APIs, or secrets. Hunts vulns. |
| **planner** | Complex feature/refactor — produces a step-by-step plan. |

## 🧪 Testing & quality

| Agent | For… |
|---|---|
| **tdd-guide** | Building a feature test-first, the disciplined way. |
| **e2e-runner** | End-to-end browser tests (Playwright). |
| **pr-test-analyzer** | Checking a PR's test coverage before merge. |
| **silent-failure-hunter** | Finding swallowed errors and bad fallbacks. |
| **performance-optimizer** | Profiling and speeding up slow code / bundles. |
| **refactor-cleaner** | Removing dead code, duplicates, unused deps. |
| **comment-analyzer** | Checking comments for rot/accuracy. |
| **type-design-analyzer** | Reviewing type design and invariants. |

## 🗄️ Domain specialists

| Agent | For… |
|---|---|
| **database-reviewer** | SQL, schema design, migrations, Postgres performance. |
| **a11y-architect** | Accessibility (WCAG 2.2) design and fixes. |
| **doc-updater** | Keeping READMEs / docs / codemaps current. |
| **docs-lookup** | Fetching up-to-date library/API docs (Context7). |
| **code-architect** | Implementation blueprints that match existing patterns. |

## 🌐 Language-specific reviewers

Call the one matching your stack: **python-reviewer**, **typescript-reviewer**,
**react-reviewer**, **go-reviewer**, **rust-reviewer**, **java-reviewer**,
**kotlin-reviewer**, **swift-reviewer**, **csharp-reviewer**, **cpp-reviewer**,
**php-reviewer**, **fsharp-reviewer**, **flutter-reviewer**, **django-reviewer**,
**fastapi-reviewer**, **mle-reviewer** (ML), **healthcare-reviewer**.

## 🔧 Language-specific build fixers

When a build breaks in a specific stack: **react-build-resolver**,
**go-build-resolver**, **rust-build-resolver**, **java-build-resolver**,
**kotlin-build-resolver**, **swift-build-resolver**, **cpp-build-resolver**,
**dart-build-resolver**, **django-build-resolver**, **pytorch-build-resolver**,
**harmonyos-app-resolver**.

## 🚀 Beyond coding

| Agent | For… |
|---|---|
| **chief-of-staff** | Triaging email/Slack into action vs. noise; drafting replies. |
| **marketing-agent** | Landing pages, email sequences, ad copy, positioning. |
| **seo-specialist** | Technical SEO audits, structured data, Core Web Vitals. |
| **loop-operator** | Running/monitoring autonomous agent loops safely. |
| **harness-optimizer** | Tuning your Claude setup itself for cost/reliability. |

## 🏗️ Networking & infra

| Agent | For… |
|---|---|
| **network-architect** | Designing enterprise/multi-site network architecture. |
| **network-config-reviewer** | Reviewing router/switch configs for safety. |
| **network-troubleshooter** | Diagnosing connectivity/routing/DNS (read-only). |
| **homelab-architect** | Home/small-lab network plans with staged rollback. |

## 📦 Open-sourcing a project

| Agent | For… |
|---|---|
| **opensource-forker** | Fork + strip secrets/internal refs for release. |
| **opensource-sanitizer** | Verify a fork is fully sanitized before release. |
| **opensource-packager** | Generate README/LICENSE/CONTRIBUTING/etc. |

## 🤖 GAN harness (auto build-and-evaluate loop)

| Agent | Role |
|---|---|
| **gan-planner** | One-line prompt → full product spec. |
| **gan-generator** | Implements features against the spec. |
| **gan-evaluator** | Tests the running app, scores it, feeds back. |

---

## A good default workflow

1. **architect** / **planner** → plan it
2. **tdd-guide** (or just build it)
3. **code-reviewer** + **security-reviewer** → catch problems
4. **`<lang>`-reviewer** → stack-specific deep review
5. **code-simplifier** / **refactor-cleaner** → polish
6. **doc-updater** → update docs

---

## MCP tools installed (load every session)

| Server | Gives Claude… |
|---|---|
| **github** | Read/create PRs & issues (bundled with ECC plugin). |
| **exa** | Web search. |
| **context7** | Up-to-date library/API docs. |
| **memory** | Persistent memory across chats. |
| **playwright** | Browser automation. |
| **sequential-thinking** | Step-by-step reasoning scratchpad. |

*Installed at user scope on this machine. Restart Claude after install for everything to activate.*
