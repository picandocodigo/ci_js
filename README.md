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
* **PHP** - https://github.com/leeway-academy/ci_php
