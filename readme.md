####[Fundamentos de HTML]####


1. Estructura base  HTML 5: 
   La estructura básica de una pagina web en html 5 consta de dos partes principales , el encabezado y el cuerpo.

2. Comentarios: 
   Son fragmentos  que no se muestran en la  página web, pero permiten agregar notas y explicaciones.

3. Tipos de Etiquetas:

   3.1 De Apertuara y cierre: 
       Son etiquetas que marcan el inicio y final de un elemento.
       &lt;p&gt;¡Hola, mundo!&lt;/p&gt; , <a></a> , etc.
      <pre></pre> : se utiliza para definir texto preformateado, lo que significa que el navegador mostrará exactamen.te el texto tal como está escrito en el código fuente.
      <button></button>: se utiliza para crear un botón interactivo en una página web.

   3.2 Self Closing: 
      Etiquetas auto-cerradas (también conocidas como etiquetas vacías) son elementos que no requieren una etiqueta de cierre separada.

      <br>: Se utiliza para insertar un salto de línea o un quiebre de línea
      </img>: Se utiliza para mostrar imágenes en la página web.
      </hr>: Se utiliza para insertar una línea horizontal.
   

   3.3 Bloque: Son etiquetas que ocupan  todo el ancho disponible en la página, separando a los elementos que las contienen.

   <p>: Se utiliza para definir un párrafo de texto.
   <h1>, <h2>, <h3>, etc.: Se utilizan para definir encabezados de diferentes niveles de importancia.
   <ul> y <ol>: Se utilizan para crear listas no ordenadas (con viñetas) y listas ordenadas (numeradas), respectivamente.
   <table>: Se utiliza para crear tablas en HTML.

   3.4 Inline: Son  elementos que se alinean en la misma línea.
    <strong>: Se utilizan para resaltar texto como negrita o cursiva, respectivamente.
    <span>: Se utiliza como un contenedor genérico para aplicar estilos o manipular partes específicas del texto.

4. Atributos
   4.1 Obligatorios: Son aquellos que siempre deben tener un valor en una etiqueta HTML.
   Ejemplo: <input type="text" name="nombre">
            Aquí "type" es obligatorio porque define el tipo de input (que puede ser texto, número...)
            Y "name" es obligatorio por lo mismo.

    4.2 Opcionales: Son aquellos que pueden tener o no tener un valor en una etiqueta HTML.
               Si no tiene un atributo opcional, tomará el valor predeterminado del navegador.
              Ejemplo: <button>Aceptar</button>
                      El botón tendrá como texto "Aceptar", si no le asignamos nada.

[HTML ETIQUETAS]

1. Encabezados: Es un elemento utilizado para definir títulos o subtítulos dentro de una página web. Los representa las etiquetas: <h1>, <h2>, <h3>,...,<h6>.

2. Parrafos: Es un elemento utilizado para estructurar y presentar texto en forma de bloques coherentes dentro de una página web. Lo representa la etiqueta <p>.

3. Enlaces: Es un elemento que permite a los usuarios navegar entre diferentes recursos web, archivos, imagenes, audios y video. Los representa la etiqueta: <a> y el atributo href que indica la url de destino.


[HTML5 ETIQUETAS]

1. HEADER : Contenido introductorio de su ancestro mas cercano
2. NAV : Barra de navegación donde se encuentran los enlaces  a otros documentos.Es usada para agrupar los enlaces y facilitar la navegación entre ellos.   
3. FOOTER : Pie de pagina de una seccion o contenido, contiene información relevante como contacto,derecho de autor, redes sociales, etc.
4. SECTION : Seccion o division de contenidos en bloques temáticos
5. ARTICLE : contenido independiente , pero completo
6. MAIN : Contenido principal de la pagina - UNICO
7. ASIDE : Contenido no necesariamente relacionado con la pagina web, como son los anuncios, sidebar,etc.