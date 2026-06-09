# ECC — Resumo de Todos os Agentes (Português de Portugal)

**Como usar qualquer agente:** basta dizeres *"usa o agente `<nome>` para…"*.
Todos os 64 agentes vêm com o plugin `ecc@ecc` e são carregados em todas as sessões.

---

## 🌟 Agentes do dia a dia

| Agente | O que faz |
|---|---|
| **architect** | Especialista em arquitetura de software: desenho de sistemas, escalabilidade e decisões técnicas. Usa antes de criar funcionalidades ou refazer sistemas grandes. |
| **planner** | Planeamento de funcionalidades complexas e refatorações. Cria um plano passo a passo antes de mexer no código. |
| **code-architect** | Desenha a arquitetura de uma funcionalidade analisando os padrões já existentes no código e entrega um "blueprint" com ficheiros, interfaces e ordem de construção. |
| **code-explorer** | Analisa a fundo o código existente: traça caminhos de execução, mapeia camadas e documenta dependências. Ideal para entender um projeto novo. |
| **code-reviewer** | Revisão geral de código: qualidade, segurança e manutenibilidade. Usa logo após escrever ou alterar código. |
| **code-simplifier** | Simplifica e limpa o código mantendo o comportamento. Foca-se no código alterado recentemente. |
| **refactor-cleaner** | Remove código morto, duplicados e dependências não usadas (knip, depcheck, ts-prune) de forma segura. |
| **build-error-resolver** | Resolve erros de build e de tipos (TypeScript) com alterações mínimas, sem mexer na arquitetura. |

## 🔒 Segurança e fiabilidade

| Agente | O que faz |
|---|---|
| **security-reviewer** | Deteção e correção de vulnerabilidades: segredos, SSRF, injeção, cripto insegura, OWASP Top 10. Usa após código que lida com input, autenticação ou dados sensíveis. |
| **silent-failure-hunter** | Caça falhas silenciosas: erros engolidos, fallbacks maus e falta de propagação de erros. |
| **comment-analyzer** | Analisa comentários do código quanto a rigor, completude e risco de ficarem desatualizados. |
| **type-design-analyzer** | Analisa o desenho de tipos: encapsulamento, expressão de invariantes e utilidade. |

## 🧪 Testes e qualidade

| Agente | O que faz |
|---|---|
| **tdd-guide** | Especialista em TDD: obriga a escrever os testes primeiro. Garante 80%+ de cobertura. |
| **e2e-runner** | Testes ponta a ponta (Vercel Agent Browser / Playwright). Gere jornadas de teste, isola testes instáveis e guarda artefactos. |
| **pr-test-analyzer** | Avalia a qualidade e a cobertura de testes de um Pull Request, com foco em prevenir bugs reais. |
| **performance-optimizer** | Análise e otimização de desempenho: estrangulamentos, fugas de memória, tamanho de bundles, melhorias algorítmicas. |

## 🗄️ Especialistas de domínio

| Agente | O que faz |
|---|---|
| **database-reviewer** | Especialista em PostgreSQL: otimização de queries, desenho de esquemas, migrações e segurança. Inclui boas práticas de Supabase. |
| **a11y-architect** | Arquiteto de acessibilidade (WCAG 2.2) para Web e nativo. Usa ao desenhar componentes de UI ou design systems. |
| **doc-updater** | Atualiza documentação e "codemaps": READMEs, guias e a pasta docs/CODEMAPS. |
| **docs-lookup** | Vai buscar documentação atualizada de bibliotecas/APIs (via Context7) e responde com exemplos. |
| **seo-specialist** | Auditorias técnicas de SEO, otimização on-page, dados estruturados, Core Web Vitals e mapeamento de palavras-chave. |

## 🌐 Revisores por linguagem

| Agente | Linguagem / Framework |
|---|---|
| **python-reviewer** | Python (PEP 8, type hints, segurança, idiomas pythonic). |
| **typescript-reviewer** | TypeScript/JavaScript (segurança de tipos, async, segurança Node/web). |
| **react-reviewer** | React/JSX (hooks, desempenho de render, fronteiras server/client, acessibilidade). |
| **go-reviewer** | Go (idiomático, concorrência, tratamento de erros). |
| **rust-reviewer** | Rust (ownership, lifetimes, uso de unsafe). |
| **java-reviewer** | Java (Spring Boot e Quarkus, deteta o framework automaticamente). |
| **kotlin-reviewer** | Kotlin e Android/KMP (corrotinas, Compose, clean architecture). |
| **swift-reviewer** | Swift (design orientado a protocolos, ARC, Swift Concurrency). |
| **csharp-reviewer** | C# (.NET, async, nullable reference types). |
| **cpp-reviewer** | C++ (segurança de memória, C++ moderno, concorrência). |
| **php-reviewer** | PHP (PSR-12, Eloquent ORM, segurança). |
| **fsharp-reviewer** | F# (idiomas funcionais, pattern matching, computation expressions). |
| **flutter-reviewer** | Flutter/Dart (widgets, gestão de estado, desempenho). |
| **django-reviewer** | Django (ORM, DRF, segurança de migrações). |
| **fastapi-reviewer** | FastAPI (async, injeção de dependências, Pydantic, OpenAPI). |
| **mle-reviewer** | Machine Learning em produção (pipelines de dados, treino, serving, monitorização). |
| **healthcare-reviewer** | Código de saúde (segurança clínica, conformidade PHI, integridade de dados médicos). |

