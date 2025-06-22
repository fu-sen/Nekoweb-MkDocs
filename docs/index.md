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
7. Browse [deploy2web # getting your cookie!](https://deploy.nekoweb.org/#getting-your-cookie)
8. Follow the steps described to get `Cookie Token` .
9. Select `Settings` for your GitHub project.
10. Select `Secrets and variables ` in `Secrets`.
11. Select `Actions`
12. Select `New repository secrets`.
13. Enter `NEKOWEB_API_KEY` in Name and API Key in Value.
14. Select `New repository secrets`.
15. Enter `NEKOWEB_COOKIE` in Name and Cookie Token in Value.
16. Commit to a GitHub project: `git push`

Cookie Token is optional.
