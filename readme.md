1. Explicar cuantas maneras existen para vincular html con css
2. Explicar con sus palabras el conjunto de reglas de CSS (selector , propiedad , valor)
3. Explicar los 4 conceptos importantes con ejemplos ( selectores, herencia , cascada , especificidad)

## EXPLICACION DE VINCULACION CSS

1. Interna en el body => La primera es poner una etiqueta que especifique se dentro de ella se esta trabajando codigo CSS y esta etiqueta es <style></style> , dentro de ella podras escribir codigo CSS en el mismo archivo HTML en la parte del body

2. Manera Externa => La segunda forma es a travez de una archivo .css , la cual para que funcionen los estilos , ese archivo debe de ser llamada con una etiqueta llamada <link> la cual viene con un atributo rel="stylesheet" que eso hace referencia que se trabajara con CSS y lo mas importante viene el atributo href="archivo.css" , como vez ahi ira el nombre del archivo .css

3. Manera inline => La tercera y ultima forma es la manera inline la cual como su nombre lo dice es en linea , actua como atributo en una etiqueta , tiene un nivel alto de especificidad y se trendria que poner con el atributo style="propiedad:valor"

## CONJUNTO DE REGLAS DE CSS

1. Selector => Esto mas se usa en la forma con la etiqueta <style></style> y de manera externa , un selector hace referencia a que etiqueta se le va a dar estilo , los selectores son las etiquetas del HTML por ejm el h1 , p , h2, etc

selector{

}

2. Propiedad => La propiedad es como una caracteristica que se le aplica a un Selector para poder darle cualquier estilos que nosotros querramos

selector{
propiedad :
}

3. Valor => Como su nombre lo dice , valores , se le aplica a la propiedad y ahi es donde el selector cambia segun el estilo que le vas dando , IMPORTANTE cada propiedad con su valor debe de terminar en punto y coma ;

selector{
propiedad : valor;
}
