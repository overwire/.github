<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/overwire/.github/main/profile/wordmark-dark.svg">
  <img alt="overwire" width="260" src="https://raw.githubusercontent.com/overwire/.github/main/profile/wordmark-light.svg">
</picture>

---

**Local workflow workbench** — run, mock, and debug your `.github/workflows/`
files locally before you push.

Overwire runs the same workflow YAML and `action.yml` files you push to GitHub,
faithfully enough that "works on Overwire" predicts "works on GitHub". Flag any
step **skip**, **live**, or **mock**, simulate events, and test branch policies
and security gates before the push — closing the push-wait-read-logs-fix loop.

Compatible with GitHub Actions workflow syntax.

### Explore

- 🌐 **[overwire.io](https://overwire.io)** — product & download
- 📚 **[docs.overwire.io](https://docs.overwire.io)** — guides, CLI reference, concepts
- 🧪 **[demo](https://github.com/overwire/demo)** — a four-repo workspace to try it on
- 🤖 **[agents](https://github.com/overwire/agents)** — AI agent skills (`/plugin marketplace add overwire/agents`)

Live runs execute inside a container and require a Docker-API-compatible
container engine (e.g., Docker Desktop, Colima, OrbStack, Rancher Desktop).

---

*Overwire is not affiliated with, endorsed by, or sponsored by GitHub, Inc.,
Microsoft Corporation, or Docker, Inc.*
