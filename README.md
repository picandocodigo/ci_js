# Validador de c&eacute;dulas de identidad

Para usarlo en tu aplicación web incluir `ci.js`:

```html
<script type="text/javascript" src="ci.js"></script>
```

Funciones:
```javascript
var ci = "1.111.111";
validation_digit(ci); // => '1' - Obtiene el dígito verificador de una cédula dada

ci = "1.111.111-1"
validate_ci(ci);      // => true/false - Valida una cédula completa

random_ci();          // => 35330781 - Obtiene un número de cédula válido al azar
```

# Aplicación de ejemplo
https://picandocodigo.github.io/ci_js

# En otros lenguajes
* **Ruby** - https://github.com/picandocodigo/ci_uy
* **Python** - https://github.com/francocorreasosa/ci_py
* **Javascript**
  * Plugin para jQuery: https://github.com/picandocodigo/ci.jquery
  * Node - https://github.com/francocorreasosa/ci_node
* **C# - CSharp** - https://github.com/danielbenedykt/ci_csharp
* **PHP** - https://github.com/leeway-academy/ci_php
* **Go** - https://github.com/picandocodigo/ciuy
* **Crystal** - https://github.com/picandocodigo/ci_uy.cr
* **Prolog** - https://github.com/bcattaneo/ci_pl
* **Java** - https://github.com/fabdelgado/ciuy
- **API REST**:
  - Generar CI: [https://ciuy-consumers-api.vercel.app/generate](https://ciuy-consumers-api.vercel.app/generate)
  - Validar CI: [https://ciuy-consumers-api.vercel.app/validate/20050766](https://ciuy-consumers-api.vercel.app/validate/20050766)
