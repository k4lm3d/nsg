# NSG – Nousagi Gang PH's Gaming Group Website

> Nousagi Gang PH [NSG] — A Filipino community of text-based MMORPG players. 🇵🇭

## Site details

> General information about the site

### Site information

- Site name:  `Nousagi Gang PH`
- Description:  `Gaming Group Website`
- Powered by [Hugo](https://gohugo.io)
[![Hugo](https://img.shields.io/badge/Hugo-%5E0.101.0-ff4088?style=flat-square&logo=hugo)](https://gohugo.io/) [![Minimum Hugo Version](https://img.shields.io/static/v1?label=min-HUGO-version&message=0.87.0&color=blue&logo=hugo)](https://github.com/gohugoio/hugo/releases/tag/v0.87.0)
- Theme: [Blowfish](https://github.com/nunocoracao/blowfish/) by [Nuno Coracao](https://n9o.xyz)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/nunocoracao/blowfish?style=flat-square)](https://github.com/nunocoracao/blowfish/releases)
[![GitHub](https://img.shields.io/github/license/nunocoracao/blowfish)](https://github.com/nunocoracao/blowfish/blob/main/LICENSE)
[![Blowfish](https://img.shields.io/badge/Hugo--Themes-@Blowfish-blue)](https://themes.gohugo.io/themes/blowfish/)
![code-size](https://img.shields.io/github/languages/code-size/nunocoracao/blowfish)

[![Update Submodule](https://github.com/k4lm3d/nsg/actions/workflows/update-submodule.yml/badge.svg)](https://github.com/k4lm3d/nsg/actions/workflows/update-submodule.yml)

### Build & deploy

> Settings for Continuous Deployment from a Git repository

#### Repository

- Repository: [github.com/k4lm3d/nsg](https://github.com/k4lm3d/nsg)
- Branches: `main`, `dev`
- Owner: [k4lm3d](https://github.com/k4lm3d/)

#### Build settings

  - Base/root directory: `/`
  - Build command:
      - `hugo --gc --minify`
      - `bash render-build.sh` *(only for Render deployments)
  - Publish directory: `public`
  - Builds: `Active`
  - Deployment platforms used:
      - [Render](https://render.com)
      - [CloudFlare Pages](https://pages.dev)
      - [Firebase Hosting](https://firebase.google.com/)
  - Manual deployment: `false`
  - Auto-deploy: `true`

> [!IMPORTANT]
> - Hugo version: `0.155.3`
>     - Extended included
> - Blowfish: `v2.100.0`

### Domains

  > Use your own domain for your site

#### Custom domains

- Default subdomains:
    - ~~[nousagi.onrender.com](https://nousagi.onrender.com) *([Render](https://render.com/))*~~
    - Preview: [nsg.pages.dev](https://nsg.pages.dev) *([CloudFlare Pages](https://pages.dev/))*
    - Production: **[nousagigangph.web.app](https://nousagigangph.web.app)** *([Firebase Hosting](https://firebase.google.com/))*
    - Preview: [nousagigangph.firebaseapp.com](https://nousagigangph.firebaseapp.com) *([Firebase Hosting](https://firebase.google.com/))*
- Primary subdomains:
    - Preview: [nsg.is-local.org](https://nsg.is-local.org/) *([Open-Domains.net](https://open-domains.net/))*
    - Production: [nsg.foo.ng](https://nsg.foo.ng/) *([Pokymon](https://github.com/Pokymon))*
- Redirects automatically to primary domain: `false`
- Domain alias: `nousagi`, `nsg`, `nsgph`,  `nousagiph`, `nousagi-gang`, `nousagigangph`
- Temporary sites: https://fyi.me/p/nousagi

> [!IMPORTANT]
> Recommended web address to use is **https://nousagigangph.web.app**

### Support us

<a href='https://ko-fi.com/O5O21U14QZ' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi3.png?v=6' border='0' alt='Buy Us a Coffee at ko-fi.com' /></a>

### Resources

  - [Hugo Documentation](https://gohugo.io/documentation/)
  - [Blowfish Docs](https://blowfish.page/docs)
  - [GitHub Docs](https://docs.github.com/)
  - [Render Docs](https://docs.render.com/)
  - [Open-Domains Repository](https://github.com/open-domains/Register)
  - [Pokymon Repository](https://github.com/Pokymon/foo.ng)
  - [CloudFlare Pages docs](https://developers.cloudflare.com/pages/)
  - [Firebase Documentation](https://firebase.google.com/docs)

### Licensing

#### Source Code

Unless otherwise stated, the source code in this repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

#### Content

Website content, including articles, guides, documentation, screenshots, and other written materials, is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

#### Third-Party Software

This project uses third-party software and themes which are licensed under their respective licenses.
