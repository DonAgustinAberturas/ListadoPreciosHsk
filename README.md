# Listado de Precios

Una aplicación web de una sola página para mostrar listados de precios de manera organizada y atractiva.

## Características

- **Diseño Responsive**: Se adapta a diferentes tamaños de pantalla
- **Pestañas Organizadas**: Productos, Servicios y Ofertas Especiales
- **Datos Dinámicos**: Los precios se cargan desde archivos TXT
- **Interfaz Moderna**: Diseño atractivo con gradientes y efectos visuales
- **Fácil Mantenimiento**: Solo necesitas editar los archivos TXT para actualizar precios

## Estructura del Proyecto

```
ListadoPrecios/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Lógica JavaScript
├── productos.txt       # Datos de productos
├── servicios.txt       # Datos de servicios
├── especiales.txt      # Datos de ofertas especiales
└── README.md          # Este archivo
```

## Formato de los Archivos TXT

Los archivos TXT deben seguir este formato:

```
Nombre|Precio|Descripción|Categoría
Producto 1|$100.00|Descripción del producto|Categoría A
Producto 2|$200.00|Descripción del producto|Categoría B
```

### Campos:
- **Nombre**: Nombre del producto/servicio
- **Precio**: Precio con formato de moneda
- **Descripción**: Descripción opcional del producto
- **Categoría**: Categoría opcional del producto

## Cómo Usar

1. **Editar Precios**: Modifica los archivos TXT para actualizar los precios
2. **Agregar Productos**: Añade nuevas líneas siguiendo el formato establecido
3. **Personalizar**: Modifica los estilos en `styles.css` para cambiar la apariencia

## Instalación y Uso

1. Descarga todos los archivos en una carpeta
2. Abre `index.html` en tu navegador
3. Para subir a GitHub:
   - Crea un nuevo repositorio en GitHub
   - Sube todos los archivos
   - Activa GitHub Pages en la configuración del repositorio

## Personalización

### Cambiar Colores
Edita las variables CSS en `styles.css`:
```css
body {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Agregar Nuevas Pestañas
1. Añade el botón en `index.html`
2. Crea el archivo TXT correspondiente
3. Actualiza `dataFiles` en `script.js`

## Tecnologías Utilizadas

- HTML5
- CSS3 (con gradientes y efectos modernos)
- JavaScript ES6+ (con async/await)
- Fetch API para cargar archivos

## Compatibilidad

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT. 