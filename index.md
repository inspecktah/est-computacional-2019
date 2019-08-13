
--- 
title: "Estadística Computacional"
author: "María Teresa Ortiz"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib]
nocite: |
    @advr, @r4ds, @gelman-bayesian, @gelman-hill
biblio-style: apalike
link-citations: yes
github-repo: tereom/est-computacional-2019
description: "Curso de estadística computacional, Maestría en Ciencia de Datos, ITAM 2019."
---


# Información del curso {-}

Notas del curso *Estadística Computacional* de los programas de maestría en 
Ciencia de Datos y en Computación del ITAM. Las notas fueron desarrolladas en 
2014 por Teresa Ortiz quien las actualiza anualmente. En caso de encontrar 
errores o tener sugerencias del material se agradece la propuesta de 
correcciones mediante [pull requests](https://github.com/tereom/est-computacional-2019).

#### Ligas {-}

Notas: https://tereom.github.io/est-computacional-2019/    
Correo: teresa.ortiz.mancera@gmail.com   
GitHub: https://github.com/tereom/est-computacional-2019 

#### Agradecimientos {-}
Se agradecen las contriubuciones a estas notas de [\@felipegonzalez](https://github.com/felipegonzalez)
y [\@mkokotchikova](https://github.com/mkokotchikova).

</br>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licencia Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Este trabajo está bajo una <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Licencia Creative Commons Atribución 4.0 Internacional</a>.


## Temario {-}

1. **Manipulación y visualización de datos**

-   Principios de visualización.
-   Reestructura y manipulación de datos.
-   Temas selectos de programación en R: programación funcional, evaluación 
no estándar.

Referencias: @tufte06, @cleveland93, @r4ds, @advr.

2. **Inferencia y remuestreo**

-   Repaso de probabilidad.
-   Muestreo y probabilidad.
-   Inferencia.
-   El principio del *plug-in*.
-   Bootstrap
    -   Cálculo de errores estándar e intervalos de confianza.
    -   Estructuras de datos complejos.
-   Introducción a modelos probabilísticos.

Referencias: @ross, @efron.

3. **Modelos de probabilidad y simulación**

-   Variables aleatorias y modelos probabilísticos.
-   Familias importantes: discretas y continuas.
-   Teoría básica de simulación
    -   El generador uniforme de números aleatorios.
    -   El método de la transformación inversa.
    -   Simulación de variables aleatorias discretas con soporte finito.
    -   Otras variables aleatorias.
-   Simulación para modelos gráficos
    -   Modelos probabilíticos gráficos.
    -   Simulación (e.g. ANOVA, regresión simple).
-   Inferencia paramétrica y remuestreo
    -   Modelos paramétricos.
    -   Bootsrap paramétrico.
-   Inferencia de gráficas

 Referencias: @gelman-hill.

4. **Métodos computacionales e inferencia Bayesiana**

-   Inferencia bayesiana.
-   Métodos diretos
    -   Familias conjugadas.
    -   Aproximación por cuadrícula.
    -   Aceptación y rechazo.
-   MCMC
    -   Cadenas de Markov.
    -   Metropolis-Hastings.
    -   Muestreador de Gibbs.
    -   Monte Carlo Hamiltoniano.
    -   Diagnósticos de convergencia.

Referencias: @kruschke, @gelman-bayesian.

### Calificación {-}

* Tareas 20% (se envían por correo con título *EstComp-TareaXX*).

* Exámen parcial (proyecto y exámen en clase) 40%.

* Examen final 40%.

### Software {-}

- R: https://www.r-project.org
- RStudio: https://www.rstudio.com
- Stan: http://mc-stan.org

### Otros recursos {-}

* [Socrative](https://b.socrative.com/login/student/) (Room **ESTCOMP**):
Para encuestas y ejercicios en clase.


* [Lista de correos](https://docs.google.com/spreadsheets/d/1ZNdpl-_c495FRb1ZEZ-TpxFDBk5Uai-9Ms-IHgsYq-E/edit?usp=sharing): Suscribete si quieres recibir noticias del curso o una 
suscripción a [DataCamp](https://www.datacamp.com) (6 meses con acceso a todos
los recursos de forma gratuita).

<!--
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Great news that Brad Efron has won the 2019 Internalibrary(tidyv)tional Statistics Prize for the 1977 bootstrap idea - so simple and yet so powerful <a href="https://t.co/XKvsoWWqNX">https://t.co/XKvsoWWqNX</a> <a href="https://t.co/kUjy6jTSAS">pic.twitter.com/kUjy6jTSAS</a></p>&mdash; David Spiegelhalter (@d_spiegel) <a href="https://twitter.com/d_spiegel/status/1061968814043250688?ref_src=twsrc%5Etfw">November 12, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


<blockquote class="twitter-tweet"><p lang="en" dir="ltr">So honoured and excited to receive the COPSS award for contributions to statistics through computing, visualisation, and data science ☺️ <a href="https://t.co/UiX6IlKGlt">https://t.co/UiX6IlKGlt</a></p>&mdash; Hadley Wickham (@hadleywickham) <a href="https://twitter.com/hadleywickham/status/1156693702372462592?ref_src=twsrc%5Etfw">July 31, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

-->