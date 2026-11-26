# Primeros Auxilios en el Entorno Laboral

Presentación web interactiva de la capacitación de primeros auxilios (60 minutos).
Presenta: **Janeth Narváez**, enfermera profesional.

Sitio estático (HTML + CSS + JS), sin dependencias ni paso de compilación.

## Uso

- Navegación: flechas ← →, barra espaciadora o deslizar en el celular.
- ☰ índice, ◐ tema claro/oscuro, ⛶ pantalla completa.

## Estructura

```
index.html
css/styles.css
js/app.js
vercel.json
```

## Probar en local

Abre `index.html` en el navegador, o ejecuta `npx serve .`

## Subir a GitHub y desplegar en Vercel

```bash
git init
git add .
git commit -m "Presentación primeros auxilios"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/primeros-auxilios.git
git push -u origin main
```

En [vercel.com/new](https://vercel.com/new): importa el repositorio, deja **Framework Preset: Other**, sin Build Command ni Output Directory, y pulsa **Deploy**.
