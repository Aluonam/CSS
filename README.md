# CSS
## Estructura básica:
.nombreClase{
    propiedad: valor; 
    }

## Selectores: 
+ .clase{}
+ #id{}
+ *{} (selecciona todos los elementos)
+ [atributo]{}
+ h1 + h2 {} (elementos adyacentes, aplica a todos los h2 que estén inmediatamente detrás de h1)
+ ul > li {} (elementos li hijos directos de ul) 
+ Si directamente se deja un espacio en lugar de un símbolo aplica a todos los elementos que estén dentro.

## Pseudoclases: 
Como actuará el elemento cuando se cumpla la condición que pones (visitado, pasar por encima)
selector:pseudoclase { propiedad: valor; }
+ :visited 
+ :hover
+ :active
+ :checked
+ :default
+ :dir()
+ :disabled
+ :empty
+ :enabled
+ :first
+ :nth-last-of-type()
+ :nth-of-type()
+ :only-child
+ :only-of-type
+ :optional
+ :out-of-range
+ :read-only
+ :read-write
+ :required
+ :right
+ :root
+ :scope (en-US)
+ :target
+ :valid
+ :first-child
+ :first-of-type
+ :fullscreen
+ :focus
+ :hover
+ :indeterminate
+ :in-range
+ :invalid
+ :lang()
+ :last-child
+ :last-of-type
+ :left
+ :link
+ :not()
+ :nth-child()
+ :nth-last-child()
  
## Pseudoelementos:
Dentro del elemento haz x cosa.
selector::pseudo-elemento { propiedad: valor; }
+ ::after (añade lo que especifiques después del elemento)
+ ::before
+ ::first-letter
+ ::first-line (modifica la primera línea)
Otros: 
+ ::selection (tiene una mayor configuración)
+ Hay otros experimentales:
 [Documentación pseudoelementos CSS](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-elements )

# Vincular CSS 
```css
<!DOCTYPE html>
  <html>
    <head>
      <link rel="stylesheet" href="style.css">
    </head>
    <body>
    
    </body>
</html>
```
