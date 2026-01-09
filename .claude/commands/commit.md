# /commit — Commit and Push Changes to GitHub

Create a git commit with a well-crafted commit message and push to GitHub.

---

## Process

1. **Check status** — Run `git status` to see what's changed
2. **Review changes** — Run `git diff` to understand the changes
3. **Stage files** — Add relevant files to staging
4. **Craft message** — Write a clear, meaningful commit message
5. **Commit** — Execute the commit
6. **Push** — Push the commit to GitHub

---

## Commit Message Format

Follow conventional commit style:

```
<type>: <short description>

<optional body explaining what and why>
```

### Types

- `feat` — New feature or functionality
- `fix` — Bug fix
- `style` — Visual/CSS changes
- `refactor` — Code restructuring without behavior change
- `docs` — Documentation changes
- `chore` — Maintenance tasks

### Examples

```
feat: add hero section with animated gradient background

style: update color palette to use warmer tones

fix: correct mobile navigation z-index issue
```

---

## Guidelines

- Keep the first line under 72 characters
- Use present tense ("add feature" not "added feature")
- Be specific about what changed
- Don't commit secrets, credentials, or `.env` files
- After committing, automatically push to origin

---

## Execute

Run `git status` and `git diff` to understand what needs to be committed, create an appropriate commit, then push to GitHub with `git push`.
