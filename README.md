# Plugins_MBA

Repositório centralizado (monorepo) de plugins, ferramentas e *skills* desenvolvidos em Python para automação de fluxos de trabalho diários e replicação entre múltiplas plataformas e agentes de IA.

## 🎯 Objetivo

Manter uma base única, modular e versionada para que qualquer plugin ou *skill* possa ser rapidamente adaptado, importado ou executado remotamente em diferentes ambientes:
- **OpenAI** (Codex / ChatGPT)
- **Anthropic** (Claude Code)
- **Google** (Gemini / Antigravity)

## 📁 Estrutura do Repositório

Cada plugin fica isolado em seu próprio diretório dentro de `plugins/`, contendo suas dependências, scripts e definições de *skills*:

```text
Plugins_MBA/
├── plugins/
│   └── exemplo-plugin/
│       ├── skills/          # Definições, prompts e instruções de cada skill
│       ├── src/             # Código-fonte e scripts em Python
│       ├── requirements.txt # Dependências específicas do plugin
│       └── README.md        # Documentação de uso e parâmetros do plugin
├── .gitignore
└── README.md
