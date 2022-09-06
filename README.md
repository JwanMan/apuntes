# Apuntes

Apuntes para las asignaturas del PCEO en Matemáticas e Ingeniería Informática de
la Universidad de Murcia.

El propósito de estos apuntes es servir de repaso a la hora de estudiar la
teoría para un examen o de referencia al hacer ejercicios. Por supuesto, no son
un sustituto de ir entendiendo los contenidos y practicar con ejercicios. Estos
apuntes no están afiliados de ningún modo a la Universidad de Murcia.

Por el momento, las asignaturas de matemáticas de las que se incluyen apuntes
son las siguientes:

Se incluyen las siguientes asignaturas:
* De matemáticas:
  * `algl`: Álgebra Lineal.
  * `cyn`: Conjuntos y Números.
  * `fuvr1`: Funciones de Una Variable Real I.
  * `fuvr2`: Funciones de Una Variable Real II.
  * `gae`: Geometría Afín y Euclídea.
  * `tem`: Topología de Espacios Métricos.
  * `epe`: Elementos de Probabilidad y Estadística (sólo PDF).
  * `aalg`: Ampliación de Álgebra y Geometría.
  * `fvv1`: Funciones de Varias Variables I.
  * `fvv2`: Funciones de Varias Variables II.
  * `fvv3`: Funciones de Varias Variables III (sólo PDF).
  * `edo`: Ecuaciones Diferenciales Ordinarias (sólo PDF).
  * `anm`: Análisis Numérico Matricial.
  * `cn`: Cálculo Numérico (sólo PDF).
  * `ol`: Optimización Lineal (sólo PDF).
  * `ga`: Grupos y Anillos.
  * `ts`: Topología de Superficies.
  * `fvc`: Funciones de Variable Compleja (falta la primera parte).
  * `gcs`: Geometría de Curvas y Superficies.
  * `ggs`: Geometría Global de Superficies.
  * `graf`: Grafos y Optimización Discreta.
  * `mne`: Métodos Numéricos de las Ecuaciones Diferenciales.
  * `ealg`: Ecuaciones algebraicas.
* De informática:
  * `fc`: Fundamentos de Computadores.
  * `ip`: Introducción a la Programación.
  * `fli`: Fundamentos Lógicos de la Informática.
  * `etc`: Estructura y Tecnología de Computadores.
  * `ffi`: Fundamentos Físicos de la Informática.
  * `tp`: Tecnología de la Programación.
  * `iso`: Introducción a los Sistemas Operativos.
  * `poo`: Programación Orientada a Objetos.
  * `aed1`: Algoritmos y Estructuras de Datos I.
  * `aed2`: Algoritmos y Estructuras de Datos II (sólo PDF).
  * `pcd`: Programación Concurrente y Distribuida (sólo PDF).
  * `rc`: Redes de Comunicaciones (sólo PDF).
  * `aec`: Ampliación y Estructura de Computadores (sólo PDF).
  * `bd`: Bases de Datos.
  * `cc`: Compiladores.
  * `ar`: Ampliación de Redes (sólo PDF).
  * `st`: Servicios Telemáticos.
  * `aoc`: Arquitectura y Organización de Computadores.
  * `si`: Sistemas Inteligentes.
  * `tds`: Tecnologías de Desarrollo de Software.
  * `pds`: Procesos de Desarrollo de Software.
  * `gpds`: Gestión de Proyectos de Desarrollo de Software.
* En progreso:
  * `ac`: Álgebra Conmutativa.
  * `af`: Análisis Funcional.
  * `dsi`: Desarrollo de Sistemas Inteligentes.
  * `mc`: Modelos de Computación.
  * `pia`: Programación para la IA.

## Venta benéfica
Si está en Murcia, puede comprar versiones impresas de los apuntes (ver imagen)
por un mínimo de 5 euros la asignatura o 19 euros por 6 asignaturas, y **el 100% 
de los beneficios** se destina a
**[Project Elea](https://projectelea.org/about-us/)**, un grupo de voluntarios
que trabajan con los residentes del campo de refugiados de Eleonas, Grecia, para
mejorar los estándares de vida y el bienestar comunitario de estas personas que
han perdido todo a causa de la guerra.

## Descargar
Necesitaremos instalar [LyX](https://www.lyx.org/) para ver los documentos,
[Git](https://git-scm.com) para descargarlos o contribuir a ellos (aunque esto 
también se puede hacer con la interfaz gráfica de GitHub) y puede que también
[TeXLive](https://tug.org/texlive/), si al compilar nos da error.

En distribuciones Linux basadas en [Debian](https://www.debian.org), como
[Trisquel](https://trisquel.info), [PureOS](https://www.pureos.net),
[Ubuntu](https://ubuntu.com) o [Linux Mint](https://linuxmint.com), podemos
descargar todo el software necesario con la orden
`sudo apt install git lyx texlive-full` en la línea de comandos.

Para descargar los apuntes con Git, usamos el comando
```sh
git clone https://github.com/JwanMan/apuntes
```

Descargar solo algunos apuntes es algo más complicado. Para descargar,
por ejemplo, solo `fuvr1` y `cyn`, haríamos lo siguiente:

```sh
git init apuntes
cd apuntes
git remote add -f origin https://github.com/JwanMan/apuntes
git config core.sparseCheckout true
echo fuvr1 >> .git/info/sparse-checkout
echo cyn >> .git/info/sparse-checkout
git pull origin master
```

## Compilar

En cada directorio, el fichero `n.lyx` es el fichero principal con los apuntes
de la asignatura. Podemos compilarlos con la interfaz gráfica
(`Archivo > Exportar`) o mediante la orden `lyx -e <formato> n.lyx`, donde
`<formato>` es `pdf2` para exportar a PDF o `html` para convertir a HTML.

## Contribuciones

Quien quiera puede contribuir mediante _Issues_ y _Pull Requests_. Por ejemplo,
interesan especialmente las contribuciones en los siguientes aspectos:

* Las asignaturas de Autómatas y Lenguajes Formales (`alf`), Ampliación de
  Sistemas Operativos (`aso`) y Funciones de Variable Compleja (`fvc`), de las
  que no hay apuntes aquí o están incompletos.
* Los tres últimos capítulos de Optimización Lineal (`ol`), de los que cada uno
  está peor expresado que el anterior.
* Los problemas de accesibilidad planteados por las asignaturas que están sólo
  en PDF, especialmente las que son versiones escaneadas (no conservo los
  ficheros fuente), pues estos son problemáticos para quienes dependan de
  lectores de pantalla. Por supuesto, si alguien sabe de otros problemas de
  accesibilidad que se den en estos apuntes, agradecería que me informara.
* Fallos y erratas. Las contribuciones en este aspecto son sencillas y siempre
  son bienvenidas.
