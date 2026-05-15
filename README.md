# Bellavista — Panela del Campo al Mundo

Sitio web oficial de **Bellavista (VR Vega Rodríguez SAS)**.

## Estructura del proyecto

```
bellavista/
├── index.html      ← Página principal (todo en un archivo)
├── vercel.json     ← Configuración de despliegue en Vercel
└── .gitignore
```

## Cómo personalizar

### Agregar logo
En el HTML, busca los comentarios `<!-- REEMPLAZAR: -->` y cambia:
```html
<span class="logo-ph-txt">Tu Logo</span>
```
por:
```html
<img src="logo.png" alt="Bellavista">
```
Sube el archivo `logo.png` a la misma carpeta que `index.html`.

### Cambiar el número de WhatsApp
Busca y reemplaza todas las ocurrencias de `TUNUMERO` con el número real en formato internacional, por ejemplo: `573001234567`

### Agregar foto o video al hero
En el HTML, busca el bloque marcado con `OPCIÓN A — FOTO / OPCIÓN B — VIDEO` y sigue las instrucciones ahí.

### Agregar fotos de productos
Cada tarjeta de producto tiene un placeholder. Reemplaza el div con la clase `prod-iph` por:
```html
<img src="foto-producto.jpg" alt="Nombre del producto">
```

## Deploy en Vercel

1. Sube este repositorio a GitHub
2. Ve a [vercel.com](https://vercel.com) → New Project → Importar repositorio
3. Vercel detecta automáticamente que es un sitio estático
4. Click en Deploy → listo en ~30 segundos

---
© 2025 Bellavista · VR Vega Rodríguez SAS · Mogotes, Santander, Colombia
