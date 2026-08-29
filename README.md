# Sistema-Proyecto-Integrador

##  Integrantes del Equipo
- **Emanuel Restrepo Ceballos**
- **Juan Alberto Zuluaga**
- **Erica Marcela Avendaño**

---


##  Estrategia de Ramas (GitFlow)
Seguimos una estrategia basada en **GitFlow**:
- `main`: Código estable y listo para entrega/producción.
- `develop`: Rama principal de integración del desarrollo actual.
- `feature/[nombre-tarea]`: Ramas individuales para trabajar características específicas creadas a partir de `develop`.

---

##  Convención de Commits
Utilizamos la convención **Conventional Commits**:
- `feat: [descripción]` para nuevas funcionalidades.
- `fix: [descripción]` para corrección de errores.
- `docs: [descripción]` para documentación (ej. cambios en el README).
- `refactor: [descripción]` para optimización de código sin alterar lógica.

---

##  Reglas para Pull Requests (PR) y Merges
1. **Creación de PR:** Todo cambio debe realizarse mediante un Pull Request desde la rama `feature/...` hacia `develop`.
2. **Revisión:** Al menos 1 integrante del equipo debe revisar y aprobar el PR antes de hacer merge.
3. **Merge:** Se aprueba si el código no presenta conflictos y cumple con los criterios de aceptación del Issue.
