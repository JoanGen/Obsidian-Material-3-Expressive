# Contributing Guidelines

Thank you for your interest in contributing to Material 3 Expressive!

If you find a bug or want to request a feature:
1. **Check if there is already an open issue** about that topic.
2. If it doesn't exist, **open a new issue** detailing the problem with screenshots, the Obsidian version you use, and which devices (Windows, macOS, Android, iOS) are affected.

If you want to contribute code (CSS):
1. **Fork** the repository.
2. Create a branch for your modification (`git checkout -b fix/issue-name` or `feature/new-feature`).
3. Follow the M3 design philosophy:
   - Use Obsidian's native variables whenever possible (`--background-primary`, etc.).
   - Do not break the mobile design.
   - Try not to use `!important` unless it is the only way to override the core application or a plugin's style.
   - Encapsulate your selectors well.
4. Commit your changes (`git commit -m "Fix modal borders"`).
5. Open a **pull request**.

By contributing, you agree that your contributions will be released under the MIT License of this project.