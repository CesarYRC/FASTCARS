# UNIVERSIDAD DE COLIMA
## FACULTAD DE TELEMÁTICA

**TDD.**

**Optativa:** Programación de Videojuegos  
**Profesor:** RODRÍGUEZ ORTÍZ MIGUEL ÁNGEL  

**Integrantes:**  
- Reyes Collas César Yahir

**GRADO Y GRUPO:**  
6° H

**Colima, Col. a 18 de marzo de 2025**

---

## Lista de características obtenidas del GDD

### Carreras de ¼ de milla:
Las cuales están enfocadas en la utilización de un embrague de cambio de marchas, el cual el más hábil podrá lograr ganar.

### Modo historia:
El modo historia tendrá una progresión en la cual el usuario (Corredor) irá siguiendo una historia la cual lo llevará a lograr nuevos desafíos con la IA y lograr obtener el desafío final el cual será llevado a cabo contra un personaje llamado "El fantasma", con el cual podrá lograr conseguir el último nivel y ser el mejor del juego.

### Modo online:
Este modo incluye modos de apuestas las cuales serán con dinero que podrás ganar dentro del juego, al igual que apuestas de carros, los cuales, al igual que el dinero, se podrán conseguir dentro del juego.

### Sistema de progresión:
Está enfocado en la mejora de autos, así como también en la escalabilidad del ranking.

### Control táctil optimizado:
Esto se llevará a cabo mediante el uso de smartphones los cuales podrán interactuar mediante gestos y toques en la pantalla, los cuales tendrán funciones específicas para el uso del videojuego.

### Ambientación:
La ambientación se basará en las calles de Colima, un lugar el cual es una ciudad muy pequeña pero tiene puntos importantes.

### Sistema de nitro estratégico:
Este sistema ayudará a obtener una ventaja para poder ganar, pero solo para los jugadores que logren obtener la habilidad para usarlo en el momento preciso.

### IA adaptativa:
Esta ayudará a la dificultad del modo historia, el cual es competir en modo progresión.

---

## Elección de Game Engine

**Motor elegido:** Unity  
**Justificación:**

- Unity es un motor que ofrece un soporte robusto para distintos dispositivos móviles, que es en lo que se busca desarrollar el videojuego.
- Tiene un sistema de físicas que permitirá simular con precisión las mecánicas de aceleración y cambio de marchas.
- Soporta cinemáticas avanzadas para la implementación de escenas clave del modo historia.
- El sistema de networking integrado facilitará el desarrollo de multijugador online.

---

## Planeación (Diagrama de Gantt):

| **Fase**                          | **Duración (Semanas)** |
|------------------------------------|------------------------|
| Diseño conceptual                 | 2                      |
| Creación de Modelos 3D            | 3                      |
| Implementación de Mecánicas       | 4                      |
| Desarrollo del Modo Historia      | 3                      |
| Desarrollo del Modo Online        | 3                      |
| Integración de IA y Física        | 3                      |
| Pruebas y Ajustes                 | 2                      |
| Final                              | 2                      |

---

## Diagramas de alto nivel

![Mi imagen](https://github.com/CesarYRC/ComandanteBikes/blob/master/Screenshot%202025-03-18%20213432.png)

---

## Arquitectura del Juego:

- **Módulo de Jugabilidad:** Maneja el sistema de carreras, IA y lógica de progresión.
- **Módulo de Interfaz (UI):** Menús optimizados para pantalla táctil.
- **Módulo de Física y Colisiones**
- **Módulo de Networking para el modo online**

---

## Herramientas de arte:

- **Blender:** Esta herramienta nos va a permitir desarrollar modelado y texturizado de vehículos y escenarios.
- **Photoshop:** Para el diseño de UI, texturas y vinilos.

---

## Objetos 3D, Terreno y Escena:

- Los vehículos se crearán en Blender, optimizando polígonos para el rendimiento móvil.
- Los entornos se modelarán usando assets modulares en Unity para facilitar su diseño.

---

## Detección de colisiones, físicas e interacciones:

- Se utilizará el sistema de Rigidbody y Wheelcollider de Unity para simular la aceleración y nitro.
- El sistema de colisiones emplea colliders tipo BoxCollider y MeshCollider optimizados para el rendimiento en móviles.

---

## Lógica de juego e inteligencia artificial:

- La IA controlará a los rivales, variando su dificultad según el progreso del jugador.
- Se implementarán comportamientos como uso estratégico del nitro y reacciones a errores del jugador.

---

## Audio y efectos visuales:

- **FMOD** se usará para gestionar el audio dinámico del motor del auto.
- Los efectos visuales incluirán partículas para el nitro, polvo en derrapes y reflejos dinámicos.

---

## Plataforma y requerimientos de software:

**Plataforma objetivo:** Smartphones con Android e iOS  
**Requerimientos mínimos:**
- Procesador Snapdragon 720G o equivalente.
- 4GB de RAM.
- Al menos 2GB de espacio de almacenamiento.
