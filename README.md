# _public

Repositorio público de **GIXS-Solutions** destinado a alojar contenido estático mediante **GitHub Pages**.

## Propósito

Este repositorio centraliza recursos públicos utilizados por las aplicaciones desarrolladas por GIXS-Solutions, tales como:

- Políticas de privacidad.
- Términos y condiciones.
- Documentación pública.
- Otros archivos HTML o recursos estáticos requeridos por las aplicaciones.

## Estructura

Cada aplicación debe mantener sus recursos dentro de un directorio independiente.

Ejemplo:

```text
/
├── app-hobbyland/
│   └── policies/
│       └── index.html
├── app-example/
│   └── policies/
│       └── index.html
└── ...
```

## Publicación

El contenido se publica automáticamente mediante **GitHub Pages**, por lo que cada recurso es accesible mediante una URL pública.

Ejemplo:

```text
https://gixs-solutions.github.io/_public/app-hobbyland/policies/
```

## Convenciones

- Una carpeta raíz por aplicación.
- Mantener únicamente contenido estático (HTML, CSS, JavaScript, imágenes, PDF, etc.).
- Evitar dependencias innecesarias.
- Conservar una estructura simple y consistente entre aplicaciones.

## Licencia

Copyright © GIXS-Solutions. Todos los derechos reservados.