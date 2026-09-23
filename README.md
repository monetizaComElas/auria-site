# Auria — site (landing pages)

Páginas estáticas de marketing da Auria, desacopladas do app (`monetizaComElas/journey-builder`).

| Página | Arquivo | Tema |
|---|---|---|
| `/lancamento/` | `lancamento/index.html` | Metas de início de ano — "Menos intensidade. Mais consistência." |
| `/empresas/` | `empresas/index.html` | Empreendedores — "Seu projeto não parou por falta de vontade." |

Cada página é um único HTML autocontido (CSS, fontes, fotos em base64 e animações GSAP inline). Não há build: a Vercel publica o repositório como está.

- CTAs apontam para o app: `https://www.auria.monetizacomelas.com.br/quiz` e `/login`.
- Imagens de compartilhamento: `og-lancamento.jpg`, `og-empresas.jpg` (1200×630).
- `/` redireciona para `/lancamento/`.

## Editar texto
Abra o `index.html` da página, procure o trecho e altere. Commit na `main` publica automaticamente.
