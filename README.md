# Barra Nobre Estúdio · site estático para a Vercel

Site em HTML puro, sem build. A raiz desta pasta é a raiz do site.

- `index.html` · página principal (Estúdio 3D, catálogo, diagnóstico, aula, processo, obras)
- `politica-de-privacidade.html` · **rascunho**, com campos [CONFIRMAR] e `noindex` até a versão final
- `404.html`, `robots.txt`, `sitemap.xml`, `vercel.json`, `favicon.svg`
- `img/` fotos reais das obras (publicação autorizada pelo Osman em 21/11/2026) · `lib/` Three.js r128, GSAP 3.12.2, Lenis 1.1.13 servidos pelo próprio site

## Publicar
Importar este repositório em vercel.com/new (Framework: Other, sem comando de build, Output: raiz). Cada push na branch principal publica de novo.

## Ao ligar o domínio
Trocar `https://barra-nobre-estudio.vercel.app` pelo domínio final em `index.html` (canonical, og), `robots.txt` e `sitemap.xml`.
