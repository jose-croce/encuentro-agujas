# Solución al problema de encuentro de las agujas del reloj

Se trata de un ejemplo de artículo escrito en Latex como ejemplo.

Describe cómo resolver el problema de hallar las horas a las que se cruzan las agujas de un reloj analógico a lo largo del día (que por cierto son sólo 11 y no 12 como podría parecer en principio).

## Dependencias

Para generar la salida en PDF desde una máquina Ubuntu (>=22.04) se recomienda la instalación de los siguientes paquetes:

- texlive-latex-extra
- texlive-extra-utils
- textlive-lang-spanish

## Generación del fichero de salida

Los fuentes se encuentran en los ficheros con extensión .tex y, para generar la salida, se deben utilizar las herramientas standard de Latex.

Para generar una versión del documento en formato `PDF` el comando es:

```bash
pdflatex encuentro_agujas.tex
```

> **NOTA:**
> Puede ser necesario ejecutar el comando dos veces para la resolución de referencias cruzadas.

