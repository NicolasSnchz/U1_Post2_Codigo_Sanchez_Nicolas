# CONTRIBUTING

## Flujo de trabajo
1. Crear ramas a partir de `develop`.
2. Usar nombres de rama con prefijos:
   - `feature/`
   - `release/`
   - `hotfix/`
3. Realizar commits con Conventional Commits.

## Convención de commits
- `feat`: nueva funcionalidad
- `fix`: corrección de errores
- `docs`: cambios de documentación
- `chore`: tareas de mantenimiento
- `ci`: cambios de integración continua

## Reglas de integración
- Las `feature/*` se fusionan a `develop`.
- Las `release/*` se fusionan a `main` y `develop`.
- Las `hotfix/*` se crean desde `main` y se fusionan a `main` y `develop`.

## Revisión
Antes de fusionar, verificar:
- nombre correcto de la rama
- mensaje de commit convencional
- cambios documentados