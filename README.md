# blockout.ar

Hub linkinbio oficial de **Blockout Entertainment** (Morón, 29 años).
Sitio estático vanilla HTML + CSS, sin build step.

## Deploy

Conectado a Cloudflare Workers Builds. Cada push a `master` despliega automáticamente.

> Requisito: la Cloudflare GitHub App debe tener acceso al repo `Blockout333/blockout-ar`
> (github.com/settings/installations → Cloudflare Workers and Pages → repos seleccionados).

URL: <https://blockout.ar>

## Stack

- HTML + CSS vanilla (sin frameworks ni build)
- Google Font Plus Jakarta Sans
- Iconos SVG inline (Lucide-style + marcas oficiales)
- Schema.org LocalBusiness para SEO
- Open Graph para previews en redes

## Estructura

```
.
├── index.html                       # Landing principal
├── logo-blockout-transparent.png    # Logo Blockout
└── README.md
```

## Cambios

Editar `index.html` localmente, commit + push, se despliega solo en segundos.
