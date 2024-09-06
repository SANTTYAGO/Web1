# Proyecto de Tienda en Línea con Flask

Este proyecto es una aplicación web básica de una tienda en línea desarrollada con **Flask**. La aplicación permite a los usuarios navegar por una lista de productos y visualizar información detallada de cada uno. 

## Características

- **Lista de productos**: Los productos se despliegan en una lista con enlaces que llevan a una página de detalles.
- **Vista de producto individual**: Muestra una página dedicada a cada producto con su nombre, imagen y precio.
- **Navegación simple**: Permite regresar a la página de inicio desde la página de detalles del producto.

## Tecnologías

- **Backend**: Flask
- **Lenguaje**: Python
- **HTML**: Plantillas Jinja para renderizado dinámico de los productos.
- **Estático**: Imágenes de productos almacenadas en la carpeta `static`.

## Estructura de Archivos

```bash
├── templates/
│   ├── index.html  # Página de inicio con la lista de productos
│   └── producto.html  # Página de detalles de cada producto
├── static/
│   └── # Carpeta para imágenes de productos
├── app.py  # Archivo principal de la aplicación Flask
├── datos.py  # Archivo de datos con información de los productos
```

## Instalación

1. Clona este repositorio.
2. Instala Flask si no lo tienes:
   ```bash
   pip install Flask
   ```
3. Ejecuta la aplicación:
   ```bash
   python main.py
   ```
