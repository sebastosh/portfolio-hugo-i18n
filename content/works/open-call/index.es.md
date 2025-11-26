+++
title = 'Open Call'
position = 'Desarrollador Web Full Stack'
location = 'New York City, USA'
image = "open-call.jpg"
date = 2019-04-01T00:00:00-07:00
repo = 'https://github.com/sebastosh/open-call'
tags = ['ReactJS','Rails API','JWT','AWS S3']
+++

Una aplicación web de mercado que permite a los artistas enviar obras para su revisión y selección por parte de instituciones. Hay dos tipos de usuarios: artistas y organizaciones. Los artistas pueden registrarse y subir sus obras a portafolios. Las organizaciones pueden registrarse y publicar convocatorias abiertas para la presentación de obras. Los artistas pueden enviar imágenes seleccionadas de su portafolio a una convocatoria abierta para su revisión por parte de la organización. Una organización puede seleccionar un artista finalista para cada una de sus respectivas convocatorias abiertas.

Desarrollado en [@flatiron-school](https://github.com/flatiron-school) con [@wrfeng](https://github.com/wrfeng).

## Tecnologías clave, paquetes y gemas

Front-end

- React.js

Back-end

- API de Rails 5
- Autenticación mediante token JWT
- BCrypt
- Base de datos Postgres
- Serializador fast_jsonapi
- AWS S3

Funciones principales

- Los usuarios no registrados pueden ver todas las convocatorias abiertas activas en la página principal.
- Una llamada a la acción dirige a los usuarios a cada uno de los procesos de registro correspondientes.
- Los artistas pueden subir y añadir metadatos a las imágenes de sus obras. 
- Se almacenan en grupos llamados portafolios.
- Las organizaciones pueden publicar una convocatoria abierta basada en un formulario, incluyendo la fijación de una fecha límite para su cierre.
- Los artistas pueden postularse una vez a cada convocatoria abierta disponible.
- Los artistas envían una selección de imágenes de portafolio precargadas.
- Una organización elige al artista finalista para cada una de sus convocatorias abiertas.
