# How to use this template

## Option 1 — Template repo on GitHub (recommended)

1. Create a new repo on your GitHub account with these files.
2. Go to **Settings → General → Template repository** and enable it.
3. When starting a new project, click **"Use this template"** on that repo. It creates a new repo with all the files and no template history.

## Option 2 — Clone and adapt

```bash
git clone <your-template-repo> my-new-project
cd my-new-project
rm -rf .git
git init
```

## Checklist when starting a new project

Once the template is copied:

- [ ] Edit `README.md` — project name, what it does, real stack.
- [ ] Fill in **Part B** of `CLAUDE.md` with the specific stack and decisions.
- [ ] Delete `INSTRUCTIONS.md` (this file) from the new project.
- [ ] Write the first ADR if you already made important decisions (e.g. "why we chose this stack").
- [ ] Update `docs/ARCHITECTURE.md` with the initial diagram (even if very basic).
- [ ] Populate `TODO.md` with what you're going to build first.
- [ ] First commit: `chore: initialize project from template`.

## Keeping the template alive

As you use the template on real projects, you'll find things to improve. When that happens:

1. Improve the file in the real project first.
2. Port the improvement back to the template.
3. Commit with a message like `template: improve PR checklist`.

That way the template matures with your experience.

## Template philosophy

This template does NOT expect you to document everything from day 1. It expects you to have **the places to document** ready, so that when you make an important decision or write a key component, there is no friction between "I want to write this down" and "where do I write it".

The golden rule: **a little living documentation is worth more than a lot of outdated documentation**.
