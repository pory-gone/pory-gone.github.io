# Blog Personale

Blog personale creato con Hugo e ospitato su GitHub Pages.

## Quick Start

### Prerequisiti

- [Hugo](https://gohugo.io/installation/) installato sul tuo sistema

### Sviluppo Locale

```bash
# Clona la repository
git clone https://github.com/porygone/pory-gone.github.io.git
cd pory-gone.github.io

# Avvia il server di sviluppo
hugo server -D

# Apri il browser su http://localhost:1313
```

### Creare un Nuovo Post

```bash
hugo new posts/mio-nuovo-post.md
```

### Build per Produzione

```bash
hugo --minify
```

I file generati saranno nella cartella `public/`.

## Struttura

```
.
├── content/        # Contenuti del blog
│   ├── posts/     # Post del blog
│   └── about.md   # Pagina About
├── layouts/       # Template HTML
├── static/        # File statici (immagini, css, js)
└── hugo.toml      # Configurazione
```

## Deploy

Il sito viene automaticamente pubblicato su GitHub Pages quando fai push sul branch `main`.

### Configurazione GitHub Pages

1. Vai su Settings → Pages
2. Source: GitHub Actions
3. Il workflow si occuperà del resto!

## Licenza

MIT

## Autore

**Porygone**

- GitHub: [@porygone](https://github.com/porygone)
