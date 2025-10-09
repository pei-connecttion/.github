# connecTTion — An Information System to Optimize Processes in Associations.

A unified ERP platform designed to centralize AETTUA’s operations (members, events, finances, and resources) and improve efficiency, transparency, and collaboration across teams.

## Why this exists

AETTUA currently relies on scattered tools and manual work. **connecTTion** addresses this by centralizing information and streamlining processes in one place, with a focus on data security, transparency, and scalability for future modules.

---

## Core Goals

- Build a functional prototype tailored to AETTUA’s workflows.
- Centralize membership, event organization, and financial control.
- Improve communication and collaboration between internal teams.
- Ensure data security, transparency, and accessibility.
- Provide a scalable foundation for future modules.

---

## Functionalities (MVP)

- **Member Management** — registration, updates, and member tracking.
- **Financial Management** — revenues, expenses, and financial reports.
- **Resource Management** — inventory of materials, rooms, and equipment.
- **Dashboard & Indicators** — quick view of key metrics (active members, events held, financial status, etc.).

> Future iterations can expand modules based on AETTUA’s priorities.

---

## Roadmap

**Phase 1 — Requirements & Planning (October)**  
Identify needs, define scope/MVP, set up dev workflow and responsibilities.

**Phase 2 — System Design (Early November)**  
Architecture (backend, frontend, database), roles/permissions, workflows, wireframes/UI mockups.

**Phase 3 — MVP Implementation (Mid Nov–Dec)**  
Develop core + integrate a module; deliver MVP for evaluation in December.

**Phase 4 — Extended Implementation (Jan–Mar)**  
Add functionalities; improve integration, usability, performance.

**Phase 5 — Testing & Validation (April)**  
Unit, integration, acceptance testing; user testing with AETTUA and improvements.

**Phase 6 — Deployment & Documentation (May)**  
Controlled deployment, user docs & training, final presentation + future recommendations.

---

## Contributing

1. Check the **Roadmap** to see what phase we’re in and the current priorities.
2. Open an issue describing the change (link it to a milestone/phase).
3. Create a feature branch from `main`.
4. Submit a PR with:
   - Scope, screenshots (if UI), and testing notes.
   - Any migrations and rollback steps.
5. Request a review from module owners (Members, Finance, Resources, Dashboard).

### Coding Standards

- Follow the architectural decisions established in Phase 2 (roles, permissions, workflows).
- Write unit/integration tests (aligned with Phase 5 testing strategy).

---

## Security & Privacy

- Handle member and financial data with care; adhere to least-privilege roles/permissions defined during system design.
- Do not commit secrets—use environment variables and secret managers.

---

## Documentation

- **User documentation & training** will be delivered ahead of deployment (Phase 6). Keep `/docs` updated as features land.

---

## Team
**Members:** Rafael Fernandes · Dinis Cunha · Pedro Fonseca · Eduardo Rosário · Henrique Lopes
**Advisors:** Osvaldo Pacheco · Daniel Ferreira  
**Collaborators:** Duarte Santos · Sebastião Teixeira · Guilherme Rosa

---

## License

TBD (choose and add a LICENSE file).
