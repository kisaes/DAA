En un sistema de generación/distribución de energía, todos los generadores están conectados
a una misma red de distribución sin ninguna estructura específica. En caso de fallo,
el sistema colapsa en su totalidad y es necesario reiniciar cada generador de forma
manual, para esto se necesita un grupo de trabajadores que se mantiene en el lugar
durante el proceso; algunos generadores pueden reiniciar por si mismos, otros necesitan
energía inicial de un conjunto predeterminado de generadores (no necesariamente el mismo
conjunto para todos los generadores), de forma que reiniciar estos generadores implica
mantener un grupo de trabajadores en el generador (para reiniciar) y en cada uno de los
generadores de los que depende (para impedir el colapso durante el reinicio del generador
dependiente). Además, si hay al menos un generador adyacente apagado y no hay ningún
trabajador presente el desbalance provocaría nuevamente el colapso de todo el sistema,
por tanto, un grupo de trabajadores solo abandona un generador luego de que todos
los generadores dependientes de este hayan sido reiniciados.

## Posibles problemas a considerar

- Cuál es la menor cantidad de grupos de trabajadores necesaria para reiniciar todo
el sistema?

- Para una cantidad fija (suficiente) de grupos de trabajadores, cuál es el mínimo
de movimientos (transporte de trabajadores de un generador a otro) necesario para
reiniciar el sistema?

## Posibles variaciones

- El conjunto predeterminado de generadores de los que un generador depende podría
sustituirse por la restricción de haber reiniciado una cantidad mínima de generadores
adyacentes.
