# Arquitetura da Jornada

A Jornada Gamificada de Git & GitHub é organizada como uma documentação progressiva.

```text
README.md
├── docs/
│   ├── architecture.md
│   ├── roadmap.md
│   └── command-reference.md
├── nivel-1-conhecendo-o-universo/
├── nivel-2-preparando-o-ambiente/
├── nivel-3-rastreando-mudancas/
├── nivel-4-trabalhando-com-branches/
├── nivel-5-integrando-com-github/
├── nivel-6-viajando-no-tempo/
├── nivel-7-colaborando-em-projetos/
├── inventario/
└── .github/
    └── workflows/
```

## Estratégia de branches

- `main`: versão estável e publicada.
- `develop`: integração das próximas mudanças.
- `feature/*`: novas funcionalidades ou capítulos.
- `fix/*`: correções.
- `docs/*`: melhorias exclusivamente documentais.

## Princípios

- Conteúdo incremental.
- Exemplos práticos.
- Commits pequenos.
- Pull Requests revisáveis.
- Documentação como parte do produto.
