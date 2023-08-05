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
Como actuará el elemento cuando se cumpla la condición que pones (visitado, pasar por encima). 
Acciones al usar los elementos.
selector:pseudoclase { propiedad: valor; }
+ :visited 
+ :hover (activa al pasar por encima)
+ :active (activa al pulsar sobre el elemento)
+ :focus (actúa cuando estás pulsando en el elemento)
+ :checked (puede que haya que especificar dentro del check o imput que es lo que se va a cambiar).
+ Por ejemplo:
<code>
input:checked + label {
    color: red;
  }
</code>

**Otros:**
:dir() :disabled :empty :enabled :first :nth-last-of-type() :nth-of-type() :only-child :only-of-type :optional :out-of-range :read-only :read-write :required :right :root :scope (en-US) :target :valid :first-child  (actúa sobre el primer hijo) :first-of-type :fullscreen :indeterminate :in-range :invalid :lang() :last-child :last-of-type :left :not()  :nth-child()   :nth-last-child()
  
## Pseudoelementos:
Dentro del elemento haz x cosa.
selector::pseudo-elemento { propiedad: valor; }
+ ::after (añade lo que especifiques después del elemento)
+ ::before (añade lo que especifiques antes del elemento)
+ ::first-letter (modifica la primera letra)
+ ::first-line (modifica la primera línea)
Otros: 
+ ::selection (tiene una mayor configuración)
+ Hay otros experimentales:
 [Documentación pseudoelementos CSS](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-elements )

## ANIMACIONES:
```css
elemento {
    /* Tiempo que dura la animación */
    animation-duration: 3s;                     
    /* animation-name: nombreDeLaAnimacion;     */
    animation-name: nombreEjemplo2; /* el nombre de la animación tiene que ser igual que en la linea donde se especifique la animación*/
    /* Especifica cuantas veces se repite la animación (número de veces o infinito) */
    animation-iteration-count: 2; 
    /* Cambiar dirección de la animación: (alternate: una vez hacia 100 y luego de vuelta a 0) */
    animation-direction: alternate;
  }
 @keyframes nombreDeLaAnimacion {
    /* Posición en la que inicia */
    from {
      margin-left: 100%;
      width: 300%;
    }
   /* Posición en la que acaba */
    to {
      margin-left: 0%;
      width: 100%;
    }
  }
```


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
