**Readme para RouterJS**

Este repositorio contiene la librería RouterJS, una herramienta sencilla para gestionar rutas en aplicaciones web.

### Ejemplo Práctico

```javascript
import { Router } from "https://cdn.devetty.es/RouterJS/js";

// Cargar rutas

Router.render(
  [
    {
      path: "/",
      template: "<h1>Hola</h1>",
    },
    {
      path: "/2",
      template: "<h1>Adios</h1>",
    },
  ],
  document.body
);

// Navegar entre rutas

Router.navigate("/2");
```
