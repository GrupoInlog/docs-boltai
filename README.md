# docs-boltai

Documentação do usuário da Plataforma BoltAI, gerada com [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

## Rodando localmente

```bash
pip install -r requirements.txt
mkdocs serve
```

Acesse em `http://localhost:8000`.

## Deploy

O deploy é automático via GitHub Actions a cada push na branch `main`. O site é publicado em GitHub Pages.

## Estrutura

```
docs/
├── index.md                    # Página inicial
├── assets/                     # CSS customizado e prints
├── chat/                       # Módulo de Chat
├── conversas-internas/         # Conversas internas
├── analytics/                  # Analytics
└── administracao/              # Administração
```

## Adicionando prints

Coloque as imagens em `docs/assets/prints/` e referencie no Markdown:

```markdown
![Descrição da imagem](../assets/prints/nome-do-arquivo.png)
```
