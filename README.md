# Aetherium
An immersive, modular AI operations universe where interactive worlds represent real agents, projects, workflows, and resources.
## Browser Prototype

Aetherium is being developed as a modular AI Operations Universe. The first prototype explores a command interface built around The Watcher and the core locations: Barracks, Workshop, Vault, and Library.

### Current functionality

- Responsive browser interface.
- Navigation between core locations.
- Local operation registration and activity history.
- Browser-local persistence.
- Initial selectable visual themes.

### Run locally

No build tools or package installation are required for the initial static prototype.

1. Clone or download this repository.
2. Open `index.html` in a modern browser.
3. Register a test operation and navigate between the rooms.

For local development, a simple static web server is preferable when testing browser features.

### Publish with GitHub Pages

1. Open the repository's Settings.
2. Select Pages.
3. Set the source to Deploy from a branch.
4. Select the `main` branch and `/ (root)` folder.
5. Save and wait for deployment to finish.

The site is expected at:

`https://balpie347.github.io/Aetherium/`

Use the URL displayed in the repository's Pages settings if it differs.

### Important limitations

The current prototype is a frontend demonstration. Local task registration does not execute a real AI agent. It has no backend database, authentication, or secure provider integration.

Do not commit API keys, passwords, private credentials, or other secrets.

### Development documentation

See `docs/ARCHITECTURE.md` for the existing architecture notes and `docs/PROTOTYPE-ROADMAP.md` for the planned milestones.
