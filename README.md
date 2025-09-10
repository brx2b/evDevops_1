# evDevops_1
+ Repositorio para evaluación 1 de la asignatura DevOps

## Estrategia de trabajo útilizada para el repositorio

Para trabajo en este repositorio se utilizó TBD (Trunk-Based Development),
la preferencia del uso se debe a la fácilidad de trabajar de forma individual ya que permite realizar
cambios de forma más constante y arreglos más rápidos que el método GitFlow que considero que es mucho más recomendable
en repositorios con un mayor equipo de desarrollo/colaboradores de por medio trabajar con TBD me ayuda a realizar el trabajo de manera más fluida y rápida.
---
# Documentación de convenciones commits, Flujos de merge, Estrategias de revisión 

### Commits

- **Formato:** 
  - feat nueva funcionalidad  
  - fix: corrección de error  
  - docs: documentación  
  - style: estilo, sin cambios de lógica  
  - refactor: reestructuración  
  - test: tests  
  - chore: mantenimiento  

### Flujos de merge

- main estable (producción).  
- develop: integración de cambios.
  
- **Proceso:**
  1. Crear ramas  main, develop, feature y hotfix.
  2. Subir cambios -> Pull Request (PR).
  3. Merge a main directamente.

#### Estrategia de revisión:

+ Todo cambio pasa por Pull Request (PR).

+ Se requiere al menos una aprobación antes del merge.

+ Revisar calidad de código, pruebas, estilo y documentación.

+ Mantener ramas actualizadas antes de mergear.

  ### Naming de ramas

  + Hotfix: Rama única para arreglos rápidos de errores.
  + feature: Nuevas funcionalidades.
  + Release: Cambios a una nueva versión.
  + Bugfix: Solución o parche a bugs.
