# MatrixFishSwarm-Optimization

!Bienvenidos al proyecto de optimizacion bioinspirada basado en el **Fish Swarm Algorithm (FSA)**! ????

Este repositorio implementa el **Fish Swarm Algorithm (FSA)**, un algoritmo de optimizacion bioinspirado en el comportamiento colectivo de bancos de peces en busca de alimento. Es una alternativa robusta y versatil frente a otros enfoques evolutivos para resolver problemas complejos de optimizacion.

## Descripcion

Este proyecto tiene como objetivo modelar y optimizar el comportamiento de enjambres de centinelas (inspirados en peces) para localizar y neutralizar **aerodeslizadores** en un entorno dinamico y lleno de niebla. Usando el algoritmo **Fish Swarm Algorithm (FSA)**, los centinelas trabajan en conjunto siguiendo comportamientos de **busqueda**, **agrupamiento**, **seguimiento** y **aleatorio**.

Inspirado por el universo de *Matrix*, donde los centinelas patrullan la zona en busca de naves humanas, este proyecto adapta el algoritmo FSA para crear una simulacion donde los centinelas buscan y neutralizan a los aerodeslizadores. Este enfoque se utiliza para resolver problemas de optimizacion complejos a traves de una inteligencia colectiva inspirada en la naturaleza.

## Tipos de comportamiento:

1. **Busqueda individual**: Cada pez explora su entorno inmediato en busca de soluciones mejores.
2. **Agrupamiento**: Los peces se acercan a regiones donde sus vecinos han encontrado mejores soluciones, siempre que estas no esten sobrepobladas.
3. **Seguimiento**: Si un pez encuentra una zona con una mejora significativa, es seguido por otros miembros del banco.
4. **Aleatorio**: Cuando no hay mejora, los centinelas se mueven de manera aleatoria.

> ?? **Limitacion**: Algunos peces pueden quedarse atrapados en optimos locales.  
> ?? **Mejora**: Una version mejorada del algoritmo permite compartir informacion global entre todos los peces para mejorar la exploracion del espacio.

## Comportamientos Principales:

- **Busqueda (Presa)**: Los centinelas buscan de forma individual el aerodeslizador mas cercano.
- **Agrupamiento (Enjambre)**: Los centinelas se agrupan alrededor de los mejores puntos (aerodeslizadores reales).
- **Seguimiento**: Los centinelas siguen a aquellos con mejores hallazgos.
- **Aleatorio**: Cuando no hay mejora, los centinelas se mueven de manera aleatoria.

## Como Funciona

1. El mapa esta dividido en **10x10 km** con una niebla densa que limita la visibilidad.
2. Hay **30 centinelas** patrullando aleatoriamente.
3. **4 aerodeslizadores** estan distribuidos aleatoriamente, uno de los cuales es un senuelo (de bajo valor).
4. El objetivo es **neutralizar** todos los aerodeslizadores mediante el comportamiento de enjambre, agrupando a al menos 10 centinelas en torno a cada uno.

## Aplicaciones

- Optimizacion numerica
- Entrenamiento de redes neuronales
- Planificacion y logistica
- Seleccion de caracteristicas
- Ajuste de hiperparametros

## Instalacion

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/MatrixFishSwarm-Optimization.git
