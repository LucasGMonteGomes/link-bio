# LinkBio

> Um espaço simples para reunir meu perfil, redes sociais e projetos em um só lugar.

[![HTML](https://img.shields.io/badge/HTML-estrutura-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML) [![CSS](https://img.shields.io/badge/CSS-estilos-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS) [![Vite](https://img.shields.io/badge/Vite-ferramenta_de_desenvolvimento-646CFF?logo=vite&logoColor=white)](https://vite.dev/)

**[English](#english)**

## Sobre

Este repositório contém uma página pessoal de links e uma página de projetos. O site apresenta o perfil de Lucas G. Monte Gomes e reúne links para redes sociais, contato e projetos, incluindo o Mosaicofy.

## Recursos

- Página de perfil com bio e links sociais
- Página separada para projetos
- Layout responsivo feito com HTML e CSS
- Vite para desenvolvimento local e geração do build

## Executar localmente

**Requisitos:** Node.js e npm compatíveis com a versão do Vite especificada no `package.json`.

```bash
git clone https://github.com/LucasGMonteGomes/link-bio.git
cd link-bio
npm install
npm run dev
```

Abra no navegador o endereço local mostrado pelo Vite.

Para gerar uma versão de produção:

```bash
npm run build
```

O resultado é gerado em `dist/`. Para visualizar o build localmente, use `npm run preview`.

## Personalização

- Conteúdo do perfil e links: `src/index.html`
- Conteúdo da página de projetos: `src/projetos.html`
- Estilos e comportamento responsivo: `src/style.css`
- Imagens e outros recursos: `src/assets/`

Edite os links e textos no HTML e confira a página em diferentes tamanhos de tela antes de publicar.

## Contribuir

Sugestões, correções e melhorias são bem-vindas. Consulte [CONTRIBUTING.md](CONTRIBUTING.md) para as orientações e [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) para os padrões da comunidade.

## Segurança

Para relatar uma possível vulnerabilidade de forma responsável, consulte [SECURITY.md](SECURITY.md).

## Licença

Distribuído sob a licença MIT. Consulte [LICENSE](LICENSE).

---

## English

A personal link page and project showcase for Lucas G. Monte Gomes, bringing profile information, social and contact links, and selected projects together in one place.

### Run locally

Make sure Node.js and npm meet the requirements of the Vite version in `package.json`, then run:

```bash
git clone https://github.com/LucasGMonteGomes/link-bio.git
cd link-bio
npm install
npm run dev
```

Use the local URL printed by Vite. Run `npm run build` to create the production build in `dist/`, or `npm run preview` to preview it locally.

### Project files

- `src/index.html` — profile page
- `src/projetos.html` — projects page
- `src/style.css` — styles and responsive layout
- `src/assets/` — images and other assets

Contributions are welcome; see [CONTRIBUTING.md](CONTRIBUTING.md). Please also read the [Code of Conduct](CODE_OF_CONDUCT.md). Report potential security vulnerabilities according to [SECURITY.md](SECURITY.md).
