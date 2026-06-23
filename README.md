# Personal Portfolio

Astro-based personal portfolio starter for GitHub Pages.

This project is based on the MIT-licensed
[Smilesharks/dev-portfolio](https://github.com/Smilesharks/dev-portfolio)
template.

## Edit Content

Most profile content lives in `cv.json`.

Start with:

- `basics.name`
- `basics.label`
- `basics.summary`
- `basics.profiles`
- `skills`
- `projects`

To show a Discord icon next to GitHub, add a Discord profile to
`basics.profiles`:

```json
{
  "network": "Discord",
  "username": "your-discord-name",
  "url": "https://discord.com/users/your-discord-user-id"
}
```

## Skill Icons

The following `skills.name` values have matching icons:

```txt
HTML
CSS
JavaScript
TypeScript
React
Node
MySQL
Git
GitHub
Next.js
Tailwind
Swift
SwiftUI
Kotlin
Flutter
Figma
Gitlab
C
Python
Linux
Docker
Wireshark
Kali Linux
Burp Suite
OWASP
Hack The Box
Metasploit
```

## Commands

```bash
npm install
npm run dev
npm run build
npm run preview
```

## GitHub Pages

This site is configured for the user page repository:

```txt
gik2927.github.io
```

Create a public GitHub repository named `gik2927.github.io`, push this project
to the `main` branch, then set `Settings > Pages > Source` to `GitHub Actions`.
The workflow in `.github/workflows/deploy.yml` will build and deploy the site.

## Dependency Note

This starter currently uses Astro 4 because the local Node.js version is 20.x.
Astro 7 requires Node.js 22.12 or newer. After upgrading Node, migrate Astro to
the latest major version and rerun `npm audit`.
