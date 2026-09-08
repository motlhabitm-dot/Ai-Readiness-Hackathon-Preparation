# Team Contributing Guidelines

Welcome to the team project repository. To ensure smooth collaboration, maintain code quality, and follow security standards, all team members must follow these guidelines.


## 1. Team Roles and Responsibilities
- **Team Lead / Demo Owner:** Oversees sprint goals, demo preparation, and daily standups.
- **Build Owners:** Manages core configurations, integrations, and low-code/solution builds.
- **Review Owner:** Reviews pull requests, ensures coding standards, and oversees code merges.
- **Data & Governance Owner:** Enforces security policies, data schemas, and Responsible AI alignment.


## 2. Branching Strategy
Direct commits to `main` are strictly blocked by branch protection rules.

### Branch Naming Convention
All branches must use the following naming pattern:
`feature/<initials>-<topic-or-task>`

**Examples:**
- `feature/tm-project-board`
- `feature/gn-copilot-setup`
- `feature/ad-power-automate-flow`


## 3. Pull Request (PR) Process
1. **Create Branch:** Create a branch from `main` using the naming convention above.
2. **Commit Changes:** Make focused, clear commits describing the work done.
3. **Open Pull Request:** Target the `main` branch with a clear description of the updates.
4. **Mandatory Peer Review:** Every PR requires at least **one approving review** before merging. 
5. **No Self-Approvals:** Authors cannot approve their own pull requests.
6. **Merge Method:** Use **Squash and merge** or standard **Merge** once checks pass.


## 4. Security and Secrets Management
- **Zero Secrets Policy:** Never commit secrets, API keys, passwords, client secrets, or personal access tokens into the repository.
- **Environment Files:** Keep credentials strictly in local `.env` files or platform environment variables. Ensure `.env` is listed in `.gitignore`.
- **Scanning:** GitHub Secret Scanning and Dependabot alerts are enabled. Any commit triggering a security alert must be remediated immediately.


## 5. Issue Tracking & Board Etiquette
- Check the repository **Projects** board before starting a task.
- Move your card to **In progress** when you start work, to **In review** when opening a PR, and to **Done** once merged.
