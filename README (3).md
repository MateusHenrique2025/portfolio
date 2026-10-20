# Portfólio · Mateus Henrique

Site pessoal de portfólio feito em um único arquivo (`index.html`), sem frameworks e sem dependências externas.

**Site no ar:** https://mateushenrique2025.github.io/portfolio/

## O que tem no site

- Céu estrelado com parallax e estrelas cadentes
- Tema claro e escuro, com transição pela View Transitions API
- Site bilíngue (PT/EN): abre no idioma do navegador e tem botão para trocar
- Animações de rolagem feitas só com CSS
- Acessibilidade: navegação por teclado, link para pular ao conteúdo e respeito a `prefers-reduced-motion`

## Estrutura

```
portfolio/
├── index.html   # página inteira (HTML, CSS e JavaScript)
├── foto.jpg     # sua foto (o nome deve ser igual ao usado em src)
└── README.md    # este arquivo
```

## Problemas comuns

- **A foto não aparece:** confira se o arquivo está na mesma pasta do `index.html` e se o nome em `src` é idêntico (maiúsculas, minúsculas e extensão contam no GitHub Pages).
- **Erro 404 no site:** confirme que o arquivo se chama `index.html` (minúsculo) e está na raiz do repositório.
- **Mudança não aparece depois do `push`:** espere o deploy terminar na aba **Actions** e atualize com `Ctrl + F5`.

## Licença

Uso pessoal. Aprendizado.
