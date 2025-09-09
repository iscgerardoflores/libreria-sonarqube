# 🙌 Contributing Guide

¡Gracias por tu interés en contribuir a este proyecto! Sigue estas pautas para mantener un flujo de trabajo claro y consistente.

---

## ✅ Cómo empezar

1. Haz un fork del repositorio y clónalo localmente.
2. Crea una rama a partir de `develop` siguiendo la [convención de nombres de ramas](#-convención-de-nombres-de-ramas).
3. Realiza tus cambios.
4. Asegúrate de pasar los linters y pruebas locales antes de hacer commit.
5. Haz push de tu rama y abre un Pull Request hacia `develop`.
6. Espera la revisión y haz los ajustes solicitados.

---

## 📚 Convención de nombres de ramas

Usamos el siguiente esquema:
**Tipos permitidos:**
- `feature/`: nuevas funcionalidades
- `bugfix/`: corrección de errores
- `hotfix/`: correcciones urgentes
- `chore/`: tareas de configuración/mantenimiento
- `docs/`: documentación

**Ejemplos:**
- `feature/crud-beneficiarios`
- `bugfix/fix-login`
- `chore/docker-setup`
- `docs/update-readme`

---

## 🎨 Estándares de código

- Usa el linter configurado (ESLint/Prettier).
- Sigue las guías de estilo del proyecto.
- Incluye comentarios claros si el código no es obvio.
- No subas código comentado o sin usar.

## 📝 Convención de commits

**Tipos de commits comunes:**
- `feat`: nuevas funcionalidades
- `fix`: correcciones
- `chore`: tareas de mantenimiento
- `docs`: documentación
- `test`: pruebas
- `refactor`: refactorizaciones

**Ejemplos:**
- `feat(beneficiarios): add CRUD operations`
- `fix(auth): correct token expiration`
- `chore: update dependencies`

---

## 🧪 Pruebas

- Agrega o actualiza pruebas unitarias con Jest.
- Si tu cambio afecta funcionalidades completas, agrega pruebas end-to-end con Cypress.
- Asegúrate de que todas las pruebas pasen antes de abrir el PR.

---

## 🔍 Revisión de código

- Todo código nuevo debe ir acompañado de un Pull Request.
- Al menos un revisor debe aprobar antes de hacer merge a `develop`.
- Revisa los comentarios en el PR y responde o corrige según sea necesario.

---

## 🚦 Reglas de merge

- Nunca hagas merge directo a `main` ni `develop` desde local.
- Solo merges mediante Pull Requests revisados.
- Usa **squash merge** para mantener el historial limpio.

---

## 🔐 Seguridad

- No subas información sensible como contraseñas, tokens, claves o datos privados.
- Usa variables de entorno para configuraciones sensibles.

---

## 📧 Contacto

Para dudas, sugerencias o problemas:
- Abre un Issue en GitHub.
- O contacta al mantenedor principal:  
  **Nombre:** [Tu Nombre]  
  **Email:** [tu@correo.com]

---

¡Gracias por ayudar a mejorar el proyecto!