## 🔧 Resolvedores de erros de build por stack

| Agente | Stack |
|---|---|
| **react-build-resolver** | React (Vite, webpack, Next.js, CRA, Parcel, esbuild, Bun). |
| **go-build-resolver** | Go (build, go vet, linters). |
| **rust-build-resolver** | Rust (cargo, borrow checker, Cargo.toml). |
| **java-build-resolver** | Java (Maven/Gradle, deteta Spring Boot ou Quarkus). |
| **kotlin-build-resolver** | Kotlin/Gradle. |
| **swift-build-resolver** | Swift/Xcode (SPM, code signing). |
| **cpp-build-resolver** | C++ (CMake, linker, templates). |
| **dart-build-resolver** | Dart/Flutter (dart analyze, pub, build_runner). |
| **django-build-resolver** | Django/Python (pip/Poetry, migrações, imports). |
| **pytorch-build-resolver** | PyTorch (CUDA, shapes de tensores, DataLoader, treino). |
| **harmonyos-app-resolver** | HarmonyOS/OpenHarmony (ArkTS, ArkUI). |

## 🚀 Negócio e produtividade

| Agente | O que faz |
|---|---|
| **chief-of-staff** | "Chefe de gabinete" de comunicação: tria email, Slack, LINE e Messenger em 4 níveis e gera rascunhos de resposta. |
| **marketing-agent** | Estratega e copywriter de marketing: campanhas, posicionamento, landing pages, sequências de email, anúncios, guiões de vídeo. |

## 🏗️ Redes e infraestrutura

| Agente | O que faz |
|---|---|
| **network-architect** | Desenha arquitetura de rede empresarial ou multi-site a partir de requisitos. |
| **network-config-reviewer** | Revê configurações de routers e switches: segurança, correção e referências obsoletas. |
| **network-troubleshooter** | Diagnostica problemas de rede (conectividade, routing, DNS) por camadas OSI, só de leitura. |
| **homelab-architect** | Planos de rede para casa/laboratório pequeno, com alterações faseadas e rollback. |

## 📦 Tornar projetos open-source

| Agente | O que faz |
|---|---|
| **opensource-forker** | Cria um fork para open-source: copia ficheiros, remove segredos (20+ padrões) e limpa o histórico git. |
| **opensource-sanitizer** | Verifica se o fork está totalmente limpo antes do lançamento (segredos, PII, referências internas). Dá relatório PASS/FAIL. |
| **opensource-packager** | Gera o "embrulho" open-source: CLAUDE.md, setup.sh, README, LICENSE, CONTRIBUTING e templates de issues. |

## 🤖 Harness GAN (ciclo automático criar–avaliar)

| Agente | Papel |
|---|---|
| **gan-planner** | Transforma um pedido de uma linha numa especificação completa de produto. |
| **gan-generator** | Implementa as funcionalidades segundo a especificação e itera com base no feedback. |
| **gan-evaluator** | Testa a aplicação a correr (Playwright), pontua-a e dá feedback acionável ao gerador. |

## ⚙️ Meta (a própria configuração)

| Agente | O que faz |
|---|---|
| **harness-optimizer** | Analisa e melhora a configuração do teu "harness" Claude para fiabilidade, custo e desempenho. |
| **loop-operator** | Opera ciclos de agentes autónomos, monitoriza o progresso e intervém quando bloqueiam. |
| **conversation-analyzer** | Analisa transcrições de conversas para encontrar comportamentos a evitar com hooks (usado pelo /hookify). |

---

## Fluxo recomendado

1. **architect** / **planner** → planear
2. **tdd-guide** (ou construir diretamente)
3. **code-reviewer** + **security-reviewer** → apanhar problemas
4. **`<linguagem>`-reviewer** → revisão específica da stack
5. **code-simplifier** / **refactor-cleaner** → polir
6. **doc-updater** → atualizar a documentação

---

*Total: 64 agentes. Reinicia o Claude após a instalação para todos ficarem ativos.*
