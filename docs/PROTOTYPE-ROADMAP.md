# Aetherium — Prototype Roadmap

## 1. Vision

Aetherium is an AI Operations Universe: an interface in which operational tools, agents, projects, knowledge, and resources are represented through an immersive and customisable environment.

The environment is not merely decoration. Interactive objects should eventually connect to real application functions.

The user should be able to change the visual world without having to rebuild the underlying operations system.

## 2. Core principles

- **World as interface:** rooms and objects provide a visual representation of functional software.
- **The Watcher:** a central supervisory interface for system status, oversight, and user-directed operations.
- **Modularity:** visual environments remain separate from the operational logic.
- **Interchangeable worlds:** fantasy, science fiction, cyberpunk, minimalist, and future custom environments.
- **Honest execution states:** simulated operations must never be presented as completed real-world AI actions.
- **User control:** permissions, confirmations, and operational status should be visible.
- **Security first:** never place API keys, passwords, or private credentials in client-side code or public repositories.
- **Incremental development:** each milestone should produce a testable improvement.

## 3. Core locations

### The Watcher

The supervisory command centre. It should eventually display system health, current activity, pending approvals, alerts, and operational summaries.

### Barracks

The agent management area. It should contain agent profiles, roles, capabilities, assignments, and execution status.

### Workshop

The project and workflow environment. It should support project creation, task planning, workflow configuration, and progress tracking.

### Vault

The resource and permissions environment. It should eventually manage connections, access policies, and references to securely stored credentials. It must not expose secrets.

### Library

The knowledge environment. It should organise documentation, project notes, instructions, references, and reusable knowledge.

## 4. Current prototype scope

The initial browser prototype aims to provide:

- A responsive command interface.
- Navigation between the five core locations.
- Local task registration.
- A local activity log.
- Browser-based persistence for prototype data.
- Selectable visual themes.
- Clear labelling of simulated operations.

The first version does not provide real AI execution, authentication, a backend database, remote agent orchestration, or fully immersive 3D environments.

## 5. Architecture direction

The intended separation is:

- `index.html`: application entry point and page structure.
- `styles.css`: shared visual styling and responsive layout.
- `src/core/`: application state and core operations.
- `src/worlds/`: visual themes and environment definitions.
- `src/ui/`: rendering and interface interactions.
- `src/main.js`: application startup and module coordination.
- `docs/`: architecture, roadmap, and development notes.

This is the intended direction, not a claim that all these files are already implemented.

## 6. Development milestones

### Milestone 1 — Browser prototype
- Working page and navigation.
- Local task registration.
- Local activity log.
- Initial visual themes.
- Basic responsive layout.

### Milestone 2 — Modular frontend
- Separate HTML, CSS, and JavaScript files.
- Shared application state.
- Theme definitions separated from core operations.
- Clear boundaries between UI, world presentation, and data.

### Milestone 3 — Functional rooms
- Room-specific controls and content.
- Editable agent profiles.
- Project and workflow records.
- Searchable activity history.
- Clear status and error handling.

### Milestone 4 — Immersive world layer
- Scene backgrounds and environmental assets.
- Interactive objects with functional actions.
- Camera, lighting, and spatial navigation experiments.
- Environment loading independent of core application state.

### Milestone 5 — Real AI integration
- Backend service and provider abstraction.
- Secure credential management.
- Explicit execution permissions and approval flows.
- Logging, error handling, and cost controls.
- Tests distinguishing queued, running, completed, and failed tasks.

## 7. Definition of done

A milestone is complete only when its functionality has been implemented, the main paths have been tested, limitations have been documented, and the repository matches the reported state.

A visual mock-up alone does not count as a functioning operational integration.
