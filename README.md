# Planificación Automática aplicada a LightsOut

Este proyecto forma parte de la asignatura **Inteligencia Artificial – Ingeniería del Software (Curso 2024/2025)**.  
El objetivo es aplicar algoritmos de búsqueda y planificación para resolver el clásico juego **LightsOut**, explorando enfoques tanto deterministas como estocásticos.

---

## 🎯 Objetivos
- Representar el juego LightsOut como un problema de planificación (usando PDDL o lenguajes similares).
- Implementar en **Python** un sistema que resuelva tableros básicos (hasta 5x5) mediante algoritmos de búsqueda.
- Ampliar la cantidad de tableros solucionables aplicando algoritmos más avanzados:
  - **Búsqueda heurística**
  - **Monte Carlo Tree Search (MCTS)**
- Documentar y analizar los resultados obtenidos.

---

## 🕹️ LightsOut
LightsOut es un puzzle de un solo jugador.  
- El tablero es una cuadrícula de tamaño N×M con celdas binarias (bombillas encendidas o apagadas).  
- Al pulsar sobre una celda, esta y sus vecinas (arriba, abajo, izquierda y derecha) cambian de estado.  
- El objetivo es transformar el tablero inicial en otro con todas las celdas encendidas, en el menor número de pasos.

---

## ⚙️ Metodología
1. **Parte común**  
   - Expresar el problema en PDDL (u otro lenguaje).  
   - Implementar en Python un buscador básico capaz de resolver el tablero 5x5 con búsqueda en anchura/profundidad.  

2. **Convocatoria de junio**  
   - Extender el sistema con un algoritmo heurístico que priorice los estados más cercanos a la solución.  

3. **Convocatoria de julio**  
   - Implementar **Monte Carlo Tree Search (MCTS)** para explorar el espacio de soluciones mediante simulaciones.  

---

## 🛠️ Tecnologías y librerías recomendadas
- **Python 3.x**  
- [Unified Planning](https://unified-planning.readthedocs.io/en/latest/index.html)  
- [Fast Downward](https://www.fast-downward.org/latest/)  
- [ENHSP](https://www.ai4europe.eu/research/ai-catalog/enhsp-unified-planning-interface)  
