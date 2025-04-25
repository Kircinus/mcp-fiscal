# MCP Fiscal

Projeto para converter leis tributárias brasileiras em regras computáveis (Machine-Computable Policies).

## Objetivo
Facilitar a automatização e simulação da aplicação de leis fiscais.

## Tecnologias
- OpenAI GPT para interpretação de texto legal
- YAML/JSON para definição de regras
- Python

## Casos de uso
- Simulação tributária
- Validação automatizada de obrigações fiscais

## Contribuições
Sugestões e PRs são muito bem-vindos!

## Estrutura
``` bash
mcp-fiscal/
│
├── laws/                   # Leis tributárias em formato original
├── src/
│   └── compiler/           # Conversor texto legal → regras computáveis
├── rulesets/               # YAML/JSON com regras formatadas
├── notebooks/
├── tests/
└── README.md
```
