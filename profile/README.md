<div align="center">

<img src="https://raw.githubusercontent.com/mookie-studio/.github/main/profile/avatar-500.png" alt="mookie studio" width="120" />

# mookie studio

Small studio building focused, multi-tenant business software.

</div>

## What we are building

**Entry Hub** is a multi-tenant room booking platform: an API plus a web front-end that lets organizations manage rooms, equipment and reservations. The current release, **v1.0.0**, is a working demo.

| Repository | What it is | Stack |
| --- | --- | --- |
| [`entry-hub`](https://github.com/mookie-studio/entry-hub) | Room booking API | .NET, PostgreSQL (Supabase), Supabase Auth |
| [`entry-hub-frontend`](https://github.com/mookie-studio/entry-hub-frontend) | Web front-end | React, Base UI (MIT), Tailwind CSS, Cloudflare Pages |

## How we work

- **Multi-tenant by design.** Every entity carries a `tenant_id`, the tenant comes from the access token, and PostgreSQL row level security enforces isolation.
- **Open and permissive.** We prefer MIT-licensed building blocks.
- **Small, reviewable changes.** One pull request per backlog item, tracked as GitHub Issues.
- **English in the repositories.** Code, issues and pull requests are written in English.

## Contributing

Read our [contributing guide](https://github.com/mookie-studio/.github/blob/main/CONTRIBUTING.md) and [code of conduct](https://github.com/mookie-studio/.github/blob/main/CODE_OF_CONDUCT.md). To report a vulnerability, follow the [security policy](https://github.com/mookie-studio/.github/blob/main/SECURITY.md).

## Contact

- Website: TBD
- Email: me@mookiefumi.com
