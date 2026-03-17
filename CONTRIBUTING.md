# Contributing

> This project follows the [Zairakai Global Contributing Guide][handbook-contributing].
> Please read it before contributing. The sections below document project-specific workflow.

---

## Development Workflow

| Step | Command / Action | Description |
| :--- | :--- | :--- |
| **1. Install** | `npm install` | Install dependencies and set up tooling. |
| **2. Branch** | `git checkout -b feature/#TICKET-name` | Create a feature branch from `develop`. |
| **3. Code** | *(your IDE)* | Implement your changes following quality standards. |
| **4. Quality** | `make quality` | Run the full quality gate. |
| **5. Test** | `npm test` | Ensure all tests are passing. |
| **6. Commit** | `git commit -m "type(scope): #TICKET subject"` | Use [Conventional Commits][git-rules] format. |
| **7. Push** | `git push origin feature/#TICKET-name` | Push and open a Merge Request to `develop`. |

---

## Quality Targets

| Command | Tool | Description |
| :--- | :--- | :--- |
| `make quality` | All | Full quality gate. |
| `npm run eslint` | ESLint | Lint check. |
| `npm run eslint:fix` | ESLint | Lint fix. |
| `npm run prettier` | Prettier | Format check. |
| `npm run prettier:fix` | Prettier | Format fix. |
| `npm run typecheck` | TypeScript | Type check. |
| `npm test` | Vitest | Run test suite. |
| `npm run build` | tsup | Build distributable. |

---

[handbook-contributing]: https://gitlab.com/zairakai/handbook/-/blob/main/CONTRIBUTING.md
[git-rules]: https://gitlab.com/zairakai/handbook/-/blob/main/GIT.md
[issues]: https://gitlab.com/zairakai/npm-packages/{{PACKAGE_SLUG}}/-/issues
