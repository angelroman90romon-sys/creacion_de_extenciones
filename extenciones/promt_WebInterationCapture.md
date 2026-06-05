Actúa como un Arquitecto Principal de Extensiones Chrome MV3, especializado en:

* Browser Internals
* Chrome Extensions
* DevTools Protocol
* React Internals
* Shadow DOM
* MutationObserver
* Chrome Debugger API
* Content Scripts
* Service Workers
* Web Automation
* Reverse Engineering

Toma como referencia completa toda la auditoría técnica generada previamente (AUDIT_TECNICA_COMPLETA.md, PATRONES_REUTILIZABLES.md, MAPA_VISUAL.md, STARTER_PACK.md y demás documentos).

Tu objetivo NO es crear una extensión de automatización.

Tu objetivo es crear una EXTENSIÓN UNIVERSAL DE CAPTURA Y ANÁLISIS DE INTERACCIONES WEB.

Debe funcionar sobre:

* Google
* Gemini
* ChatGPT
* Claude
* Meta AI
* QwenChat
* DeepSeek
* Perplexity
* Gmail
* Facebook
* Instagram
* LinkedIn
* Twitter/X
* aplicaciones React
* aplicaciones Vue
* aplicaciones Angular
* aplicaciones NextJS
* aplicaciones Nuxt
* Shadow DOM
* Web Components
* SPAs
* PWAs

La extensión debe capturar cualquier acción que realice un usuario.

# OBJETIVO PRINCIPAL

Generar un blueprint universal de automatización reutilizable.

La extensión debe registrar:

* acción realizada
* selector encontrado
* estrategia de búsqueda
* eventos disparados
* tiempo de espera
* validaciones
* resultado obtenido

Todo debe poder exportarse a Markdown.

# ARQUITECTURA

Diseñar:

manifest.json

background.js

service-worker.js

content.js

page-bridge.js

recorder-engine.js

selector-engine.js

shadow-engine.js

react-engine.js

network-engine.js

download-engine.js

upload-engine.js

storage-engine.js

export-engine.js

sidepanel

popup

settings

# CAPTURA DE INTERACCIONES

Registrar:

click

doubleclick

mousedown

mouseup

mousemove

mouseover

mouseenter

mouseleave

hover

drag

dragstart

dragend

drop

wheel

scroll

touchstart

touchmove

touchend

swipe

zoom

pinch

focus

blur

input

change

paste

copy

cut

submit

keydown

keyup

keypress

select

toggle

checkbox

radio

range

colorpicker

datepicker

timepicker

file upload

folder upload

download

preview

video controls

audio controls

camera permissions

microphone permissions

clipboard access

notifications

websocket events

modal confirmations

toast notifications

loading indicators

skeleton screens

spinners

infinite scrolling

pagination

tab changes

route changes

history changes

pushState

replaceState

popstate

# CAPTURA DE SELECTORES

Para cada acción registrar:

selector CSS

selector único

XPath

atributos

id

name

role

aria-label

data-testid

data-qa

data-id

innerText

React Fiber

Shadow Root Path

DOM Path completo

estrategia recomendada

score de estabilidad

# SHADOW DOM

Detectar:

open shadow roots

closed shadow roots

nested shadow roots

web components

Generar la ruta completa.

# REACT

Detectar:

React Fiber

React Props

React State

React Component

React Events

Generar selectores estables.

# OBSERVADORES

Implementar:

MutationObserver

ResizeObserver

IntersectionObserver

PerformanceObserver

# DETECCIÓN DE ESPERAS

Detectar automáticamente:

aparición de elemento

desaparición

texto esperado

spinner terminado

descarga finalizada

subida finalizada

respuesta API recibida

WebSocket recibido

navegación completada

render React completado

render Shadow DOM completado

# RED

Interceptar:

fetch

XHR

WebSocket

EventSource

GraphQL

Registrar:

request

response

headers

payload

status

tiempo

# DESCARGAS

Detectar:

inicio

progreso

finalización

nombre final

tipo MIME

URL origen

# SUBIDAS

Detectar:

input file

drag and drop upload

folder upload

estado

progreso

finalización

# EXPORTACIÓN

Un botón:

EXPORTAR AUDITORÍA

Debe generar:

Markdown

JSON

YAML

CSV

# MARKDOWN FINAL

Debe contener:

Resumen

Mapa de navegación

Acciones capturadas

Selectores encontrados

Eventos

Shadow DOM detectado

React detectado

APIs utilizadas

Esperas identificadas

Descargas

Subidas

WebSockets

Mutaciones observadas

Patrones reutilizables

Recomendación de automatización

Código sugerido para:

Playwright

Puppeteer

Chrome Extension

Automa

Actiona

# REQUISITO CRÍTICO

No usar únicamente querySelector.

Implementar múltiples estrategias:

CSS

XPath

Text Matching

ARIA

Role

React Fiber

Shadow DOM traversal

MutationObserver tracking

DevTools Protocol

Chrome Debugger API

Generar una solución profesional lista para producción, modular, extensible y preparada para analizar cualquier sitio web moderno.
