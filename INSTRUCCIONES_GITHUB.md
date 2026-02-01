# Instrucciones para publicar en GitHub Pages

## Problema identificado
Si solo ves "Saludo" en la página, es porque GitHub Pages necesita que el archivo principal se llame `index.html`.

## Solución

### Opción 1: Renombrar el archivo (Recomendado)
1. Renombra `tarjeta-saludos.html` a `index.html`
2. Sube el archivo `index.html` a tu repositorio
3. Asegúrate de que la carpeta `image` esté en la misma ubicación que `index.html`

### Opción 2: Estructura del repositorio
Tu repositorio debe tener esta estructura:
```
Saludo/
├── index.html (o tarjeta-saludos.html renombrado)
└── image/
    ├── hello.gif
    ├── dias.gif
    ├── as.gif
    ├── jh.gif
    ├── unnamed.gif
    ├── asd.gif
    ├── ax.gif
    └── qw.gif
```

### Configuración de GitHub Pages
1. Ve a Settings de tu repositorio
2. Ve a la sección "Pages"
3. Selecciona la rama (branch) donde está tu código (normalmente `main` o `master`)
4. Selecciona la carpeta `/root` o `/docs` según tu estructura
5. Guarda los cambios

### Verificar
- La URL debería ser: `https://boris13jbb.github.io/Saludo/`
- Si usas `index.html`, se cargará automáticamente
- Si usas otro nombre, accede con: `https://boris13jbb.github.io/Saludo/tarjeta-saludos.html`

## Notas importantes
- Las rutas de las imágenes ya están corregidas para funcionar en GitHub Pages
- Todas las imágenes usan rutas relativas (`./image/...`)
- El archivo funciona tanto localmente como en GitHub Pages
