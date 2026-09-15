# 💡 Minhas Ideias de Negócio

> Caderno digital e vault de ideias hospedado na Vercel e versionado no GitHub.

- 🌐 **Site no ar**: [https://minhas-ideias-nine.vercel.app](https://minhas-ideias-nine.vercel.app)
- 🔒 **Repositório Privado**: [https://github.com/IuryAlmeidaDev/minhas-ideias](https://github.com/IuryAlmeidaDev/minhas-ideias)

---

## 📱 Como adicionar uma nova ideia pelo celular

1. Abra o app do **GitHub** no celular ou acesse [github.com/IuryAlmeidaDev/minhas-ideias](https://github.com/IuryAlmeidaDev/minhas-ideias).
2. Entre na pasta `docs/` e na pasta da categoria (ex: `docs/ecommerce/` ou crie uma nova pasta digitando `minha-categoria/nome-da-ideia.md`).
3. Escreva o conteúdo em Markdown (você pode copiar o formato de `docs/templates/modelo-nova-ideia.md`).
4. Clique em **Commit changes**.
5. Em ~45 segundos, a Vercel faz o build automático e a ideia já estará visível no link do seu site.

---

## 🗂️ Estrutura de Pastas

```text
docs/
├── intro.md                        # Página inicial com visão geral
├── ecommerce/                      # Categoria E-commerce
│   └── venda-relogios.md           # Exemplo: Loja de relógios
├── saas/                           # Categoria SaaS / Software
│   └── gestao-assistencia.md       # Exemplo: SaaS para assistência técnica
└── templates/
    └── modelo-nova-ideia.md        # Template para duplicar
```

Cada nova pasta ou arquivo `.md` que você colocar em `docs/` vira automaticamente uma seção e página no menu lateral.

---

## 💻 Desenvolvimento Local

```bash
# Rodar servidor local
npm run start

# Gerar build estático de produção
npm run build
```
