# T-Craft Platforms
T-Craft Platforms is a collaborative initiative focused on building Minecraft plugins, mods, and the infrastructure required to run them on private servers.
The organization is not a company, does not pursue monetisation, and aims to keep projects open-source whenever possible.

---

## 🤝 Community & Conduct
- Be respectful, constructive, and professional.
- Assume good intent and communicate openly.
- Follow common open-source etiquette.

---

## 🔐 Repository Visibility & Ownership
- Always create repositories as `internal` or `private` by default.
- Only set a repository to public if you are absolutely sure it is intended for open-source.
- Never make a repository public if it:
  - Uses proprietary software
  - Depends on private or demo environments
  
  unless explicitly approved by the code owners.
- If a repository's purpose cannot be justified, it may be archived or removed at any time at the discretion of the organization administrators.
- Do not migrate repositories to or away from T-Craft Platforms without prior approval from the relevant code owners and organization administrators.

---

## 🌿 Branching & Workflow
- Never push directly to `main`, especially on public repositories.
  - For public repositories, a branch protection rule protecting at least the default branch must be configured.
  - For internal repositories, branch protection is highly advised.
  - For private repositories, branch protection is the responsibility of the repository maintainers, but is also highly advised.
- Always:
  1. Create an issue
  2. Create a branch linked to that issue
  3. Open a pull request
  4. Merge into `main` after review

→ See [Creating a Branch for an Issue](#creating-a-branch-for-an-issue)

### Branch naming
Use prefixes whenever possible:
- `feature/`
- `bug/`
- `security/`

Avoid loose or unnamed branches.

---

## 🧩 Issues, Projects & Discussions
### Issues
- Use repository issues for detailed, specific feature requests or tasks.
- Always consider:
  - Is this limited to one repository?
  - Or does it affect multiple repositories?

Rules:
- Single-repo topic → create the issue in that repository
- Multi-repo topic → create the issue in the [`root`](https://github.com/T-Craft-Platforms/root) repository
- Always link issues to a project if one exists  
→ See [Selecting a Project for an Issue](#selecting-a-project-for-an-issue)

### Projects
- Use GitHub Projects (Kanban recommended) for planning and tracking.
- When creating a project:
  - Always select [`root`](https://github.com/T-Craft-Platforms/root) as the default repository
  - This allows issues that span multiple repositories
- After creation:
  - Go to each relevant repository
  - `Projects` → `Link a project` → select the project

### Discussions
Use organization-wide Discussions for:
- Announcements
- Ideas and coarse feature requests
- Polls
- Questions & answers

It is generally not recommended to create repository-specific discussions unless the repository is large.

[//]: # (exclude)

---

## 🖼️ Visual Guidelines
### Selecting a Project for an Issue
<img width="393" height="294" alt="Screenshot" src="https://github.com/user-attachments/assets/f89522d2-ed9c-4b13-9e77-a6507fc73cb1" />

### Creating a Branch for an Issue
<img width="393" height="294" alt="Screenshot" src="https://github.com/user-attachments/assets/8840a6e6-2ed8-4773-bf30-7d0c227e24f6" />
<br>
<img width="393" height="294" alt="Screenshot" src="https://github.com/user-attachments/assets/3adb0735-4d2b-4296-afca-72f0b9833963" />
<br>
<img width="393" height="294" alt="Screenshot" src="https://github.com/user-attachments/assets/cf4725cd-a828-4146-8090-61691ae16271" />
