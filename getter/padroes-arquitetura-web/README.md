# Padrões Técnicos de Arquitetura Web & Integrações — Getter

Apresentação em [Reveal.js](https://revealjs.com/) para o time de engenharia da Getter, com diretrizes de arquitetura web, integrações entre sistemas, GitLab CI/CD e segurança.

## ▶️ Como visualizar

Abra o `index.html` em qualquer navegador:

```bash
open index.html
```

Ou sirva localmente (recomendado para navegar pelos slides com hash):

```bash
python3 -m http.server 8080
# acesse http://localhost:8080
```

## 🎮 Navegação

| Ação | Tecla / Gestos |
|---|---|
| Avançar | `→` / `Espaço` / clique |
| Voltar | `←` |
| Visão geral dos slides | `Esc` |
| Tela cheia | `F` |
| Notas do apresentador | `S` |
| Ir direto a um slide | `http://localhost:8080/#/5` (índice zero-based) |

## 📁 Estrutura

```
getter/
├── index.html                  # Apresentação completa (21 slides)
├── assets/
│   ├── logo-getter-color.png   # Logo oficial da Getter
│   ├── logo-getter-preta.png   # Logo versão preta
│   └── favicon.png
└── vendor/reveal/              # Reveal.js 5.1.0 (local, funciona offline)
    ├── dist/
    └── plugin/
```

## ✏️ Como editar

Todo o conteúdo está em **um único arquivo**: `index.html`.

- Cada `<section>` dentro de `<div class="slides">` é um slide.
- Para adicionar um slide, copie um bloco `<section>...</section>` existente e edite.
- Classes utilitárias disponíveis: `.kicker`, `.card`, `.grid-2/3/4`, `.tag`, `.callout`, `.steps`, `.kpi`, `.check`, `.cross`, `.arrow`.
- As cores seguem o branding Getter: azul `#1863dc`, verde `#11CE99`, fundo escuro `#0a0f1e`.
- Realce de código usa highlight.js (linguagens: json, protobuf, python, typescript, yaml).

## 🚀 Publicar no GitHub Pages

A pasta é compatível com GitHub Pages:

1. Suba a pasta `getter/` para o repo `presentations.github.io` (branch `main` ou `gh-pages`).
2. A apresentação fica disponível em `https://<usuario>.github.io/presentations/getter/`.

## 🖨️ Exportar PDF

No navegador, adicione `?print-pdf` à URL e imprima com "Salvar como PDF":

```
http://localhost:8080/?print-pdf
```

---

**Getter · Time de Engenharia · 2026**
