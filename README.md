# Apuntes

Este repositorio contiene apuntes para las asignaturas del PCEO en Matemáticas e
Ingeniería Informática de la Universidad de Murcia. Estos apuntes no son
oficiales ni están afiliados de algún modo a la Universidad de Murcia.
Cualquiera es libre de enviar correcciones, modificaciones ante cambios en los
contenidos académicos u otras mejoras.

Por el momento, las asignaturas de matemáticas de las que se incluyen apuntes
son las siguientes:

* `algl`: Álgebra Lineal.
* `cyn`: Conjuntos y Números.
* `fuvr1`: Funciones de Una Variable Real I.
* `fuvr2`: Funciones de Una Variable Real II.
* `gae`: Geometría Afín y Euclídea.
* `tem`: Topología de Espacios Métricos.
* `aalg`: Ampliación de Álgebra y Geometría.
* `fvv1`: Funciones de Varias Variables I.
* `fvv2`: Funciones de Varias Variables II (falta el capítulo 2).
* `fvv3`: Funciones de Varias Variables III (sólo PDF).
* `edo`: Ecuaciones Diferenciales Ordinarias (sólo PDF).
* `epe`: Elementos de Probabilidad y Estadística (sólo PDF).
* `cn`: Cálculo Numérico (sólo PDF).
* `fvc`: Funciones de Variable Compleja (falta la primera parte).

Las asignaturas de ingeniería informática que se incluyen son las siguientes:

* `fc`: Fundamentos de Computadores.
* `ip`: Introducción a la Programación.
* `logic`: Fundamentos Lógicos de la Informática.
* `etc`: Estructura y Tecnología de Computadores.
* `ffi`: Fundamentos Físicos de la Informática.
* `tp`: Tecnología de la Programación.
* `iso`: Introducción a los Sistemas Operativos.
* `poo`: Programación Orientada a Objetos.
* `aed1`: Algoritmos y Estructuras de Datos I.
* `aed2`: Algoritmos y Estructuras de Datos II (sólo PDF).
* `pcd`: Programación Concurrente y Distribuida (sólo PDF).
* `rc`: Redes de Comunicaciones (sólo PDF).

Los apuntes están escritos con [LyX](https://www.lyx.org/). En cada directorio,
el fichero `n.lyx` es el fichero principal con los apuntes de la asignatura.
En distribuciones basadas en Debian, LyX y todo lo necesario de
[TeX Live](https://www.tug.org/texlive/) se pueden instalar mediante
`sudo apt install lyx texlive-full`, si bien realmente muchos de los paquetes
que se instalan con esta orden no son necesarios.

Para compilar los apuntes, `lyx -e pdf2 n.lyx` convierte a PDF y
`lyx -e html n.lyx` convierte a HTML, aunque también se puede usar la interfaz
gráfica de LyX. Si encuentra problemas de accesibilidad, no dude en enviar una
"Issue" al respecto.

Algunos apuntes solo están disponibles en PDF debido a que se perdió la fuente y
solo se muestra la versión para venta o versión preliminar a venta, lo que es
desafortunado porque el formato es difícilmente editable y plantea problemas de
accesibilidad, por lo que toda aportación de apuntes para estas asignaturas es
bien recibida, así como para las asignaturas en las que faltan apuntes.

No obstante, se anima a todo interesado que esté en Murcia a comprar los
ejemplares que necesite, pues los beneficios se destinan a
[Project Elea](https://projectelea.org/about-us/), un grupo de voluntarios que
trabajan con los residentes del campo de refugiados de Eleonas, Grecia, para
mejorar los estándares de vida y el bienestar comunitario de estas personas que
han perdido todo a causa de la guerra. El precio mínimo es de tan solo 3 euros
para una asignatura o 10 euros para 6 asignaturas, y solo se vende de las
asignaturas que están completas. Para asignaturas sólo en versión preliminar en
PDF, se eliminará la marca de agua.
