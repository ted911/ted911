---
description: Automate git commit and push with Angular conventions
---

1. Check the current status of the repository.
   - Run `git status` to see which files have changed.
   - Run `git diff` to inspect the actual changes in the files.

2. Generate a commit message based on the changes, following the **Angular Commit Message Conventions**:
   - Format: `type(scope): subject`
   - **Types**:
     - `feat`: A new feature
     - `fix`: A bug fix
     - `docs`: Documentation only changes
     - `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc)
     - `refactor`: A code change that neither fixes a bug nor adds a feature
     - `perf`: A code change that improves performance
     - `test`: Adding missing tests or correcting existing tests
     - `chore`: Changes to the build process or auxiliary tools and libraries such as documentation generation
   - **Scope**: (Optional) The scope of the core component changed (e.g., `workflow`, `api`, `auth`).
   - **Subject**: Use the imperative mood, lower case, no dot at the end.

3. Stage all changes.
   // turbo
   - Run `git add .`

4. Commit the changes with the generated message.
   - Run `git commit -m "YOUR_GENERATED_MESSAGE"` (Replace `YOUR_GENERATED_MESSAGE` with the message you created).

5. Push the changes to the remote repository.
   // turbo
   - Run `git push`
