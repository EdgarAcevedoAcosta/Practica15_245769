Preguntas:
Responder: ¿por qué el 404 sí tiene encabezado y pie? Por que es para mandar al usuario que hubo un error y no piense que fue otra cosa
Responder: ¿qué cambia en la pestaña Red si usas <a href> en lugar de Link? Muéstralo con capturas.  Te mandaría a otra pestaña, 
Responder: ¿en qué tipo de dato llega el id de la URL y qué pasa si no lo conviertes? llega como un String pero luego se convierte en number, pues que no buscaria el id por que no lo podria leer
Responder: ¿qué pasa al ir de /clases/1 a /clases/2 si el id no está en las dependencias del efecto? te saldría error o solo te actualizara la pagina 







# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some Oxlint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the Oxlint configuration

If you are developing a production application, we recommend enabling type-aware lint rules by installing `oxlint-tsgolint` and editing `.oxlintrc.json`:

```json
{
  "$schema": "./node_modules/oxlint/configuration_schema.json",
  "plugins": ["react", "typescript", "oxc"],
  "options": {
    "typeAware": true
  },
  "rules": {
    "react/rules-of-hooks": "error",
    "react/only-export-components": ["warn", { "allowConstantExport": true }]
  }
}
```

See the [Oxlint rules documentation](https://oxc.rs/docs/guide/usage/linter/rules) for the full list of rules and categories.
