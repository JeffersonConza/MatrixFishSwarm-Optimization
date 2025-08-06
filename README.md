# MatrixFishSwarm-Optimization

Proyecto de optimizaci車n bioinspirada basado en el **Fish Swarm Algorithm (FSA)** ????

Este repositorio implementa el **Fish Swarm Algorithm (FSA)**, un algoritmo de optimizaci車n bioinspirado en el comportamiento colectivo de bancos de peces en busca de alimento. Es una alternativa robusta y vers芍til frente a otros enfoques evolutivos para resolver problemas complejos de optimizaci車n.

## Descripci車n

Este proyecto tiene como objetivo modelar y optimizar el comportamiento de enjambres de centinelas (inspirados en peces) para localizar y neutralizar **aerodeslizadores** en un entorno din芍mico y lleno de niebla. Usando el algoritmo **Fish Swarm Algorithm (FSA)**, los centinelas trabajan en conjunto siguiendo comportamientos de **b迆squeda**, **agrupamiento**, **seguimiento** y **aleatorio**.

Inspirado por el universo de *Matrix*, donde los centinelas patrullan la zona en busca de naves humanas, este proyecto adapta el algoritmo FSA para crear una simulaci車n donde los centinelas buscan y neutralizan a los aerodeslizadores. Este enfoque se utiliza para resolver problemas de optimizaci車n complejos a trav谷s de una inteligencia colectiva inspirada en la naturaleza.

## Tipos de comportamiento:

1. **B迆squeda individual**: Cada pez explora su entorno inmediato en busca de soluciones mejores.
2. **Agrupamiento**: Los peces se acercan a regiones donde sus vecinos han encontrado mejores soluciones, siempre que estas no est谷n sobrepobladas.
3. **Seguimiento**: Si un pez encuentra una zona con una mejora significativa, es seguido por otros miembros del banco.
4. **Aleatorio**: Cuando no hay mejora, los centinelas se mueven de manera aleatoria.

> ?? **Limitaci車n**: Algunos peces pueden quedarse atrapados en 車ptimos locales.  
> ?? **Mejora**: Una versi車n mejorada del algoritmo permite compartir informaci車n global entre todos los peces para mejorar la exploraci車n del espacio.

## Comportamientos Principales:

- **B迆squeda (Presa)**: Los centinelas buscan de forma individual el aerodeslizador m芍s cercano.
- **Agrupamiento (Enjambre)**: Los centinelas se agrupan alrededor de los mejores puntos (aerodeslizadores reales).
- **Seguimiento**: Los centinelas siguen a aquellos con mejores hallazgos.
- **Aleatorio**: Cuando no hay mejora, los centinelas se mueven de manera aleatoria.

## C車mo Funciona

1. El mapa est芍 dividido en **10x10 km** con una niebla densa que limita la visibilidad.
2. Hay **30 centinelas** patrullando aleatoriamente.
3. **4 aerodeslizadores** est芍n distribuidos aleatoriamente, uno de los cuales es un se?uelo (de bajo valor).
4. El objetivo es **neutralizar** todos los aerodeslizadores mediante el comportamiento de enjambre, agrupando a al menos 10 centinelas en torno a cada uno.

## Aplicaciones

- Optimizaci車n num谷rica
- Entrenamiento de redes neuronales
- Planificaci車n y log赤stica
- Selecci車n de caracter赤sticas
- Ajuste de hiperpar芍metros

## Instalaci車n

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/MatrixFishSwarm-Optimization.git
