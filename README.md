# CSS
## Estructura básica:
.nombreClase{
    propiedad: valor; 
    }

## Selectores: 
.clase{}
#id{}
*{} (selecciona todos los elementos)
[atributo]{}
h1 + h2 {} (elementos adyacentes, aplica a todos los h2 que estén inmediatamente detrás de h1)
ul > li {} (elementos li hijos directos de ul) 
Si directamente se deja un espacio en lugar de un símbolo aplica a todos los elementos que estén dentro.

## Pseudoclases: 
selector:pseudoclase { propiedad: valor; }
:visited 
:hover
:active
:checked
:default
:dir()
:disabled
:empty
:enabled
:first
:nth-last-of-type()
:nth-of-type()
:only-child
:only-of-type
:optional
:out-of-range
:read-only
:read-write
:required
:right
:root
:scope (en-US)
:target
:valid
:first-child
:first-of-type
:fullscreen
:focus
:hover
:indeterminate
:in-range
:invalid
:lang()
:last-child
:last-of-type
:left
:link
:not()
:nth-child()
:nth-last-child()
## Pseudoelementos:
selector::pseudo-elemento { propiedad: valor; }
::after
::before
::first-letter
::first-line
::selection
::backdrop
::placeholder Experimental
::marker Experimental
::spelling-error Experimental
::grammar-error (en-US) 

# Vincular CSS 
```css
<!DOCTYPE html>
  <html>
    <head>
      <link rel="stylesheet" src="style.css">
    </head>
    <body>
    
    </body>
</html>
```
