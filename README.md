# NOVACAR Auto Service · Pit Stop

Site institucional da **NOVACAR Auto Service · Pit Stop**, oficina automotiva em Santos/SP com atuação desde 1981.

## Sobre o projeto

Este repositório contém a versão estática do site institucional da NOVACAR, preparada para publicação direta em serviços como Netlify, GitHub Pages ou qualquer servidor HTTP estático.

O projeto foi limpo para não depender de React, Vite, TypeScript, Node.js ou processo de build. Todo o conteúdo necessário para execução está disponível diretamente em HTML, CSS/JavaScript no documento e arquivos de mídia locais.

## Estrutura

- `index.html` — página principal e lógica de interface.
- `images/` — imagens utilizadas pelo site.
- `novacar-animation.mp4` — vídeo utilizado na experiência visual do site.
- `.gitignore` — arquivos locais que não devem entrar no versionamento.

## Executar localmente

Por ser um site estático, basta abrir `index.html` no navegador. Para testar em um servidor local, também é possível usar qualquer servidor HTTP simples.

Exemplo com Python:

```bash
python -m http.server 8080
```

Depois, acesse `http://localhost:8080`.

## Deploy na Netlify

Não há comando de build obrigatório.

- **Build command:** deixar em branco
- **Publish directory:** raiz do projeto (`.`)

## Tecnologias

- HTML5
- Tailwind CSS via CDN
- JavaScript nativo
- Google Fonts
- Schema.org / JSON-LD

## Marca

NOVACAR Auto Service · Pit Stop  
**Precisão em Movimento.**