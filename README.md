# API de Tarefas com Deploy Automatizado (CI/CD)

Este projeto foi desenvolvido para a disciplina de Integração e Entrega Contínua, com foco na implementação prática de um pipeline completo de CI/CD. A API REST foi criada em Node.js com Express e possui estrutura simples, utilizada como base de testes para demonstrar automação de deploy, versionamento e integração entre GitHub Actions e Render.

## Funcionalidades
- Listar tarefas
- Criar, atualizar e remover tarefas
- Resposta de saúde da API (health check)
- Dados mantidos em memória para fins de demonstração

## Tecnologias Utilizadas
- Node.js e Express
- Git e GitHub
- GitHub Actions (workflow acionado por tags SemVer)
- Render (deploy automático)

## Fluxo de CI/CD
O projeto utiliza um workflow que identifica novas tags no padrão `v*.*.*`. Ao publicar uma versão, o GitHub Actions executa o pipeline e aciona o deploy no Render, garantindo atualização contínua da aplicação.

## Objetivo do Projeto
Aplicar na prática:
- Estruturação essencial de uma API REST
- Versionamento SemVer
- Configuração de pipelines de CI/CD
- Deploy automatizado em ambiente cloud
