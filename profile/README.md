<div align="center">

<img src="https://raw.githubusercontent.com/mookie-studio/.github/main/profile/avatar-500.png" alt="mookie studio" width="120" />

# mookie studio

Small studio building focused, multi-tenant business software.

</div>

## What we are building

We maintain two products, each with its own repositories.

**Entry Hub** is a multi-tenant room booking platform: an API plus a web front-end that lets organizations manage rooms, equipment and reservations. The current release, **v1.0.0**, is a working demo. It is also the companion code for the blog series at [mookiefumi.github.io](https://mookiefumi.github.io).

**Just Looking** is a generic multi-tenant product catalog: an admin back office to manage products and a public catalog to browse them. It shows products; it does not sell them.

| Repository | What it is | Stack |
| --- | --- | --- |
| [`entry-hub`](https://github.com/mookie-studio/entry-hub) | Room booking demo for .NET 10: Minimal APIs, EF Core and PostgreSQL, orchestrated with Aspire and deployed to Kubernetes | .NET, PostgreSQL (Supabase), Supabase Auth |
| [`entry-hub-frontend`](https://github.com/mookie-studio/entry-hub-frontend) | React front-end of Entry Hub | React, Base UI (MIT), Tailwind CSS, Cloudflare Pages |
| [`just-looking`](https://github.com/mookie-studio/just-looking) | Generic multi-tenant product catalog: .NET 10 Minimal API and React SPA | .NET 10, React (Vite, TypeScript), Tailwind CSS, shadcn/ui |

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
