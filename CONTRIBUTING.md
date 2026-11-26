# Contributing to Nebeto Studio

Thank you for your interest in contributing to **Nebeto Studio**!

## Workflow

1. **Open or pick an issue** — Check existing issues or open one using our issue templates before starting large changes.
2. **Branch naming** — Create a branch matching our organization convention:
   - `feature/<short-slug>` or `feat/<short-slug>`
   - `bugfix/<short-slug>` or `fix/<short-slug>`
   - `hotfix/<short-slug>`
   - `docs/<short-slug>`
   - `chore/<short-slug>`
3. **Commits** — Follow [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`, `refactor:`, `ci:`, `chore:`) and **sign all commits** (SSH or GPG).
4. **Pull Request** — Fill out the PR template, ensure all automated CI gates pass, and resolve review threads before squash-merging.

## Quality Standards

- Strict typing, linting, and formatting must pass with zero warnings.
- Include automated tests covering new behavior or bug fixes.
- UI changes must respect **RGAA 4.1 / WCAG 2.1 AA** (Light & Dark themes).
- Never commit secrets, credentials, or personal data.

## Security

Please report security vulnerabilities privately following [`SECURITY.md`](./SECURITY.md).
