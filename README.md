# Informes TBD 2015-1

Informes y Presentaciones del Grupo 3:

* Gerson Aguirre
* Max Chacón
* Daniel Gacitúa
* Elías González
* Nicolás Rozas

## Preludio

Ya que está estipulado en los requisitos del curso el tener los Informes y Presentaciones con control de versiones, lo más sano y recomendable es hacerlos en LaTeX, para facilitar el formateo y uniformidad de la documentación (además de ser multiplataforma).

## Método de trabajo

En el repo hay 2 carpetas: "InformeEjemplo" y "PresentacionEjemplo", cada vez que sea necesario hacer una entrega, hagan una copia de ambas carpetas y modifiquen las copias con los contenidos de cada entrega respectiva.

Para editar el contenido del informe, editen el archivo "prueba.tex" usando [formato LaTeX](http://users.dickinson.edu/~richesod/latex/latexcheatsheet.pdf).

Para editar el contenido de la presentación, editen el archivo "presentacion.md" usando [formato Markdown](http://daringfireball.net/projects/markdown/syntax).

## Dependencias necesarias

Los paquetes necesarios para compilar los Informes y Presentaciones son los siguientes:

* TeXLive
* TeXLive Idioma Español
* pdflatex
* biblatex
* biber
* pandoc
* beamer
* latexmk

Para usuarios de Ubuntu y Debian, con el siguiente comando instalan las dependencias necesarias:

	sudo apt-get install texlive texlive-latex-recommended texlive-bibtex-extra texlive-lang-spanish biber pandoc latexmk

NOTA: Son como 350MB en paquetes, así que tengan paciencia.

Para usuarios de Windows, pueden instalar el paquete MikTeX que contiene las dependencias necesarias:

[Descargar MikTeX](http://miktex.org/download)

NOTA: Asegúrense con el manejador de paquetes de MikTeX de tener instalados los paquetes necesarios para compilar los informes.

## Editar y Compilar

Un buen editor para los informes LaTeX es Texmaker.

* [Descarga para Linux](http://www.xm1math.net/texmaker/download.html#linux)
* [Descarga para Windows](http://www.xm1math.net/texmaker/download.html#windows)

NOTA: Para instalar paquetes .deb en Ubuntu/Debian se usa:

	sudo dpkg -i NOMBREPAQUETE.deb

Para compilar el informe desde Ubuntu/Debian se entra a la carpeta desde el Terminal y se usa:

	latexmk

Para compilar la presentación desde Ubuntu/Debian se entra a la carpeta desde el Terminal y se usa:

	make
