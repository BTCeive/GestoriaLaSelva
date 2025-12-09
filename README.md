# Gestoría La Selva — Sitio estático

Esta carpeta contiene el sitio estático para la Gestoría La Selva.

Estructura inicial:
- `docs/` → archivos públicos del sitio (usado por GitHub Pages).

Publicar en GitHub y activar Pages (opciones):

1) Usando la CLI `gh` (recomendada si la tienes instalada):

```bash
cd /home/lorenzo/Escritorio/proyect/GestoriaLaSelva
gh repo create <usuario>/<repo> --public --source=. --push
# Luego en GitHub Settings -> Pages escoger "Branch: main" y "/docs" como carpeta (o usar la web para activar Pages desde la rama/dir correspondiente).
```

2) Manual (sin `gh`):

```bash
cd /home/lorenzo/Escritorio/proyect/GestoriaLaSelva
# Crea el repo en github.com usando la interfaz web
# Luego añade el remoto y empuja:
git remote add origin https://github.com/<usuario>/<repo>.git
git branch -M main
git push -u origin main
```

En GitHub: Settings → Pages → Source: `main` branch `/docs` folder.

Si quieres, puedo intentar crear el repo remoto automáticamente con `gh` si me confirmas que tienes `gh` instalado y autenticado, o puedo darte los pasos exactos para hacerlo desde tu máquina.
