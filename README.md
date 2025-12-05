# RPS-LS-MIA-2425
Proyecto de la especialidad **Inteligencia Artifical y Big Data** sobre estructura de un agente
    * [Contorno de tareas](#contorno-de-tareas)
    * [Estructura del agente](#estructura-del-agente)

## Contorno de tareas
Especificaciones de las características del contorno de las tareas de el RPS

Contorno de tareas | Observable| Agentes | Determinista | Episódico | Estático | Discreto | Conocido
:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
 RPS | Parcialmente Observable | Multi | Estocástico | Secuencial | - |  - |  - |

1. Contorno de tareas: **RPS**
2. Observable: **Parcialmente observable**. EL  agente no puede ver que va a sacar si tijeras, piedra o papel (información oculta).
3. Agentes: **Multiagente**. Competitivo, juegas con otro rival, ya sea humano u otro agente.
4. Determinista: **Estocástico**. El resultado que elija va a estar acompañada en el azar, depende del otro jugador.
5. Episódico: **Secuencial**. La decisión que elija afacta a la siguiente ronda(si es mejor a 3, gana).
6. Estático: **Estático**. El juego no cambia hasta que el agente decida en su turno que elegir.
7. Discreto: **Discreto**. Tiene finitos valores a elegir (piedra, papel, tijeras).
8. Conocido: **Conocido**. El agente conoce las reglas del juego antemano.

## Estructura del agente