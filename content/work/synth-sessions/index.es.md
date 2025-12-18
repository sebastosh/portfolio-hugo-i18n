+++
title = 'Synth Sessions'
position = 'Desarrollador Web Full Stack'
location = 'New York City, USA'
image = "synth-sessions.png"
date = 2019-07-01T00:00:00-07:00
repo = 'https://github.com/sebastosh/synth-session'
tags = ['ReactJS','ToneJS','NexusUI','Rails API','JWTAuth']
+++

Una aplicación web diseñada para improvisar con varios sintetizadores. Los usuarios pueden crear una sesión y añadir uno o más módulos de sintetizador (actualmente disponibles: Mono Synth, Duo Synth y FM). Pueden tocar cada sintetizador con las teclas en pantalla o con el teclado del ordenador.

Tecnologías, paquetes y gemas clave:

Front End

- React.js
- Tone.js
- nexusUI
- react-select

Back End

- API de Rails 5
- Autenticación mediante token JWT
- BCrypt
- Base de datos Postgres
- Serializador fast_jsonapi

Funciones principales

- Los usuarios no registrados pueden improvisar con sintetizadores, pero se les solicitará que se registren al guardar una sesión o los parámetros del sintetizador.
- La página de visualización de la sesión muestra un menú para agregar de 1 a 3 módulos de sintetizador diferentes en cualquier momento.
- Los nombres de las sesiones y los módulos se pueden editar en línea.
- Los parámetros de los módulos (ganancia, envolventes, armónicos, etc.) se pueden guardar en el servidor backend y restaurar en futuras sesiones.
