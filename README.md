<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg" />
  <img alt="Dino Kliček, frontend engineer" src="assets/header-dark.svg" width="100%" />
</picture>

Frontend engineer based in Croatia. I ship small tools: Angular form controls, browser extensions, an IDE plugin, watch faces.

Angular and TypeScript most days. Web scraping in my spare time, which is where the power-outage extension came from.

[LinkedIn](https://www.linkedin.com/in/dineeek) · [Email](mailto:dineeek.dev@gmail.com) · [npm](https://www.npmjs.com/~dklicek) · [JetBrains Marketplace](https://plugins.jetbrains.com/vendor/dineeek)

## Things I've shipped

<table>
  <tr>
    <td width="240"><a href="https://github.com/dineeek/ng-nx-scaffolder"><img src="assets/thumb-scaffolder.png" width="220" alt="Scaffolder preview dialog" /></a></td>
    <td><b><a href="https://github.com/dineeek/ng-nx-scaffolder">Angular/Nx Scaffolder</a></b> &nbsp; <a href="https://plugins.jetbrains.com/plugin/31141-angular-nx-scaffolder"><img src="https://img.shields.io/jetbrains/plugin/v/31141?label=Marketplace" alt="JetBrains Marketplace" /></a><br/><br/>IntelliJ and WebStorm plugin that scaffolds Angular and Nx libraries with standalone components, <code>inject()</code> and signalStore already wired. Written in Kotlin.</td>
  </tr>
  <tr>
    <td width="240"><a href="https://github.com/dineeek/ngx-libs-workspace"><img src="assets/thumb-ngx-libs.png" width="220" alt="Numeric range form field" /></a></td>
    <td><b><a href="https://github.com/dineeek/ngx-libs-workspace">ngx-libs-workspace</a></b> &nbsp; <a href="https://dineeek.github.io/ngx-libs-workspace">Live playground</a><br/><br/>Five reactive Angular form controls built on Signal Forms, themable with CSS custom properties, free of Material, CDK and <code>ControlValueAccessor</code>. Packages listed below.</td>
  </tr>
  <tr>
    <td width="240"><a href="https://github.com/dineeek/hep-bez-struje"><img src="assets/thumb-hep.png" width="220" alt="Outage list in the extension popup" /></a></td>
    <td><b><a href="https://github.com/dineeek/hep-bez-struje">hep-bez-struje</a></b> &nbsp; <a href="https://chromewebstore.google.com/detail/hep-bez-struje/hahhmkkofmofnadefiadmpmcencoaljf"><img src="https://img.shields.io/chrome-web-store/v/hahhmkkofmofnadefiadmpmcencoaljf?label=Chrome%20Web%20Store" alt="Chrome Web Store" /></a><br/><br/>Chrome extension that shows which areas of Croatia are without power, scraped from the HEP site. React and TypeScript.</td>
  </tr>
  <tr>
    <td width="240"><a href="https://github.com/dineeek/najbrzi-prst"><img src="assets/thumb-najbrzi.png" width="220" alt="Countdown panel on a page" /></a></td>
    <td><b><a href="https://github.com/dineeek/najbrzi-prst">najbrzi-prst</a></b> &nbsp; <a href="https://github.com/dineeek/najbrzi-prst/releases"><img src="https://img.shields.io/github/v/release/dineeek/najbrzi-prst?label=Release&cacheSeconds=3600" alt="Release" /></a><br/><br/>Chrome extension that clicks a chosen button at an exact server-synced second. Made for Croatian public calls where funds go by order of receipt.</td>
  </tr>
</table>

## npm packages

| Package | What it does | Downloads |
|-|-|-|
| [ngx-numeric-range-form-field](https://github.com/dineeek/ngx-libs-workspace/tree/main/libs/ngx-numeric-range-form-field) | Two number inputs, one value, with validators for order, bounds, completeness and span. | [![npm](https://img.shields.io/npm/dm/ngx-numeric-range-form-field)](https://www.npmjs.com/package/ngx-numeric-range-form-field) |
| [ngx-pass-code](https://github.com/dineeek/ngx-libs-workspace/tree/main/libs/ngx-pass-code) | OTP and pass-code input, one box per character, paste anywhere. | [![npm](https://img.shields.io/npm/dm/ngx-pass-code)](https://www.npmjs.com/package/ngx-pass-code) |
| [ngx-phone-form-field](https://github.com/dineeek/ngx-libs-workspace/tree/main/libs/ngx-phone-form-field) | Country picker with flags plus national number, stored as one E.164 string. | [![npm](https://img.shields.io/npm/dm/ngx-phone-form-field)](https://www.npmjs.com/package/ngx-phone-form-field) |
| [ngx-time-range-form-field](https://github.com/dineeek/ngx-libs-workspace/tree/main/libs/ngx-time-range-form-field) | Two time inputs, one value, same validator set as the numeric range. | [![npm](https://img.shields.io/npm/dm/ngx-time-range-form-field)](https://www.npmjs.com/package/ngx-time-range-form-field) |
| [ngx-overflow-tooltip](https://github.com/dineeek/ngx-libs-workspace/tree/main/libs/ngx-overflow-tooltip) | Headless directive that exposes an `isTruncated` signal when an element's text is ellipsized. | [![npm](https://img.shields.io/npm/dm/ngx-overflow-tooltip)](https://www.npmjs.com/package/ngx-overflow-tooltip) |
| [crnk-filtering](https://github.com/dineeek/crnk-filtering) | Zero-dependency builder for CRNK and JSON:API filter, sort and pagination query strings. Works with any HTTP client. | [![npm](https://img.shields.io/npm/dm/crnk-filtering)](https://www.npmjs.com/package/crnk-filtering) |

## What I'm working on

| | |
|-|-|
| **Maintaining** | [ngx-libs-workspace](https://github.com/dineeek/ngx-libs-workspace), keeping the five controls current with Angular Signal Forms. |
| **Building** | Four Garmin Connect IQ watch faces in Monkey C: Noir Aurum, Azimuth, Console and Croata. Packaged, store listings next.<br/><br/><img src="assets/face-noir-aurum.png" width="80" alt="Noir Aurum" /> <img src="assets/face-azimuth.png" width="80" alt="Azimuth" /> <img src="assets/face-console.png" width="80" alt="Console" /> <img src="assets/face-croata.png" width="80" alt="Croata" /> |
| **Exploring** | Zoneless Angular, and where AI-assisted development saves time versus where a generator like the scaffolder does it cheaper. |

## Stack

Angular, TypeScript, Nx, NgRx signals, RxJS, Jest, Playwright. Kotlin for the IDE plugin, Monkey C for the watch faces.

Also comfortable on the Java/Quarkus side: SQL, PDF and email templating, Helm and GitOps config.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dineeek/dineeek/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dineeek/dineeek/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/dineeek/dineeek/output/github-snake-dark.svg" />
</picture>
