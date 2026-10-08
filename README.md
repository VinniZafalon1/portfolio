# Zafalon OS — Vinicius Pamplona Zafalon

Zafalon OS é um portfólio interativo apresentado como uma área de trabalho de sistema operacional. A interface permite abrir aplicações em janelas e conhecer o perfil, a formação, as habilidades e os interesses acadêmicos de Vinicius.

## Tecnologias

- React e TypeScript
- Vite
- Framer Motion
- Lucide React
- CSS responsivo, com suporte à preferência por movimento reduzido

## Funcionalidades

- Desktop conceitual com wallpaper técnico desenhado em CSS e SVG
- Menu Zafalon OS, ícones de aplicações, relógio e data atualizados em tempo real
- Janelas com foco, arraste pelo cabeçalho, minimizar, maximizar, restaurar e fechar
- Aplicações Sobre Mim, Meus Projetos, Habilidades, Currículo, Contato, Zafalon Engineering Lab e Terminal
- Laboratório com seletor interativo de área de engenharia
- Terminal frontend com comandos `help`, `about`, `skills`, `education`, `contact`, `engineering`, `whoami`, `obmep` e `clear`
- Layout adaptado para celular, com janelas quase em tela cheia

## Instalação e execução

Requer Node.js 18 ou superior e npm.

```bash
npm install
npm run dev
```

O Vite mostra no terminal o endereço local, normalmente `http://localhost:5173`.

## Build de produção

```bash
npm run build
npm run preview
```

O build é criado na pasta `dist/`.

## Estrutura

```text
src/
  App.tsx       Aplicações, janelas e gerenciamento do desktop
  main.tsx      Entrada React
  styles.css    Sistema visual e regras responsivas
index.html      Idioma e metadados SEO
vite.config.ts  Configuração Vite
```

## Deploy

Execute `npm run build` e publique o conteúdo de `dist/` em Vercel, Netlify, Cloudflare Pages ou outro serviço de hospedagem estática. Para uma publicação em subdiretório (como GitHub Pages), configure a propriedade `base` em `vite.config.ts` antes do build.

O botão de currículo informa que o PDF está em preparação. Quando o documento existir, adicione o arquivo ao projeto e atualize a ação na aplicação Currículo.

## Créditos do wallpaper

A foto da McLaren no GP de Singapura 2025 é de Liauzh, via Wikimedia Commons, licenciada em [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). A imagem é carregada diretamente do Wikimedia Commons; o crédito também aparece no desktop.
