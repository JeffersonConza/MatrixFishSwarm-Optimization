# MatrixFishSwarm-Optimization 🐟🤖

Optimización bioinspirada con el algoritmo Fish Swarm en un entorno simulado tipo *Matrix*.

¡Bienvenidos al proyecto de optimización basado en el **Fish Swarm Algorithm (FSA)**! Este repositorio implementa una simulación inspirada en el universo de *Matrix*, donde centinelas patrullan un entorno dinámico y lleno de niebla para localizar y neutralizar aerodeslizadores humanos.

---

## 🧠 Descripción

El **Fish Swarm Algorithm (FSA)** es un algoritmo de optimización bioinspirado en el comportamiento colectivo de bancos de peces. En esta simulación, los centinelas (inspirados en peces) se comportan según cuatro patrones:

- **Búsqueda individual**
- **Agrupamiento**
- **Seguimiento**
- **Movimiento aleatorio**

El objetivo es neutralizar todos los aerodeslizadores mediante inteligencia colectiva.

---

## 🎮 Cómo Funciona

- El mapa está dividido en una cuadrícula de **10x10 km** con niebla densa.
- Hay **30 centinelas** patrullando aleatoriamente.
- **4 aerodeslizadores** están distribuidos aleatoriamente (uno es señuelo).
- Se considera neutralizado un aerodeslizador cuando **≥10 centinelas** lo rodean.

---

## 🐟 Comportamientos del Enjambre

| Comportamiento     | Descripción                                                                 |
|--------------------|------------------------------------------------------------------------------|
| Búsqueda           | Exploración individual en busca de soluciones mejores.                      |
| Agrupamiento       | Acercamiento a regiones con buenos resultados, evitando sobrepoblación.     |
| Seguimiento        | Imitación de peces exitosos en zonas de mejora significativa.               |
| Aleatorio          | Movimiento aleatorio cuando no hay mejora detectada.                        |

> ⚠️ *Limitación*: Algunos peces pueden quedar atrapados en óptimos locales.  
> 🚀 *Mejora*: Se incluye una versión con comunicación global para mejorar la exploración.

---

## 📦 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/MatrixFishSwarm-Optimization.git
   cd MatrixFishSwarm-Optimization
