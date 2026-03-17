# Security Policy

> This project follows the [Zairakai Global Security Policy][handbook-security].
> Please refer to it for standard protections, response timeline, and contact information.

---

## 🔒 Reporting Vulnerabilities

| Channel | Description | Contact / Link |
| :--- | :--- | :--- |
| **GitLab Issues** | For non-sensitive issues (bugs, public vulnerabilities). | [Open Issue][issues] |
| **Service Desk** | Preferred channel for sensitive reports. | `{{SERVICE_DESK_TOKEN}}` |
| **Email** | Alternative secure contact. | `security@the-white-rabbits.fr` |

Please **do not disclose vulnerabilities publicly** until they have been reviewed.

---

## 🛡️ Security Features

### Protection Layers

| Layer | Security Protection |
| :--- | :--- |
| **Static Analysis** | Strict TypeScript configs and ESLint security rules. |
| **CI Pipeline** | Automated secret detection in GitLab CI. |

---

## 🔍 Security Scope

`@zairakai/{{PACKAGE_SLUG}}` — {{PACKAGE_DESCRIPTION}}

---

[handbook-security]: https://gitlab.com/zairakai/handbook/-/blob/main/SECURITY.md
[issues]: https://gitlab.com/zairakai/npm-packages/{{PACKAGE_SLUG}}/-/issues
