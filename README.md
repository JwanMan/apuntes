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

Las asignaturas de ingeniería informática que se incluyen son las siguientes:

* `fc`: Fundamentos de Computadores.
* `ip`: Introducción a la Programación.
* `logic`: Fundamentos Lógicos de la Informática.
* `etc`: Estructura y Tecnología de Computadores.
* `ffi`: Fundamentos Físicos de la Informática.
* `tp`: Tecnología de la Programación.
* `aed1`: Algoritmos y Estructuras de Datos I.

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
