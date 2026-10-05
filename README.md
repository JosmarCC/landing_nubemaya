# NubeMaya Tech Solutions — Sitio estático

Empresa ficticia de servicios web (Linux + nube).

## Archivos
- `index.html` — Inicio
- `caracteristicas.html` — Características técnicas
- `styles.css` — Estilos

## Versionamiento (Git + GitHub)
```powershell
git init
git branch -M main
git add .
git commit -m "Primer commit para subir archivos"
# crear repo en GitHub: landing_nubemaya
git remote add origin https://github.com/TU-USUARIO/landing_nubemaya.git
git push -u origin main
```

## Despliegue Azure Static Web Apps
1. Portal Azure > Crear recurso > Aplicación web estática.
2. Origen: GitHub, repositorio landing_nubemaya, rama main.
3. Detalles compilación: Ubicación de la aplicación `/`, Ubicación de salida vacío.
4. Revisar y crear > URL `*.azurestaticapps.net`.
5. Cada push a main dispara GitHub Actions y actualiza el sitio.

## Evidencias
Guarda tus capturas en `evidencias/` (ev01_vscode.png, ev02_git-init.png, etc.)
