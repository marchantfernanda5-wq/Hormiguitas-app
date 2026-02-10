# Hormiguita (Lecciones 1–5)

Proyecto del módulo 3 (UI Web) implementado con:
- HTML semántico + BEM
- SASS con estructura 7-1
- Layout responsivo (box model + media queries + Grid)
- Bootstrap 4 (componentes + utilities)

## Ejecutar
1. Abre `index.html` en tu navegador (ideal con Live Server).
2. Compila SASS para generar/actualizar `css/main.css`.

## Compilar SASS
```bash
npm install -g sass
sass --watch sass/main.scss:css/main.css
```

## Qué se integra en Lección 5
- Estado vacío usando componente Bootstrap `alert`.
- Botón principal del modal “tintado” con la paleta Hormiguita vía SASS (`.modal-miguita__boton--principal`).
- Bootstrap se usa sin sobreescrituras innecesarias: tu SASS define identidad y pequeños ajustes.

## Estructura (7-1)
- `sass/abstracts`: variables, mixins
- `sass/base`: reset, tipografía
- `sass/layout`: layout general
- `sass/components`: componentes BEM
- `sass/pages`: layout específico de páginas (dashboard)
