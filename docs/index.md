## Nekoweb-MkDocs

<https://github.com/fu-sen/Nekoweb-MkDocs>

**MkDocs with Nekoweb (minimal configuration)**

- [Nekoweb](https://nekoweb.org/)
- [MkDocs](https://www.mkdocs.org/)

## How to use

1. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
2. Add the pip package to `requirements.txt` . (Themes and plugins)
3. Log in to Nekoweb and Browse [API](https://nekoweb.org/api)
5. Select `Generate API Key` in `API Key`. 
6. The API Key will be displayed, so save this text string.
7. Select `Settings` for your GitHub project.
8. Select `Secrets and variables ` in `Secrets`.
9. Select `Actions`
10. Select `New repository secrets`.
11. Enter `NEKOWEB_API_KEY` in Name and API Key in Value.
12. Commit to a GitHub project: `git push`

