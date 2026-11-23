# eliseumarmon.com

Landing personal de Eliseu Martínez, alojada como sitio estático en GitHub Pages mediante el repositorio `eliseumarmon.github.io` y el archivo `CNAME`.

## Responsabilidad de esta web

La portada presenta el perfil profesional, una selección de proyectos públicos y el interés por la infraestructura. No reproduce el CV completo.

**Catch My CV** es un proyecto independiente: una experiencia interactiva y un currículum HTML/PDF en `cv.eliseumarmon.com`. El acceso desde esta landing lleva por ahora a la sección de presentación del proyecto (`#catch-my-cv`), mientras el subdominio no esté desplegado. Cuando esté disponible, sustituir el aviso «próximamente» por un enlace directo al juego, sin duplicar aquí su contenido.

## Identidad visual

- Landing: superficie clara `#f7f6f2`, texto azul tinta `#19223a`, acento cobalto `#3356ba` y detalle terracota `#b34d2b`.
- Catch My CV: escena lúdica oscura con verdes forestales y ámbar.
- La pequeña tarjeta de Catch My CV conserva el verde del juego para que se perciba que es otro producto.

## Contenido y mantenimiento

- `index.html`: secciones, textos y enlaces.
- `styles.css`: diseño adaptable, esquema cromático e ilustraciones CSS.
- `favicon.svg`: marca geométrica de la landing.
- `CNAME`: dominio, conservar tal como está.

Los proyectos enlazados son repositorios **públicos** de GitHub. El homelab se presenta como experiencia personal sin enlazar su repositorio privado. ProxiMarkt identifica explícitamente su origen académico en equipo y su posterior evolución individual.

No hay generador, dependencias, rastreo, cookies ni llamadas externas para montar la interfaz.

## Comprobar en local

Desde la raíz:

```bash
python3 -m http.server 8000
```

Abre `http://localhost:8000/` y comprueba también la vista móvil y la navegación con teclado. Para publicar se fusiona el cambio en `main`, que GitHub Pages sirve en el dominio indicado por `CNAME`.
