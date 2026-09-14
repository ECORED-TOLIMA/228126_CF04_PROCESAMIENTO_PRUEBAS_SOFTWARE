<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Sintaxis y estructuras de programación en JavaScript
    
    p(data-aos="flip-up") JavaScript es un lenguaje de programación que potencia las páginas HTML al añadir animaciones, interactividad y efectos visuales dinámicos. Permite una respuesta inmediata en el navegador, lo que significa que cualquier cambio en el código se refleja de forma automática en la #[i web]. Con JavaScript se pueden crear interfaces interactivas, como menús animados o ventanas emergentes. Además, es el lenguaje fundamental en el desarrollo de #[i software] actual, especialmente en aplicaciones #[i web], por lo que comprender su sintaxis y estructuras de programación es esencial para construir soluciones eficientes, mantenibles y escalables.
    p.mb-4(data-aos="flip-up") La siguiente imagen ejemplifica este proceso: 
    .row.justify-content-center.align-items-center.mb-3
      .col-lg-12(data-aos="flip-up")
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 1.
          span Interactividad Zajuna
    .row.justify-content-center.mb-4
      .col-lg-12(data-aos="flip-up")
        .d-none.d-lg-block
          ImagenInfografica.color-acento-botones
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/temas/tema3/img1.png', alt='Figura 1 que contiene la página principal de la plataforma Zajuna del SENA, donde se muestra el acceso al aula virtual. Incluye un formulario de inicio de sesión, un aviso de seguridad sobre contraseñas, un menú lateral de servicios, accesos a cursos virtuales y secciones informativas con iconos y fotografías de aprendices.')
        .d-block.d-lg-none
          figure
            img(src='@/assets/curso/temas/tema3/img1_1.png', alt='Figura 1 que contiene la página principal de la plataforma Zajuna del SENA, donde se muestra el acceso al aula virtual. Incluye un formulario de inicio de sesión, un aviso de seguridad sobre contraseñas, un menú lateral de servicios, accesos a cursos virtuales y secciones informativas con iconos y fotografías de aprendices.')
    p.mb-4 Un ejemplo concreto es la página Zajuna del SENA, donde gran parte de la interactividad se soporta en JavaScript. Gracias a ello, es posible encontrar efectos dinámicos como el resaltado de textos, sombras, animaciones y movimiento de imágenes, entre otros elementos que mejoran la experiencia del usuario.
    p.mb-4 Zajuna es una plataforma #[i web] interactiva que:
    .row.justify-content-center.mb-4
      .col-lg-3
        .tarjeta-bg12.p-4.h-100
          p.mb-0.text-center Permite iniciar sesión.
      .col-lg-3
        .tarjeta--fondo1.p-4.h-100
          p.mb-0.text-center Permite gestionar cursos, usuarios y contenido.
      .col-lg-3
        .tarjeta-bg12.p-4.h-100
          p.mb-0.text-center Navegar entre cursos.
      .col-lg-3
        .tarjeta--fondo1.p-4.h-100
          p.mb-0.text-center Mostrar contenido dinámico.
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-10
        p Todo eso requiere JavaScript para funcionar correctamente.
        p.mb-4 Adicionalmente, JavaScript trasciende el ámbito de las páginas #[i web], ya que puede emplearse en aplicaciones como Yahoo!, Widgets, Google Apps y en la automatización de tareas dentro de #[i software] de Adobe, entre otros usos. Asimismo, ha ganado relevancia en el desarrollo del lado del servidor mediante plataformas como Node.js, lo que amplía las oportunidades para el desarrollo #[i full-stack] utilizando un solo lenguaje.
        .row.justify-content-center.align-items-center.mb-4
            .col-lg-12
              .bloque-texto-gg.color-primario
                .bloque-texto-gg__texto1.p-4
                  p.mb-3 Con JavaScript se puede crear:
                  ul.lista-ul
                    li
                      i.fas.fa-cloud-arrow-down
                      | Páginas #[i web].
                    li
                      i.fas.fa-cloud-arrow-down
                      | Aplicaciones móviles.
                    li
                      i.fas.fa-cloud-arrow-down
                      | Sistemas completos (#[i frontend] + #[i backend]).
                    li
                      i.fas.fa-cloud-arrow-down
                      | Juegos.
                    li
                      i.fas.fa-cloud-arrow-down
                      | Programas de escritorio.

                .bloque-texto-gg__img1(
                  :style="{'background-image':`url(${require('@/assets/curso/temas/tema3/img2.svg')})`}"
                )
        p.mb-4 Este conocimiento permite abordar proyectos de #[i software] de forma estructurada y eficiente; además, su comprensión facilita la resolución de problemas complejos en entornos reales de desarrollo. En el contexto actual del desarrollo de #[i software], estas habilidades son altamente valoradas y demandadas en la industria tecnológica.
        .titulo.mb-4(data-aos="fade-left")
          img(src='@/assets/curso/icon.svg', alt='')
          h5 Estructura de programación en JavaScript 
        p.mb-4 Para entender esta estructura, se relaciona el siguiente ejemplo de un código de un programa en Java, seguido de su debida explicación:
        .tarjeta.color-primario.p-0.mt-3.overflow-hidden.mb-4
          .px-3.py-2(style="background-color: #311a6a; display: flex; align-items: center;")
            .d-flex
              .circle.me-1(style="width: 12px; height: 12px; border-radius: 50%; background-color: #69D7E5;")
              .circle.me-1(style="width: 12px; height: 12px; border-radius: 50%; background-color: #6CB9FF;")
              .circle(style="width: 12px; height: 12px; border-radius: 50%; background-color: #FFD453;")
          .p-4(style="background-color: #0d0d2b;")
            .row.align-items-center
              .col-md-8.mb-3.mb-md-0
                p.text-white.mb-1 MiClase.java
                .row.justify-content-center
                  .col-lg-1
                    p.text-white.mb-0 1
                  .col-lg-11
                    p.text-white.mb-1 class MiClase { 
                .row.justify-content-center
                  .col-lg-1
                    p.text-white.mb-0 2
                  .col-lg-11
                    p.text-white.mb-2 public static void main(String[] args){ 
                .row.justify-content-center
                  .col-lg-1
                    p.text-white.mb-0 3
                  .col-lg-11
                    p.text-white.ms-3.mb-1  System.out.println(“Hola mundo”);
                .row.justify-content-center
                  .col-lg-1
                    p.text-white.mb-0 4
                  .col-lg-11
                    p.text-white.ms-2.mb-1    } // Fin del método main 
                .row.justify-content-center
                  .col-lg-1
                    p.text-white.mb-0 5
                  .col-lg-11
                    p.text-white.ms-1.mb-2   } // Fin de la clase MiClase
                p.text-white.mb-1 Hola mundo
          figcaption #[b Nota:] escriba el código del ejemplo anterior en un editor de texto plano, guarde el archivo con el nombre y extensión.            
        .tarjeta-bg10.p-4
          .row.justify-content-center.align-items-center
            .col-lg-2.d-none.d-lg-block
              img(src="@/assets/curso/temas/tema3/img3.svg", alt="").img100.m-auto
            .col-lg-10
              p MiClase.java
              p.mb-0 Es importante respetar las letras en mayúsculas y las letras en minúsculas; es decir, el nombre del archivo debe ser exactamente el que se muestra en la línea 1; así también, la extensión debe ser .java. Como cualquier nuevo conocimiento, conforme se realicen más ejercicios, poco a poco se irá familiarizando con la estructura general de los programas en Java. 
    p.mb-4.text-center A continuación, se da la explicación de cada línea del código:
    .BG05.px-5.py-3.p-4.mb-4
      .tarjeta--fondo2.p-4
        PasosB.color-acento-botones
          .row(titulo="")

            .col-lg-6.col-12.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema3/img4.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              h5 Línea 1: class MiClase {
              p Marca el inicio de la definición de la clase MiClase. En Java, todo programa debe contar con al menos una clase. Para declarar dicha clase se utiliza la palabra reservada class, seguida del nombre que identificará la clase. Las palabras reservadas siempre se escriben en minúsculas y son exclusivas del lenguaje Java. Finalmente, la llave de apertura { indica que, a partir de ese punto, todo el contenido pertenece a esa clase.

          .row(titulo="")
            .col-lg-6.col-12.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema3/img5.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              h5 Línea 2: public static void main(String[] args){
              p Corresponde al método que se ejecuta para iniciar el programa. Por ahora no es necesario comprender completamente esta línea; a medida que se avance en el aprendizaje, se entenderá el significado de cada una de sus partes. Lo importante es reconocer que todo programa en Java necesita una clase, y dentro de ella debe existir un método main para poder ejecutarse. Al final de la línea se observa nuevamente una llave de apertura {, la cual señala el comienzo de las instrucciones que ejecutará el programa.

          .row(titulo="")
            .col-lg-6.col-12.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema3/img6.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              h5 Línea 3: System.out.println(“Hola mundo”);
              p Se encarga de mostrar el texto Hola mundo en la pantalla. Es importante notar que, al ejecutar el programa, el mensaje aparece sin las comillas dobles. En Java, las cadenas de texto se escriben entre comillas dobles. Aunque aún no se comprenda cada parte de esta instrucción, con el tiempo se logrará entender en detalle. Por ahora, si se desea imprimir texto en pantalla, basta con utilizar la instrucción mostrada en esta línea.

          .row(titulo="")
            .col-lg-6.col-12.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema3/img7.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              h5 Línea 4: } // Fin del método main
              p Inicia con una llave de cierre }, lo cual indica el término de las instrucciones que forman parte del método main. Al utilizar dos barras diagonales //, todo el contenido que sigue en esa misma línea es ignorado por el compilador de Java. Esto se conoce como comentario de línea y se utiliza para añadir aclaraciones o información que facilite la comprensión del código.

          .row(titulo="")
            .col-lg-6.col-12.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema3/img8.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              h5 Línea 5: } // Fin de la clase MiClase
              p Comienza también con una llave de cierre }, indicando el final del cuerpo de la clase MiClase. Esta línea incluye un comentario de línea, por lo que todo el texto que aparece después de las dos barras diagonales // será ignorado por el compilador hasta que se llegue a la siguiente línea. Todos los programas en Java seguirán esta misma estructura.
    p.mb-4.text-center Por otra parte, los símbolos en Java son importantes, pues son la estructura del programa como tal y para que su ejecución se dé, se tiene lo siguiente:
    SlyderF(columnas="col-lg-6 col-xl-4")
      .tarjeta.tarjeta-bg13.p-4
        .row.justify-content-center.mb-3
          .col-5
            img(src='@/assets/curso/temas/tema3/img9.svg' alt='')
        h5.text-center Los paréntesis ()
        p Los paréntesis cumplen dos funciones principales en un programa Java, las cuales son:
        ul.lista-ul.mb-0
          li.mb-0 #[b •] Delimitan listas de parámetros en los métodos.
          li.mb-0 #[b •] Alteran la prioridad en una expresión aritmética.

      .tarjeta.tarjeta-bg13.p-4
        .row.justify-content-center.mb-3
          .col-5
            img(src='@/assets/curso/temas/tema3/img10.svg' alt='')
        h5.text-center Las llaves {}
        p Las llaves en el lenguaje de programación Java se utilizan en los siguientes casos:
        ul.lista-ul.mb-0
          li.mb-0 #[b •] Definen un bloque de código, el cual puede estar anidado.
          li.mb-0 #[b •] Permiten declarar valores iniciales de los arreglos, separados por comas.

      .tarjeta.tarjeta-bg13.p-4
        .row.justify-content-center.mb-3
          .col-5
            img(src='@/assets/curso/temas/tema3/img11.svg' alt='')
        h5.text-center Los corchetes []
        p Los corchetes se emplean en un programa Java para:
        ul.lista-ul.mb-0
          li.mb-0 #[b •] Declarar arreglos (vectores).
          li.mb-0 #[b •] Acceder a los elementos de los arreglos.

      .tarjeta.tarjeta-bg13.p-4
        .row.justify-content-center.mb-3
          .col-5
            img(src='@/assets/curso/temas/tema3/img12.svg' alt='')
        h5.text-center El punto y coma «;»
        p El punto y coma indica el final de una instrucción en un programa Java.
        ul.lista-ul.mb-0
          li.mb-0 #[b •] Finaliza una línea de código.

      .tarjeta.tarjeta-bg13.p-4
        .row.justify-content-center.mb-3
          .col-5
            img(src='@/assets/curso/temas/tema3/img13.svg' alt='')
        h5.text-center La coma «,»
        p La coma se utiliza para:
        ul.lista-ul.mb-0
          li.mb-0 #[b •] Separar identificadores en declaraciones.

      .tarjeta.tarjeta-bg13.p-4
        .row.justify-content-center.mb-3
          .col-5
            img(src='@/assets/curso/temas/tema3/img14.svg' alt='')
        h5.text-center El punto «.»
        p El punto en un programa Java se utiliza para:
        ul.lista-ul.mb-0
          li.mb-0 #[b •] Acceder a métodos de una clase instanciada.
          li.mb-0 #[b •] Referenciar subpaquetes dentro de un paquete.

    separador
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 3.1 Tipos de datos, operadores y orden de evaluación
    .bloque-texto-g.C01.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img15.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Este apartado presenta los tipos de datos, los operadores y las reglas que determinan el orden de evaluación de las expresiones en Java. Estos elementos permiten definir la información que se almacena, realizar operaciones y comprender cómo se procesan las instrucciones de un programa.
    
    .titulo.mb-4(data-aos="fade-left")
      img(src='@/assets/curso/icon.svg', alt='')
      h5 a) Tipos de datos
    p.mb-4 Determinan la clase de valores que pueden almacenarse en una variable y las operaciones que pueden realizarse con ellos. En Java se clasifican en tipos de datos primitivos y tipos de datos de referencia.
    .row.justify-content-center.align-items-center.mb-3
      .col-lg-12
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 4.
          span Tipos de datos en Java
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-12
        .tabla-a.color-acento-contenido 
          .tabla-a   
            table
              thead
                tr.tarjeta-bg7
                  th Categoría
                  th Tipo
                  th Tamaño / característica
                  th Descripción
                  th Ejemplo
              tbody
                tr(style="background-color: #F0F8FF")
                  td.text-center Primitivo
                  td.text-center byte
                  td.text-center 8 #[i bits]
                  td Almacena números enteros en un rango reducido.
                  td.text-center byte edad = 25;
                tr
                  td.text-center Primitivo
                  td.text-center short
                  td.text-center 16 #[i bits]
                  td Almacena números enteros en un rango mayor que #[i byte].
                  td.text-center short cantidad = 1000;
                tr(style="background-color: #F0F8FF")
                  td.text-center Primitivo
                  td.text-center int
                  td.text-center 32 #[i bits]
                  td Almacena números enteros y es uno de los tipos más utilizados.
                  td.text-center int edad = 25;
                tr
                  td.text-center Primitivo
                  td.text-center long
                  td.text-center 64 #[i bits]
                  td Almacena números enteros que requieren un rango mayor que #[i int].
                  td.text-center long poblacion = 8000000L;
                tr(style="background-color: #F0F8FF")
                  td.text-center Primitivo
                  td.text-center float
                  td.text-center 32 #[i bits]
                  td Almacena números de punto flotante con precisión simple.
                  td.text-center float precio = 25.5f;
                tr
                  td.text-center Primitivo
                  td.text-center double
                  td.text-center 64 #[i bits]
                  td Almacena números de punto flotante con doble precisión.
                  td.text-center double promedio = 4.5;
                tr(style="background-color: #F0F8FF")
                  td.text-center Primitivo
                  td.text-center char
                  td.text-center 16 #[i bits]
                  td Almacena un carácter Unicode.
                  td.text-center char letra = 'A';
                tr
                  td.text-center Primitivo
                  td.text-center boolean
                  td.text-center #[i true o false]
                  td Almacena valores lógicos.
                  td.text-center boolean activo = true;
                tr(style="background-color: #F0F8FF")
                  td.text-center Referencia
                  td.text-center Clase
                  td.text-center Depende del objeto
                  td Permite trabajar con objetos creados a partir de una clase.
                  td.text-center Persona p = new Persona();
                tr
                  td.text-center Referencia
                  td.text-center Interfaz
                  td.text-center Depende de la implementación
                  td Define un conjunto de comportamientos que pueden ser implementados por una clase.
                  td.text-center List&lt;Integer&gt; lista;
                tr(style="background-color: #F0F8FF")
                  td.text-center Referencia
                  td.text-center Arreglo
                  td.text-center Depende de los elementos
                  td Permite almacenar varios valores del mismo tipo.
                  td.text-center int[] edades = {18, 20, 25};
                tr
                  td.text-center Referencia
                  td.text-center String
                  td.text-center Clase
                  td Permite representar cadenas de caracteres.
                  td.text-center String nombre = "Ana";

    p.mb-4 La declaración de una variable en Java sigue la estructura tipo nombreVariable;. Por ejemplo, int edad = 20; declara una variable de tipo entero y le asigna el valor 20. En los valores de tipo float, los literales decimales deben incluir el sufijo f o F, mientras que los valores de tipo double no requieren este sufijo.

    .row.justify-content-center.mb-5
      .col-lg-10
        .cajon.color-secundario.p-4
          p.mb-0 Java también proporciona clases envolventes para representar los tipos primitivos como objetos. Por ejemplo, Integer corresponde al tipo primitivo int, Double a double y Boolean a boolean.

    .titulo.mb-4(data-aos="fade-left")
      img(src='@/assets/curso/icon.svg', alt='')
      h5 b) Operadores
    p.mb-4 Son símbolos que permiten realizar diferentes operaciones sobre los datos de un programa. En Java se utilizan para asignar valores, realizar operaciones aritméticas, incrementar o disminuir valores, comparar datos y combinar expresiones lógicas.

    .row.justify-content-center.align-items-center.mb-3
      .col-lg-12
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 5.
          span Operadores en Java
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-12
        .tabla-a.color-acento-contenido
          table
            thead
              tr.tarjeta-bg7
                th Categoría
                th Operadores
                th Función
            tbody
              tr(style="background-color: #F0F8FF")
                td.text-center Asignación
                td.text-center =, +=, -=, *=, /=, %=
                td Permiten asignar un valor a una variable o modificarlo mediante una operación.
              tr
                td.text-center Aritméticos
                td.text-center +, -, *, /, %
                td Permiten realizar operaciones matemáticas como suma, resta, multiplicación, división y obtención del resto.
              tr(style="background-color: #F0F8FF")
                td.text-center Incremento y decremento
                td.text-center ++, --
                td Permiten aumentar o disminuir en una unidad el valor de una variable.
              tr
                td.text-center Relacionales
                td.text-center &lt;, &gt;, &lt;=, &gt;=, ==, !=
                td Permiten comparar valores y producen un resultado booleano (#[i true] o #[i false]).
              tr(style="background-color: #F0F8FF")
                td.text-center Lógicos
                td.text-center !, &&, ||
                td Permiten combinar expresiones booleanas mediante las operaciones de negación, conjunción (Y) y disyunción (O).

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta-bg2.p-3
          .row.justify-content-center.align-items-center
            .col-auto
                img(src='@/assets/curso/temas/tema3/img3-2.svg' alt='')
            .col-lg-10
              p.mb-0 Por ejemplo, los operadores de asignación permiten modificar directamente el valor de una variable, como en #[i n += 5;], que equivale a #[i n = n + 5;]. Los operadores relacionales permiten realizar comparaciones, mientras que los operadores lógicos permiten combinar sus resultados para construir condiciones más complejas.

    .titulo.mb-4(data-aos="fade-left")
      img(src='@/assets/curso/icon.svg', alt='')
      h5 c) Orden de evaluación
    p.mb-4 Determina la forma en que Java procesa los operadores que aparecen en una expresión. Para establecer este orden se consideran principalmente la precedencia, la asociatividad y el uso de paréntesis. En las expresiones que utilizan operadores lógicos como #[i &&] y #[i ||], también puede aplicarse la evaluación en cortocircuito.

    .row.justify-content-center.align-items-center.mb-3
      .col-lg-12
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 6.
          span Orden de evaluación de expresiones en Java
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-12
        .tabla-a.color-acento-contenido
          table
            thead
              tr.tarjeta-bg7
                th Elemento
                th Función
                th Ejemplo
                th Resultado o comportamiento
            tbody
              tr(style="background-color: #F0F8FF")
                td.text-center Precedencia
                td Determina qué operadores se evalúan primero.
                td.text-center 2 + 3 * 4
                td Primero 3 * 4 y después 2 + 12; resultado: 14.
              tr
                td.text-center Asociatividad
                td Determina el sentido de evaluación cuando los operadores tienen la misma precedencia.
                td.text-center 10 - 5 - 2
                td Se evalúa de izquierda a derecha: (10 - 5) - 2 = 3.
              tr(style="background-color: #F0F8FF")
                td.text-center Paréntesis
                td Permiten establecer o modificar el orden de evaluación.
                td.text-center (2 + 3) * 4
                td Primero 2 + 3 y después 5 * 4; resultado: 20.
              tr
                td.text-center Cortocircuito
                td Detiene la evaluación de una expresión lógica cuando su resultado ya puede determinarse.
                td.text-center false && verificar()
                td verificar() no se ejecuta porque el resultado de && ya es #[i false].

    p.mb-0 En síntesis, comprender la precedencia, la asociatividad, el uso de paréntesis y la evaluación en cortocircuito permite interpretar correctamente las expresiones y prever el resultado de las operaciones realizadas por un programa en Java.

    separador
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 3.2 Expresiones, funciones y comentarios

    p.mb-4 Este apartado aborda los elementos básicos que permiten construir instrucciones significativas en JavaScript, organizar la lógica del programa y documentar el código, facilitando su comprensión, reutilización y mantenimiento dentro del proceso de desarrollo de #[i software].

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        .titulo.mb-4(data-aos="fade-left")
          img(src='@/assets/curso/icon.svg', alt='')
          h5 Expresiones
        p.mb-4 En JavaScript, una expresión es cualquier fragmento de código que produce un valor. Las expresiones son la base de la programación, ya que permiten realizar cálculos, comparaciones, asignaciones y evaluaciones lógicas dentro de un programa.
        p.mb-0 Los siguientes son los tipos de expresiones:
    
    .row.justify-content-center.BG02.p-4
      .col-lg-4.d-none.d-lg-block
        figure(data-aos="zoom-in")
          img(src="@/assets/curso/temas/tema3/img21.png", alt="").img400.m-auto
      .col-lg-8
        p.mb-5
        SlyderF.custom.mb-5(columnas="col-lg-12 col-xl-12")
          .tarjeta.tarjeta--slyder.p-4
            p.mb-3 #[b • Expresiones aritméticas]
            p.mb-3 Se utilizan para realizar operaciones matemáticas como suma, resta, multiplicación y división.
            p.mb-3 Ejemplo:
            .p-2
              .tarjeta--fondo4.p-2
                p.mb-0.text-white let resultado = 5 + 3 * 2; // Resultado: 11
          .tarjeta.tarjeta--slyder.p-4
            p.mb-3 #[b • Expresiones relacionales]
            p.mb-3 Sirven para comparar valores y devuelven un resultado booleano (true o false).
            p.mb-3 Ejemplo:
            .p-2
              .tarjeta--fondo4.p-2
                p.mb-0.text-white let esMayor = 10 > 5; // true
          .tarjeta.tarjeta--slyder.p-4
            p.mb-3 #[b • Expresiones lógicas]
            p.mb-3 Permiten combinar condiciones utilizando operadores como AND (&&), OR (||) y NOT (!).
            p.mb-3 Ejemplo:
            .p-2
              .tarjeta--fondo4.p-2
                p.mb-0.text-white let valido = (10 > 5) && (3 < 8); // true
          .tarjeta.tarjeta--slyder.p-4
            p.mb-3 #[b • Expresiones de asignación]
            p.mb-3 Se usan para asignar valores a variables.
            p.mb-3 Ejemplo:
            .p-2
              .tarjeta--fondo4.p-2
                p.mb-0.text-white let x = 10;
          .tarjeta.tarjeta--slyder.p-4
            p.mb-3 #[b • Expresiones de cadena]
            p.mb-3 Permiten trabajar con texto (strings).
            p.mb-3 Ejemplo:
            .p-2
              .tarjeta--fondo4.p-2
                p.mb-0.text-white let saludo = 'Hola ' + 'mundo';
          .tarjeta.tarjeta--slyder.p-4
            p.mb-3 #[b • Expresiones de función]
            p.mb-3 Son funciones definidas dentro de una expresión.
            p.mb-3 Ejemplo:
            .p-2
              .tarjeta--fondo4.p-2
                p.mb-0.text-white const suma = function(a, b) { return a + b; };
    .row.justify-content-center.align-items-center
      .col-lg-10
        .tarjeta--fondo10.p-4.mb-4
          p.mb-2 Las expresiones en JavaScript se evalúan siguiendo reglas de precedencia, asociatividad y uso de paréntesis.
          p.mb-2 Ejemplo:
          p.mb-0.text-white.tarjeta--fondo5.p-2 let resultado = (2 + 3) * 4; // 20
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-5
            p.mb-2 Los siguientes son algunos ejercicios prácticos:
            p.mb-0 #[b Ejercicio 1]
            p.mb-0 let a = 10 + 5 * 2; // ¿Cuál es el resultado?
            p.mb-0 #[b Ejercicio 2]
            p.mb-0 let b = (10 + 5) * 2; // ¿Cuál es el resultado?
            p.mb-0 #[b Ejercicio 3]
            p.mb-0 let c = (5 > 3) && (2 < 1); // ¿Cuál es el resultado?
          .col-lg-7.d-none.d-lg-block
            figure
              img(src="@/assets/curso/temas/tema3/img22.png", alt="").img400.m-auto
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-3.col-6.mb-4.mb-lg-0
        figure
          img(src="@/assets/curso/temas/tema3/img23.svg", alt="").img400.m-auto
      .col-lg-9
        .titulo.mb-4(data-aos="fade-left")
          img(src='@/assets/curso/icon.svg', alt='')
          h5 Funciones
        p.mb-3 En JavaScript, una función es un bloque de código diseñado para realizar una tarea específica. Las funciones permiten reutilizar código, organizar mejor los programas y facilitar el mantenimiento.
        p.mb-3 Una función se define utilizando la palabra reservada function, seguida de un nombre, paréntesis y un bloque de código.
        .p-4.tarjeta--fondo4
            .row.align-items-center
              .col-md-8.mb-3.mb-md-0
                  p.text-white.mb-1 Ejemplo:
                  p.text-white.mb-1 function saludar() {
                  p.text-white.mb-1   console.log('Hola mundo');
                  p.text-white.mb-1 }
    p.mb-4 Las siguientes son las funciones más destacadas y sus ejemplificaciones:
    .row.justify-content-center.mb-4
      .col-lg-4.mb-3
        .cajon.c01.p-4.h-100
          p.mb-3 #[b Funciones con parámetros]
          p.mb-0 Las funciones pueden recibir datos de entrada llamados parámetros.
          p.mb-0 #[b Ejemplo: ]
          .tarjeta--fondo4.p-2
            p.mb-0.text-white function sumar(a, b) {
            p.mb-0.text-white  return a + b;
            p.mb-0.text-white }
      .col-lg-4.mb-3
        .tarjeta-bg3.p-4.h-100
          p.mb-3 #[b Funciones con retorno]
          p.mb-0 Una función puede devolver un valor utilizando la palabra return.
          p.mb-0 #[b Ejemplo: ]
          .tarjeta--fondo5.p-2
            p.mb-0.text-white let resultado = sumar(5, 3); // 8
      .col-lg-4.mb-3
        .cajon.c01.p-4.h-100
          p.mb-3 #[b Funciones anónimas]
          p.mb-0 Son funciones sin nombre que pueden asignarse a una variable.
          p.mb-0 #[b Ejemplo: ]
          .tarjeta--fondo4.p-2
            p.mb-0.text-white const saludo = function() {
            p.mb-0.text-white  console.log('Hola');
            p.mb-0.text-white };
      .col-lg-4.mb-3
        .tarjeta-bg3.p-4.h-100
          p.mb-3 #[b Funciones flecha (#[i arrow functions])]
          p.mb-0 Son una forma más corta de escribir funciones.
          p.mb-0 #[b Ejemplo: ]
          .tarjeta--fondo5.p-2
            p.mb-0.text-white const suma = (a, b) => a + b;
      .col-lg-4.mb-3
        .cajon.c01.p-4.h-100
          p.mb-3 #[b Ámbito (#[i scope]) de las funciones]
          p.mb-0 El #[i scope] define el alcance de las variables dentro de una función.
          p.mb-0 #[b Ejemplo: ]
          .tarjeta--fondo4.p-2
            p.mb-0.text-white function ejemplo() {
            p.mb-0.text-white  let x = 10;
            p.mb-0.text-white }
            p.mb-0.text-white // x no es accesible fuera de la función
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-10
        .row.justify-content-center.align-items-center.mb-4
          .col-lg-5.order-2.order-lg-1
            p.mb-2 Igualmente, se presentan los siguientes ejercicios prácticos:
            p.mb-0 #[b Ejercicio 1]
            p.mb-0 Crear una función que reciba un número y devuelva su cuadrado.
            p.mb-0 #[b Ejercicio 2]
            p.mb-0 Crear una función que reciba un nombre y muestre un saludo.
            p.mb-0 #[b Ejercicio 3]
            p.mb-0 Crear una función flecha que multiplique dos números.
          .col-lg-7.col-10.mb-4.mb-lg-0.order-1.order-lg-2
            figure
              img(src="@/assets/curso/temas/tema3/img24.png", alt="").img400.m-auto
        p.mb-4.text-center Comprendiendo lo que tiene que ver tanto con las expresiones como con las funciones, se relaciona la importancia de cada una:
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-10
        .tarjeta--container.row
          .col-md.tarjeta.tarjeta-bg2.p-5
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema3/img25.svg', alt='')
              
            h5.text-center Importancia de las funciones
            p Las funciones son fundamentales en JavaScript porque permiten dividir el código en partes más pequeñas, reutilizables y fáciles de entender; comprender el uso de funciones en JavaScript es esencial para desarrollar aplicaciones eficientes y bien estructuradas.
          .col-md.tarjeta.tarjeta-bg3.p-5
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema3/img26.svg', alt='')
            h5.text-center Importancia de las expresiones
            p.mb-2 Las expresiones permiten construir la lógica de un programa, realizar cálculos, evaluar condiciones y manipular datos.
            p.mb-2 Comprender las expresiones en JavaScript es fundamental para desarrollar programas eficientes. Estas permiten realizar múltiples operaciones y son esenciales en cualquier aplicación.
    .titulo.mb-4(data-aos="fade-left")
      img(src='@/assets/curso/icon.svg', alt='')
      h5 Comentarios
    p.mb-4 Los comentarios en el lenguaje de programación Java se utilizan para añadir anotaciones o mensajes aclaratorios dentro del código; no son ejecutados y se clasifican en tres tipos:
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-8.order-2.order-lg-1
        AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Comentarios de una sola línea")
            .col-md-12.mb-4.mb-md-0
              p.mb-3 Inician con los caracteres // seguidos del contenido del comentario.
              p.mb-0 #[b Ejemplo: ]
              .tarjeta--fondo4.p-4
                p.mb-0.text-white // Atributos int a,b,c; // a,b,c representan atributos enteros de la clase
          .row(titulo="Comentarios de bloques")
            .col-md-12.mb-4.mb-md-0
              p.mb-3 Comienzan con los caracteres /* en cualquier parte de la línea de código, continúan con el contenido del comentario y finalizan con los caracteres /.
              p.mb-0 #[b Ejemplo: ]
              .tarjeta--fondo4.p-4
                p.mb-0.text-white /
                p.mb-0.text-white  Texto de los comentarios en bloque
                p.mb-0.text-white  / comentarios en bloque
                p.mb-0.text-white  /
                p.mb-0.text-white  xxxxxxxxxxxxxxxxxx
                p.mb-0.text-white  */
          .row(titulo="Comentarios de documentación")
            .col-md-12.mb-4.mb-md-0
              p.mb-3 Se utilizan para documentar el programa. Empiezan con los caracteres /** en cualquier parte de la línea de instrucción, luego se escribe el contenido del comentario y finalizan con los caracteres /.
              p.mb-0 #[b Ejemplo: ]
              .tarjeta--fondo4.p-4
                p.mb-0.text-white /*
                p.mb-0.text-white  Texto de los comentarios de documentación
                p.mb-0.text-white  /
                p.mb-0.text-white  Este es un ejemplo de comentarios de documentación:
                p.mb-0.text-white  /* * *
                p.mb-0.text-white  @author jorger
                p.mb-0.text-white  */
      .col-lg-4.col-8.mb-4.mb-lg-0.order-1.order-lg-2
        figure
          img(src='@/assets/curso/temas/tema3/img27.png', alt='')
    separador
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 3.3 Estructuras de selección
    p.mb-4 Las estructuras de selección en JavaScript permiten tomar decisiones dentro de un programa, ejecutando diferentes bloques de código según se cumplan o no determinadas condiciones. Las siguientes son este tipo de estructuras:
    TabsC.color-acento-botones.mb-5
      .py-3.py-md-4(titulo="Estructura if")
        .px-4
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-6.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema3/img28.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              p.mb-3 Se utiliza para ejecutar un bloque de código si una condición es verdadera.
                p.mb-0 #[b Ejemplo: ]
                .tarjeta--fondo4.p-3
                  p.mb-0.text-white if (x > 0) {
                  p.mb-0.text-white   console.log('Número positivo');
                  p.mb-0.text-white }
      .py-3.py-md-4(titulo="Estructura if - else")
        .px-4
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/temas/tema3/img29.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              p.mb-3 Permite ejecutar un bloque de código si la condición es verdadera y otro si es falsa.
                p.mb-0 #[b Ejemplo: ]
                .tarjeta--fondo4.p-3
                  p.mb-0.text-white if (x > 0) {
                  p.mb-0.text-white    console.log('Positivo');
                  p.mb-0.text-white  } else {
                  p.mb-0.text-white    console.log('Negativo o cero');
                  p.mb-0.text-white  }
      .py-3.py-md-4(titulo="Estructura if - else if - else")
        .px-4
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/temas/tema3/img30.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              p.mb-3 Se utiliza para evaluar múltiples condiciones.
                p.mb-0 #[b Ejemplo: ]
                .tarjeta--fondo4.p-3
                  p.mb-0.text-white if (x > 0) {
                  p.mb-0.text-white    console.log('Positivo');
                  p.mb-0.text-white  } else if (x < 0) {
                  p.mb-0.text-white    console.log('Negativo');
                  p.mb-0.text-white  } else {
                  p.mb-0.text-white    console.log('Cero');
                  p.mb-0.text-white  }
      .py-3.py-md-4(titulo="Estructura switch")
        .px-4
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/temas/tema3/img31.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              p.mb-3 Permite seleccionar una opción entre múltiples casos.
                p.mb-0 #[b Ejemplo: ]
                .tarjeta--fondo4.p-3
                  p.mb-0.text-white switch (dia) {
                  p.mb-0.text-white    case 1:
                  p.mb-0.text-white      console.log('Lunes');
                  p.mb-0.text-white      break;
                  p.mb-0.text-white    case 2:
                  p.mb-0.text-white      console.log('Martes');
                  p.mb-0.text-white      break;
                  p.mb-0.text-white    default:
                  p.mb-0.text-white      console.log('Otro día');
                  p.mb-0.text-white  }
      .py-3.py-md-4(titulo="Operador ternario")
        .px-4
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/temas/tema3/img32.png', alt='')
            .col-lg-6.mb-4.mb-md-0
              p.mb-3 Es una forma abreviada de la estructura if-else.
                p.mb-0 #[b Ejemplo: ]
                .tarjeta--fondo4.p-3
                  p.mb-0.text-white let mensaje = (x > 0) ? 'Positivo' : 'Negativo';
        
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-4
            figure
              img(src='@/assets/curso/temas/tema3/img33.svg', alt='')
          .col-lg-8
            p.mb-3 #[b Ejercicios propuestos:]
            ol.lista-ol--cuadro
              li
              .lista-ol--cuadro__vineta
                span 1
              |  Crear un programa que determine si un número es mayor de edad.
              li
              .lista-ol--cuadro__vineta
                span 2
              |  Crear un programa que determine el mayor de dos números.
              li
              .lista-ol--cuadro__vineta
                span 3
              |  Usar switch para mostrar el nombre de un mes según su número.
        p.mb-4 Soluciones sugeridas:
        .row.justify-content-center.align-items-center.mb-4
          .col-lg-4.h-100
            .tarjeta--fondo4.p-2
              ol.lista-ol--cuadro
              li.text-white
                .lista-ol--cuadro__vineta
                  span 1
                |  if (edad >= 18) {<br>
                |    console.log('Mayor de edad');<br>
                |  } else {<br>
                |    console.log('Menor de edad');<br>
                |  }
          .col-lg-4.h-100
            .tarjeta--fondo4.p-2
              ol.lista-ol--cuadro
              li.text-white
                .lista-ol--cuadro__vineta
                  span 2
                |  if (a > b) {<br>
                |    console.log(a);<br>
                |  } else {<br>
                |    console.log(b);<br>
                |  }
          .col-lg-4.h-100
            .tarjeta--fondo4.p-2
              ol.lista-ol--cuadro
              li.text-white
                .lista-ol--cuadro__vineta
                  span 3
                |  switch (mes) {<br>
                |  case 1: console.log('Enero'); break;<br>
                |  case 2: console.log('Febrero'); break;<br>
                |  default: console.log('Otro');<br>
                |  }
        .cajon.cajon.color-secundario.p-4
          p.mb-0 Las estructuras de selección son fundamentales en JavaScript, ya que permiten controlar el flujo del programa y tomar decisiones basadas en condiciones.
    separador
    #t_3_4.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 3.4 Estructuras de repetición (for y while)
    p.mb-4 Las estructuras de repetición permiten ejecutar un conjunto de instrucciones de manera repetida, ya sea un número determinado de veces o mientras se cumpla una condición específica. En Java, los bucles for y while son ampliamente utilizados para automatizar tareas repetitivas y controlar el flujo del programa de forma eficiente, según las necesidades de cada situación.
    .titulo.mb-4(data-aos="fade-left")
      img(src='@/assets/curso/icon.svg', alt='')
      h5 Repetición sobre un rango determinado: for
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7
        p.mb-3 El for es una estructura de repetición que permite ejecutar un conjunto de instrucciones tantas veces como sea necesario. Esta estructura consta de tres partes fundamentales: la variable de inicio, la condición y el incremento.
        p.mb-3 El bucle for permite repetir un bloque de instrucciones mientras se cumpla una condición. Su sintaxis es la siguiente:
        .p-2.tarjeta--fondo5.p-3
            .row.align-items-center
              .col-md-8.mb-3.mb-md-0
                  p.text-white.mb-1 for (inicialización; condición; incremento)
                  p.text-white.mb-1  {
                  p.text-white.mb-1  // Bloque de instrucciones
                  p.text-white.mb-1  }
      .col-lg-5
        figure
          img(src="@/assets/curso/temas/tema3/img39.svg", alt="").img400.m-auto
    .BG01.px-5
      .row.justify-content-center.align-items-center
        .col-lg-10
          p.mb-4 En la sección de iniciación se puede declarar una variable de control del ciclo, cuyo alcance estará limitado al propio bucle. Tanto en la parte de iniciación como en la de incremento se pueden incluir varias expresiones separadas por comas, pero esto no es permitido en la parte de la condición.
          p.mb-4 La condición debe ser una expresión booleana o una expresión que se evalúe como un valor booleano.
          p.mb-4 Ejemplos:
          .tarjeta--fondo4.p-4.mb-4
            p.text-white.mb-1 for (int i=0;i<=5;i++){
            p.text-white.mb-1  /* variable inicial = i, condición i menor o igual a 5, incremento i++ equivalente a i+1 */
            p.text-white.mb-1  System.out.println("hola");
            p.text-white.mb-1  }
          figure.mb-4
            img(src="@/assets/curso/temas/tema3/img34.png", alt="").img400.m-auto
          p.mb-4 Como resultado, este bucle for imprimirá 6 veces la palabra hola, ya que en Java el ciclo for inicia desde el valor definido (en este caso 0). Por lo tanto, si se requieren 10 repeticiones, la condición debería ser i<=9, comenzando desde cero.
          .tarjeta--fondo5.p-4.mb-4
            p.text-white.mb-1 for (int j = 1; j< 4;j++){
            p.text-white.mb-1  System.out.print(objArray01.muestra(j)+" ");
            p.text-white.mb-1  }
    .titulo.mb-4(data-aos="fade-left")
      img(src='@/assets/curso/icon.svg', alt='')
      h5 Repeticiones condicionales: while
    p El while, al igual que el for, es una estructura de repetición; la diferencia principal es que el while no requiere una variable de control ni un incremento explícito, ya que solo necesita una condición para ejecutarse. El while evalúa dicha condición y, si se cumple, ejecuta el bloque de instrucciones; posteriormente, vuelve a evaluar la condición. Cuando esta deja de cumplirse, el ciclo se detiene y el programa continúa con su flujo normal.
    p.mb-4 Su sintaxis y funcionamiento son similares a los de C/C++. En la estructura while, la condición se evalúa antes de ejecutar el bloque de instrucciones.
    .row.justify-content-center.align-items-center
      .col-lg-10
        .row.justify-content-center.align-items-center.mb-4
          .col-lg-6
            .tarjeta--fondo4.p-4
              p.text-white.mb-1 while(condición) {
              p.text-white.mb-1  // Bloque de instrucciones
              p.text-white.mb-1  }
              p.text-white.mb-1  Ejemplo
              p.text-white.mb-1
              p.text-white.mb-1  int A=0;
              p.text-white.mb-1  int B=5;
              p.text-white.mb-1  while(A < B) { // repetir mientras A sea menor que B //
              p.text-white.mb-1  A=A+1;
              p.text-white.mb-1  }
          .col-lg-6
            figure
              img(src="@/assets/curso/temas/tema3/img35.png", alt="").img400.m-auto
        p.mb-0 Este ejemplo del ciclo while finalizará cuando A deje de ser menor que B; es decir, cuando la variable A alcance el valor de 6. En cada iteración del ciclo, A se incrementa en 1; por lo tanto, cuando A sea igual a 6, la condición ya no se cumple y el ciclo termina.
    separador
    #t_3_5.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 3.5 Estructuras de salto (continue, break, return)
    p.mb-4 Las estructuras de salto en JavaScript permiten alterar el flujo normal de ejecución de un programa. Estas estructuras son útiles para controlar ciclos, salir de bloques de código o devolver valores desde funciones.
    .row.justify-content-center.mb-4
      .col-lg-4
        .tarjeta-bg10.p-4.h-100
          p.mb-2 #[b Sentencia continue]
          p.mb-2 La sentencia continue se utiliza para omitir la iteración actual de un bucle y continuar con la siguiente.
          p.mb-2 #[b Ejemplo:]
          .tarjeta--fondo5.p-4.mb-4
              p.text-white.mb-1 for (let i = 0; i < 5; i++) {
              p.text-white.mb-1   if (i === 2) {
              p.text-white.mb-1     continue;
              p.text-white.mb-1   }
              p.text-white.mb-1   console.log(i);
              p.text-white.mb-1 }
              p.text-white.mb-1 // Imprime: 0, 1, 3, 4
      .col-lg-4
        .tarjeta-bg10.p-4.h-100
          p.mb-2 #[b Sentencia break]
          p.mb-2 La sentencia break se utiliza para terminar de forma inmediata un bucle o una estructura switch.
          p.mb-2 #[b Ejemplo:]
          .tarjeta--fondo5.p-4.mb-4
              p.text-white.mb-1 for (let i = 0; i < 5; i++) {
              p.text-white.mb-1    if (i === 3) {
              p.text-white.mb-1      break;
              p.text-white.mb-1    }
              p.text-white.mb-1    console.log(i);
              p.text-white.mb-1  }
              p.text-white.mb-1  // Imprime: 0, 1, 2
      .col-lg-4
        .tarjeta-bg10.p-4.h-100
          p.mb-2 #[b Sentencia return]
          p.mb-2 La sentencia return se utiliza dentro de una función para devolver un valor y finalizar su ejecución.
          p.mb-2 #[b Ejemplo:]
          .tarjeta--fondo5.p-4.mb-4
              p.text-white.mb-1 function sumar(a, b) {
              p.text-white.mb-1    return a + b;
              p.text-white.mb-1  }
              p.text-white.mb-1  let resultado = sumar(3, 4);
              p.text-white.mb-1  // resultado = 7

    p.mb-4.text-center Las diferencias principales entre estas sentencias son:

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-8.mb-4.mb-lg-0
        .bloque-texto-gg.tarjeta--fondo7
          .bloque-texto-gg__texto.p-4
            h5.mb-0 break
            p.mb-0 Finaliza completamente un ciclo o switch.
          .bloque-texto-gg__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema3/img36.svg')})`}"
          )           
      .col-lg-4.col-8.mb-4.mb-lg-0
        .bloque-texto-gg.tarjeta--fondo7
          .bloque-texto-gg__texto.p-4
            h5.mb-0 continue
            p.mb-0 Salta a la siguiente iteración del ciclo.
          .bloque-texto-gg__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema3/img37.svg')})`}"
          )           
      .col-lg-4.col-8
        .bloque-texto-gg.tarjeta--fondo7
          .bloque-texto-gg__texto.p-4
            h5.mb-0 return
            p.mb-0 Finaliza una función y devuelve un valor.
          .bloque-texto-gg__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema3/img38.svg')})`}"
          )  
    p.mb-4.text-center Ejercicios propuestos
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4
        .cajon.c01.p-4.h-100
          p.mb-2 Crear un ciclo que imprima números del 1 al 10, pero que se detenga cuando llegue a 6.

          .tarjeta--fondo4.p-4.mb-4
              p.text-white.mb-1 for (let i = 1; i <= 10; i++) {
              p.text-white.mb-1    if (i === 6) break;
              p.text-white.mb-1    console.log(i);
              p.text-white.mb-1  }
      .col-lg-4
        .cajon.c01.p-4.h-100
          p.mb-2 Crear un ciclo que imprima números del 1 al 10, pero que omita el número 5.

          .tarjeta--fondo4.p-4.mb-4
              p.text-white.mb-1 for (let i = 1; i <= 10; i++) {
              p.text-white.mb-1    if (i === 5) continue;
              p.text-white.mb-1    console.log(i);
              p.text-white.mb-1  }
      .col-lg-4
        .cajon.c01.p-4.h-100
          p.mb-2 Crear una función que reciba un número y retorne si es par o impar.

          .tarjeta--fondo4.p-4.mb-4
              p.text-white.mb-1 function esPar(n) {
              p.text-white.mb-1    return (n % 2 === 0) ? 'Par' : 'Impar';
              p.text-white.mb-1  }
              br
    .row.justify-content-center
      .col-lg-10.col-12
        p Las estructuras de salto son herramientas clave en JavaScript que permiten controlar el flujo de ejecución de manera eficiente, facilitando la construcción de programas más claros y optimizados.
</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
