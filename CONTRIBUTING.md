# Contributing to Boboter UI

Thank you for your interest in helping out! To keep the project safe and maintainable, please follow these steps.

(For those confused by the term PR: it stands for **Pull Request**! 😉)

## 1. Workflow
1. **Fork**: Create a copy (Fork) of the repository in your own account.
2. **Branch**: Create a new branch for your changes (`git checkout -b feature/my-feature`).
3. **Commit**: Write clear and descriptive commit messages.
4. **Push**: Upload the branch to **your fork**.
5. **Pull Request (PR)**: Open a PR against my `main` branch.

## 2. Pull Request Rules
- Briefly describe what you changed or added and why.
- Keep PRs small and focused on a single topic.
- **Never** push API keys, passwords, or private configuration files.

## 3. Code Style
- Ensure your code is spotless and structured. I maintain high standards to keep the codebase
  accessible for beginners.
- **Compodoc** documentation is mandatory for methods, namespaces and classes.
- Use comments only where absolutely necessary to explain complex logic.
- Format variables and similar using `snake_case` (like this: `variable_name`)
- Format files using `kebab-case` (like this: `file-name.ts`)
- Maintain the existing formatting and naming scheme(s) of the app.
- Use only tailwind CSS and **avoid** inline styles, big CSS blocks and similar.
- **Architecture**: Keep logic inside **Services**; Components should only handle the view and user interaction.
- **Tailwind**: Use the standard class order. Avoid creating custom CSS classes unless Tailwind's utility classes are insufficient.

## 4. Content
- Only add new libraries if there is no other way, and only after consulting with the lead developer.
- **NEVER** modify core app principles, such as networking, without prior approval from the lead developer.
- Only add things that aim to improve the experience of using this app, as it is unnecessary to
  add custom features that only benefit you to the full official app. Rather, you can keep those in a fork
  of the repo and ask me to add that fork to the README! ;)

### Questions or Feedback?
Feel free to contact me via [Discord](https://discord.com/users/772058278116851734)! ;)
