# 🎓 Curso pessoal de Rust 
## Sobre este repositório

Repositório de acompanhamento de um curso estruturado de Rust, do zero à plataforma distribuída. O curso é composto por **projetos práticos** organizados em **diversos módulos** progressivos, cobrindo:

- Fundamentos (ownership, borrowing, lifetimes)
- Padrões idiomáticos avançados (typestate, newtype, RAII guards)
- Concorrência e async (threads, Tokio, structured concurrency)
- Backend HTTP e bases de dados (Axum, PostgreSQL, SQLx)
- Frontend Rust (Leptos, WASM, Tauri)
- IA e machine learning (Polars, candle, RAG)
- Sistemas embebidos e `no_std`+
- Engenharia avançada (FFI, macros, fuzzing, verificação formal com Kani)

## Estrutura do repositório

curso100+/
├── modulo-00-meta-aprendizagem/
│ ├── p001-ola-rust/
│ ├── p002-erros-compilador/
│ └── ...
├── modulo-01-fundamentos/
│ ├── p005-variaveis-tipos/
│ └── ...
├── ...
└── modulo-xx-plataforma-final/
└── pxx-plataforma/


Cada projeto é uma **pasta independente** com o seu próprio `Cargo.toml` e `README.md` documentando:
- Objetivo do projeto
- Conceitos Rust praticados
- Decisões de arquitetura
- Limitações e melhorias futuras
- Como executar

## Aplicação-âncora evolutiva

Um dos projetos (o Gestor de Tarefas) evolui ao longo de diversos módulos:
1. CLI simples (Módulo 1)
2. Lib reutilizável (Módulo 4)
3. TUI com `ratatui` (Módulo 6)
4. API REST com Axum (Módulo 9)
5. Desktop com Tauri (Módulo 10)
6. Mobile com Tauri 2 (Módulo 10)
7. IoT com Embassy (Módulo 12)
8. Microsserviço numa plataforma distribuída (Módulo xx)

Isto demonstra **reutilização real de código** entre diferentes plataformas, não apenas exercícios paralelos.

## Tecnologias e ferramentas

- **Linguagem:** Rust (Edition 2024)
- **Runtime async:** Tokio
- **Web framework:** Axum
- **Base de dados:** PostgreSQL + SQLx (compile-time queries)
- **Frontend:** Leptos (SSR/SPA), Tauri (desktop/mobile)
- **IA/ML:** Polars, candle, burn
- **Embebidos:** Embassy, `no_std`
- **Testes:** cargo test, cargo-fuzz, Kani (verificação formal)
- **CI/CD:** GitHub Actions, cargo-dist, Sigstore

## Progresso

| Módulo | Estado | Projetos |
|---|---|---|
| 00 — Meta-aprendizagem | 🟡 Em curso | 4 |
| 01 — Fundamentos | ⬜ Planeado | 10 |
| 02 — Ownership e Borrowing | ⬜ Planeado | 10 |
| 03 — Modelação de Domínio | ⬜ Planeado | 8 |
| 04 — Erros e Qualidade | ⬜ Planeado | 10 |
| 05 — Padrões Idiomáticos | ⬜ Planeado | 10 |
| 06 — Debugging e TUI | ⬜ Planeado | 8 |
| 07 — Concorrência Clássica | ⬜ Planeado | 10 |
| 08 — Async e Tokio | ⬜ Planeado | 12 |
| 09 — Backend HTTP e BD | ⬜ Planeado | 14 |
| 10 — Frontend e Desktop | ⬜ Planeado | 12 |
| 11 — IA e Machine Learning | ⬜ Planeado | 8 |
| 12 — Engenharia Avançada | ⬜ Planeado | 12 |
| 13 — Plataforma Final | ⬜ Planeado | 8 |

## Como executar um projeto

Navega para a pasta do projeto e corre:

```bash
cargo run

Licença
Este repositório é público para fins de aprendizagem. O código dos projetos pode ser reutilizado livremente.