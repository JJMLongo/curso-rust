# Projeto 1 — Olá, Rust!

## Introdução
Primeiro projeto do curso Rust. Configuração do ambiente e escrita do primeiro programa. Projeto muito simples, um "Hello World" só para validar se está tudo ok com o ambiente.

## Artigo da preparação do ambiente do curso
🔗 [[ 2 ] A jornada Rust começa aqui - Instalação e preparação](https://factorvirtual.com/blog/2-jornada-rust-comeca-aqui-instalacao-e-preparacao?serie=vamos-aprender-rust)

## Artigo do projeto
🔗 [[ 3 ] O "Hello World" habitual]([link-do-artigo-p001](https://factorvirtual.com/blog/3-o-hello-world-habitual?serie=vamos-aprender-rust))

## Como executar

    cargo run

## Conceitos praticados
- `cargo new` para criar projetos
- Estrutura de um projeto Cargo (`Cargo.toml`, `Cargo.lock`, `src/main.rs`)
- `cargo run` para compilar e executar
- Função `main()` como ponto de entrada
- Macro `println!` para imprimir no ecrã

## Decisões de arquitetura
- Mensagem personalizada em português
- Projeto independente dentro do repositório do curso

## Limitações
- Programa trivial (apenas imprime texto)
- Sem testes (ainda não aprendemos a escrever testes)

## Melhorias futuras
- Adicionar testes unitários (Módulo 1)
- Aceitar argumentos da linha de comandos (Módulo 1)