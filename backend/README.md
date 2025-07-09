# agenda-tool

Professional appointment and business agenda tool for companies and professionals.

---

# agenda-tool

Herramienta profesional de agenda y turnos para empresas y profesionales.

---

## Features Checklist / Lista de Funcionalidades

- [ ] User registration (professionals & clients) / Registro de usuarios (profesionales y clientes)
- [ ] Email confirmation for both / Confirmación de cuenta por email para ambos
- [ ] Manual approval for companies / Aprobación manual para empresas
- [ ] First company user becomes first employee / Primer usuario empresa es su primer empleado
- [ ] Brute force protection (rate limiting, IP blocking) / Protección contra fuerza bruta (limitación de intentos, bloqueo de IP)
- [ ] Logging (Winston) / Registro de logs (Winston)
- [ ] Employee invitations via email / Invitación de empleados por email
- [ ] Professional dashboard with stats / Dashboard profesional con estadísticas
- [ ] Service management (CRUD) / Gestión de servicios (CRUD)
- [ ] Schedule and availability management / Gestión de agenda y disponibilidad
- [ ] Public reservation page per company / Página pública de reservas por empresa
- [ ] Client history and quick booking / Historial del cliente y reservas rápidas
- [ ] Email notifications and reminders / Notificaciones y recordatorios por email
- [ ] Statistics module / Módulo de estadísticas
- [ ] Code linting and formatting / Linting y formato de código
- [ ] Automated tests / Pruebas automatizadas

---

## Branching Strategy

- Each major feature or setup step should be developed in its own branch (e.g., project-setup, auth-and-user-registration, etc.).
- After completing and testing each step, commit and push that branch to GitHub.
- The main branch should always be stable and production-ready.

## Contribution Guidelines

- Follow the checklist in the README to track progress.
- Update the checklist in every pull request.
- Keep commits clear and descriptive.
- Ensure all code passes linting and tests before merging. 