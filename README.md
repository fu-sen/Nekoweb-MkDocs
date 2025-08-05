<!-- 2025/06/22 MkDocs 1.6.1 -->

## Nekoweb-MkDocs

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
16. Select `New repository secrets`.
17. Enter `NEKOWEB_DIRECTORY` in output directory on Nekoweb
18. Commit to a GitHub project: `git push`

Cookie Token is optional.

## Note

If you have created your own `elements.css` ,
please include the file in the `docs/` folder.

New routing support is now available on July 25, 2025.
If your Nekoweb is using outdated routing support,
you need a fix for '.github/workflows/deploy.yaml'.

## Build error

Many of the build error are that you mistyped `mkdocs.yml`
or you forgot to add the package to` requirements.txt`.
Check the file change immediately before the error occurred.

This is often not a problem with this project.
You should not open an issue for that.
