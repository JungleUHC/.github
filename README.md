# `.github`

Org-level GitHub configuration for [JungleUHC](https://github.com/JungleUHC).

| Path | Purpose |
| --- | --- |
| `profile/README.md` | The organisation profile, rendered on [github.com/JungleUHC](https://github.com/JungleUHC). |
| `profile/assets/` | Images the profile references. Committed here rather than hotlinked, so the profile never depends on another deployment. |

This repository must stay **public** for the profile to render — GitHub ignores
`profile/README.md` in a private `.github` repository. The members-only profile
lives in a separate private repository, and only members ever see it.
