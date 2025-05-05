# 🌟 Template Mei Caminho Andado: Next.js + Docker + VSCode + GitHub Codespaces

Este repositório é um **template pronto para uso** no desenvolvimento de aplicações React com **Next.js**, preparado para **ambientes de desenvolvimento com GitHub Codespaces** e **containers DevContainer**.

Inclui configurações otimizadas de:

- Ambiente com **Node.js**, **Zsh**, **Oh My Zsh** e **plugins**.
- Extensões e configurações do **VSCode** para produtividade.
- Suporte a **verificação ortográfica**, **formatação automática** e **análise de código**.
- Ferramentas de integração com Git, Docker e GitHub Actions.

> **Foco:** JavaScript com Next.js e Material UI. TypeScript pode ser habilitado com ajustes.

---

## 🚀 Começando

### ✅ Pré-requisitos

Para rodar localmente:

```bash
npm run dev
```

### 🧱 Estrutura do Container
Este repositório já inclui um DevContainer configurado com:

- Node.js + Common Utilities
- Zsh + Oh My Zsh + Plugins
- Docker CLI
- GitHub CLI (gh)
- Extensões de VSCode úteis para produtividade

Recrie o container após alterações com:

```bash
Ctrl+Shift+P → "Codespaces: Rebuild Container"
```

### 📦 🔍 Linters e Validadores
Este template já vem com:
- Prettier: formatação automática ao salvar
- SonarLint: análise de código e segurança
- Code Spell Checker: correção ortográfica para en, pt, pt_BR
- Configurações incluídas em .vscode/settings.json.

### 🐳 Docker & Dev Containers
Ambiente isolado com as mesmas dependências para todos os devs:

- Configurado via .devcontainer/devcontainer.json
- Suporte a rebuild de container
- Plugins como zsh-autosuggestions e fast-syntax-highlighting

### 📁 Git & .gitignore
Modelo de .gitignore baseado no arquivo oficial do React, adaptado para projetos Next.js.

