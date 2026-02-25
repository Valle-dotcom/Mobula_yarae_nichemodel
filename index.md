---
title: "Ejercicio de modelado de nicho de Mobula yarae"
---

# Flujo de trabajo
<nav>
  <a href="#paso-1">I. Preparación de datos</a> |
  <a href="#paso-2">II. </a> |
  <a href="#paso-3">III. </a> |
  <a href="#paso-4">Paso</a> |
  <a href="#paso-5">Paso</a>
</nav>

---
## Introducción
El siguiente ejercicio está diseñado con la idea de que el estudiante pueda poner en práctica los pasos esenciales del flujo de trabajo para la 
realización de modelos de distribución de especies (MDE o SDM en inglés) y modelos de nicho ecológico (MNE o ENM en inglés) para organismos marinos. 
Este *workflow* está basado y adaptado a partir del manual de [Simoes et al. (2020)](https://doi.org/10.17161/bi.v15i2.13376), el cual recomiendo ampliamente 
como una guía práctica introductoria al tema. Además, recomiendo también para la limpieza de datos el manual de [Cobos et al. (2018)](https://doi.org/10.17161/bi.v13i0.7600) y el libro de 
[Peterson et al. (2011)](https://doi.org/10.1515/9781400840670?urlappend=%3Futm_source%3Dresearchgate.net%26utm_medium%3Darticle) como texto base para esta disciplina.

Este ejercicio tiene como objetivo realizar un SDM y un ENM (para aprender más sobre las diferencias conceptuales entre estos dos tipos de modelos recomiendo
[Soberón et al. 2017](https://doi.org/10.1016/j.rmb.2017.03.011)) de la mantarraya del Atlántico (*Mobula yarae*), una especie recién descrita por [Bucair et al. (2025)](https://doi.org/10.1007/s10641-025-01727-2) y de la cual aún no se conocen varios aspectos de su historia natural, incluyendo su área de distribución.
En este ejercicio usaremos [*ellipsenm* (Cobos et al. 2020)](https://github.com/marlonecobos/ellipsenm2) un paquete de R que utiliza envolturas elipsoidales para caracterizar el nicho de la especie [(Farber and Kadmon 2003)](https://doi.org/10.1016/S0304-3800(02)00327-7)





<a id="paso-1"></a>
## I. Preparación de datos

Debido a que *M. yarae* es una especie recién descrita, los datos presentes en [GBIF](https://www.gbif.org/es/)
aún no presentan registros de esta especie. Ya que *M. yarae* es simpátrica con *M. birostris* [(Bucair et al.,2025)](https://doi.org/10.1007/s10641-025-01727-2), es necesario volver a reclasificar los registros de *M. birostris* que se encuentran dentro del área de distribución de *M. yarae*. Si bien para esto, y según [Bucair et al.,2025](https://doi.org/10.1007/s10641-025-01727-2) es necesario una identificación genética; para fines de este ejercicio vamos a realizar un proceso de limpieza estandarizado para MDE/MNE con los registros provenientes de GBIF para *M. birostris*.
- Objetivo:
- Requisitos:
- Instalación:

<a id="paso-2"></a>
## Paso 2 — Datos
- Descargar datos
- Limpiar datos
- Formato esperado

<a id="paso-3"></a>
## Paso 3 — Variables ambientales
- Fuente
- Recorte / resolución
- Preparación

<a id="paso-4"></a>
## Paso 4 — Modelado
- Algoritmo
- Parámetros
- Ejecución

<a id="paso-5"></a>
## Paso 5 — Resultados
- Mapas
- Métricas
- Exportar productos

---

### Volver arriba
[↑ Ir al índice](#indice)
