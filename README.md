# atoll-theme-portfolio

Official **portfolio** theme for `atoll-cms`.

## Install

```bash
php bin/atoll theme:install https://github.com/atoll-cms/atoll-theme-portfolio/archive/refs/heads/main.zip
php bin/atoll theme:activate portfolio
```

## Scope

- `assets/main.css` contains the visual style.
- `templates/layouts/base.twig` and `templates/components/*` override the shared base layout structure.
- Page templates can remain minimal and still use core fallbacks where appropriate.
