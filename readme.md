# Sitemap - Plataforma E-commerce

Este repositorio contiene la arquitectura de navegación y el mapa de rutas de la aplicación. El diagrama detalla la jerarquía de páginas, desde la página de inicio hasta las secciones de productos y cuenta de usuario.

## Estructura de Navegación
El sitio está organizado en cuatro ejes principales que parten de la Página de Inicio (/):
1. Catálogo de Productos
+ Todos los productos (/productes): Listado general.
+ Detalle de producto (/productes/{id}): Vista individual de cada artículo.
2. Categorías (/categories): Clasificación de productos.
+ Móviles (/categories/mobils)
+  Ordenadores (/categories/ordinadors)
+  Accesorios (/categories/accessoris)
3. Gestión de Compra
+  Cesta (/cistella): Gestión de artículos seleccionados antes de finalizar la compra.
4. Área de Usuario
+  Cuenta de usuario (/compte): Acceso al perfil, historial y configuración del cliente.

## Visualización del Diagrama
Si tienes instalada la extensión de draw.io para GitHub, puedes ver el archivo .xml directamente. Por si no, pudieras, he añadido una copia en formato svg.

## Notas de Diseño
+ Colores: El diagrama utiliza códigos de colores para diferenciar los niveles de profundidad y relaciones.
+ Rutas: Todas las rutas siguen una nomenclatura RESTful clara para facilitar el desarrollo del frontend y el enrutamiento.


![sitemap tienda online](Sitemap-Tienda-online.drawio.svg)