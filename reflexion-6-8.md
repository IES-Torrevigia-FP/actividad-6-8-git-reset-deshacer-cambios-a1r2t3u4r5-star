## Pregunta 1
soft → borra commit, mantiene staging
mixed → borra commit, quita staging
hard → borra TODO (commit + staging + archivos)

##Pregunta 2
git reset -reescribe historial
git revert -crea un commit nuevo y que quita otro

##Pregunta 3
--soft
Cuando escribes un commit mal y quieres rehacerlo
mixed
Cuando quieres reorganizar cambios antes de hacer commit
--hard
Cuando has roto todo y quieres volver a un estado limpio
