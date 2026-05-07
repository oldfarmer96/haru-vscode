# Contributing to Haru Theme

Thanks for contributing to Haru Theme.

## Ways to contribute

- Report readability or contrast issues.
- Propose token color improvements for specific languages.
- Improve documentation and preview assets.
- Suggest accessibility improvements.

## Reporting issues

When opening an issue, include:

- VS Code version.
- Language and file type.
- Whether semantic highlighting is enabled.
- Screenshot of the problem area.
- Expected behavior and current behavior.

## Development workflow

1. Fork the repository.
2. Create a branch: `feat/short-description` or `fix/short-description`.
3. Update theme values in `themes/haru-color-theme.json`.
4. Test in VS Code using Extension Development Host (`F5`).
5. Validate in at least these contexts:
   - Editor UI (tabs, sidebar, activity bar)
   - Source code tokens
   - Markdown preview and terminal colors
6. Open a Pull Request with before/after screenshots.

## Style guidelines

- Keep the palette calm and focus-oriented.
- Avoid introducing extreme contrast unless fixing accessibility issues.
- Preserve visual consistency across UI and token colors.
- Prefer small, focused PRs.

## Pull Request checklist

- [ ] Theme changes are tested in VS Code.
- [ ] Screenshots are included.
- [ ] `README.md` updated if behavior/documentation changed.
- [ ] `CHANGELOG.md` updated under `Unreleased`.

## Commit message guidance

Use clear messages such as:

- `feat(theme): add better Go token coverage`
- `fix(colors): improve selection contrast in editor`
- `docs(readme): add language preview section`

Thank you for helping improve Haru Theme.
