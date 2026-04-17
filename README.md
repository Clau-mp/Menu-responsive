# Menu-responsive

## VARIABLES DE CCS

Las variables de ccs son elementos para guardar valores de propiedades de ccs.
Se declaran en un pseudo-selector que se llama :root{} que se encontrara en la primera linea del ccs.
Las variables se declaran por el nombre que decidamos (que tenga sentido) predecido de :
--nombre-de-variable: valor;

Para llamar luego a esa variable usaremos la función 
var(--nombre-de-variable)

# MEDIDAS RELATIVAS AL TAMAÑO DEL VIEWPORT

VW -> viewport width
VH -> viewport heigh
Sonn pormedidas en porcentaje directamente relatovas al tamaño del viewport

funcion calc() me permite hacer calculos matemáticos

#  MEDIDAS RELATIVAS AL FONT-SINZE DEL :ROOT

- REM -> esta medida es relativa al tamaño del font size que tiene el documento por defecto, son 16px

- EM -> es una medida relativa al tamaño de la fuente del elemento padre.