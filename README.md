# FASE 1. Investigación Técnica
## Tarea: Antes de empezar el diseño, debemos documentarnos sobre la sintaxis específica de UML 2.5 para nodos de control. Lo importante aquí es distinguir entre una decisión (rombo) y una bifurcación (barra de fork).

Nodo decision que es el rombo, se usa cuando el flujo toma solo una ruta segun una condicion por ejemplo stock disponible --> si o no

Bifurcacion que es una barra gruesa horizontal o vertical sirve para ejecutar tareas en paralelo es decir en el mismo tiempo --> validar stock y comprobar sesion

En un diagrama UML, un fork o un nodo de bifurcacion sirve para representar cuando dos o mas actividades se estan ejecutando en el mismo tiempo:
Graficamente se representa con una barra negra en horizontal o vertical. 
Tiene un flujo de entrada y dos flujos o mas de salida, cuando el flujo llega a la bifurcacion éste se divide en varios caminos donde cada uno representa una accion o actividad que acaba de comenzar de forma paralela al resto.

Cada vez que en un fork hay actividades paralelas aparece una ocurrencia de bifurcacion, esto significa que pueden darse varias tareas o acciones a la vez, unas independientes de otras por lo que no tienen que esperar a que una acabe para poder ser ejecutada

Se usan para poder modelar un sistema mas eficiente con mayor rendimiento, menor tiempo de espera y separar acciones de forma responsable.
