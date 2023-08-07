# Legendary Fiesta

General Info

![GitHub](https://img.shields.io/github/license/cornersyrup/legendary-fiesta)

Release Info

![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/cornersyrup/legendary-fiesta?sort=semver)
[![Deploy to GitHub Pages](https://github.com/cornersyrup/legendary-fiesta/actions/workflows/vite-gh-pages.yml/badge.svg?branch=main)](https://github.com/cornersyrup/legendary-fiesta/actions/workflows/vite-gh-pages.yml)
![Website](https://img.shields.io/website?down_color=lightgrey&down_message=offline&up_color=blue&up_message=online&url=https%3A%2F%2Fcornersyrup.github.io%2Flegendary-fiesta%2F)
![jsDelivr hits (GitHub)](https://img.shields.io/jsdelivr/gh/hm/cornersyrup/legendary-fiesta)

Development Info

![GitHub language count](https://img.shields.io/github/languages/count/cornersyrup/legendary-fiesta)
![GitHub top language](https://img.shields.io/github/languages/top/cornersyrup/legendary-fiesta)
![GitHub package.json dependency version (subfolder of monorepo)](https://img.shields.io/github/package-json/dependency-version/cornersyrup/legendary-fiesta/vue)

[![CodeFactor](https://www.codefactor.io/repository/github/cornersyrup/legendary-fiesta/badge)](https://www.codefactor.io/repository/github/cornersyrup/legendary-fiesta)
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/cornersyrup/legendary-fiesta)

Try it out on [GitHub Pages](https://cornersyrup.github.io/legendary-fiesta/)!

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz_small.svg)](https://stackblitz.com/github/cornersyrup/legendary-fiesta)
[![Open in vscode.dev](https://img.shields.io/badge/-Open%20in%20vscode.dev-007ACC?logo=Visual%20Studio%20Code)](https://vscode.dev/github/cornersyrup/legendary-fiesta)

## Installation

```sh
git clone https://github.com/cornersyrup/legendary-fiesta.git
cd legendary-fiesta
npm install
```

## Usage

```sh
npm run serve
```

## Behaviour

- PWA (manifest.json)
  - installable web app
- Service worker
  - cacheing for offline
  - prompt install in browser (chrome, edge)
- IndexedDB
- LocalStorage
- Notification
- Share API

### HTTPS

This app include share feature, which require secure context.
By providing `cert.pem` and `key.pem` in `certs` directory, vite will be execute in HTTPS with config.

### Configuration

The app require the following env var to function properly.

- `API_SERVER`: url to api server. Default: http://localhost:5173/legendary-fiesta/data

## Notes

Mount [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) with the following setting in workspace.

```json
{
  "liveServer.settings.mount": [["/legendary-fiesta", "./dist"]]
}
```
