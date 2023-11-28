<p align='center'>
  <img src='https://raw.githubusercontent.com/nyxb/velocita/main/.github/assets/Velocita_banner.png' alt='Velocita - Meinungsbildende Vite Starter-Vorlage' width='600'/>
</p>

<p align='center'>
Erstelle Webanwendungen schnell mit <sup><em>Velocita</em></sup>
<br>
</p>

<br>

<p align='center'>
<a href="https://velocita.netlify.app/">Online-Demo</a>
</p>

<br>

> **Hinweis**: Diese Vorlage wurde in den frühen Phasen von Vue 3 und Vite erstellt. Wenn du nach einer besseren Vue-Entwicklungserfahrung und kontinuierlicher Wartung suchst, empfehlen wir dir, [Nuxt 3](https://nuxt.com) zu verwenden (das kannst du auch als SPA oder SSG nutzen, je nach Bedarf). Diese Vorlage wird weiterhin als Referenz langsam gepflegt, aber es wird nicht viele Updates geben.

<br>

<p align='center'>
<a href="https://github.com/nyxb/velocita/blob/main/README.md">Englisch</a> | <b>German</b>
</p>

<br>

## Features

- ⚡️ [Vue 3](https://github.com/vuejs/core), [Vite](https://github.com/vitejs/vite), [pnpm](https://pnpm.io/), [esbuild](https://github.com/evanw/esbuild) - es ist superschnell!

- 🗂 [Dateibasiertes Routing](./src/pages)

- 📦 [Automatisches Laden von Komponenten](./src/components)

- 🍍 [Zustandsverwaltung mit Pinia](https://pinia.vuejs.org)

- 📑 [Layout-System](./src/layouts)

- 📲 [PWA](https://github.com/nyxb/vite-plugin-pwa)

- 🎨 [UnoCSS](https://github.com/unocss/unocss) - Ein Atomic-CSS-Engine, der sowohl leistungsstark als auch flexibel ist

- 😃 [Verschiedene Icon-Sets für dich](https://github.com/nyxb/unocss/tree/main/packages/preset-icons)

- 🌍 [I18n Internationalisierung sofort einsatzbereit](./locales)

- 🗒 [Markdown-Unterstützung](https://github.com/unplugin/unplugin-vue-markdown)

- 🔥 Nutze die [neue `<script setup>` Syntax](https://github.com/vuejs/rfcs/pull/227)

- 📥 [API-Autoimport](https://github.com/unplugin/unplugin-auto-import) - Nutze die Composition API direkt ohne Import

- 🖨 Erzeuge serverseitig mit [vite-ssg](https://github.com/nyxb/vite-ssg)

- 🦔 Generiere kritische CSS mit [critters](https://github.com/GoogleChromeLabs/critters)

- 🦾 TypeScript, natürlich

- ⚙️ Nutze [GitHub Actions](https://github.com/features/actions) für Unit-Tests mit [Vitest](https://github.com/vitest-dev/vitest), E2E-Tests mit [Cypress](https://cypress.io/)

- ☁️ Einfaches Deployment auf Netlify ohne Konfiguration

<br>

## Vorkonfiguration

### UI-Framework

- [UnoCSS](https://github.com/antfu/unocss) - Ein leistungsstarker und flexibler Atomic-CSS-Engine

### Icons

- [Iconify](https://iconify.design) - Nutze beliebige Icon-Sets, schau mal hier: [🔍Icônes](https://icones.netlify.app/)
- [UnoCSS's Pure CSS Icon-Lösungen](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

### Plugins

- [Vue Router](https://github.com/vuejs/router)
  - [`unplugin-vue-router`](https://github.com/posva/unplugin-vue-router) - Routing basierend auf deinem Dateisystem
  - [`vite-plugin-vue-layouts`](https://github.com/JohnCampionJr/vite-plugin-vue-layouts) - Layoutsystem für deine Seiten
- [Pinia](https://pinia.vuejs.org) - Eine direkte, typ

sichere und flexible Zustandsverwaltung
- [`unplugin-vue-components`](https://github.com/antfu/unplugin-vue-components) - Lade deine Komponenten automatisch
- [`unplugin-auto-import`](https://github.com/antfu/unplugin-auto-import) - Nutze APIs wie die Composition API direkt ohne Import
- [`vite-plugin-pwa`](https://github.com/antfu/vite-plugin-pwa) - PWA Support
- [`unplugin-vue-markdown`](https://github.com/antfu/unplugin-vue-markdown) - Markdown als Komponenten und umgekehrt
  - [`markdown-it-prism`](https://github.com/jGleitz/markdown-it-prism) - Syntaxhervorhebung mit Prism
  - [`prism-theme-vars`](https://github.com/antfu/prism-theme-vars) - Passe Prism.js-Themen mit CSS-Variablen an
- [Vue I18n](https://github.com/intlify/vue-i18n-next) - Internationalisierung
  - [`unplugin-vue-i18n`](https://github.com/intlify/bundle-tools/tree/main/packages/unplugin-vue-i18n) - Vue I18n Vite Plugin
- [VueUse](https://github.com/antfu/vueuse) - Sammlung von nützlichen Composition APIs
- [`vite-ssg-sitemap`](https://github.com/jbaubree/vite-ssg-sitemap) - Sitemap-Generator
- [`@vueuse/head`](https://github.com/vueuse/head) - Bearbeite den Dokumentenkopf reaktionsfähig
- [`vite-plugin-vue-devtools`](https://github.com/webfansplz/vite-plugin-vue-devtools) - Ein Vite-Plugin, das deine Vue-Entwicklungserfahrung verbessert

### Codierungsstil

- Nutze die Composition API mit der [`<script setup>` SFC Syntax](https://github.com/vuejs/rfcs/pull/227)
- [ESLint](https://eslint.org/) konfiguriert nach [@nyxb/eslint-config](https://github.com/nyxb/eslint-config), Einzelzitate, ohne Semikolons.

### Entwicklungswerkzeuge

- [TypeScript](https://www.typescriptlang.org/)
- [Vitest](https://github.com/vitest-dev/vitest) - Ein Unit-Test-Framework basierend auf Vite
- [Cypress](https://cypress.io/) - E2E-Tests
- [pnpm](https://pnpm.js.org/) - Ein schneller, platzsparender Paketmanager
- [`vite-ssg`](https://github.com/antfu/vite-ssg) - Serverseitige Generierung
   - [critters](https://github.com/GoogleChromeLabs/critters) - Generator für kritischen CSS
- [Netlify](https://www.netlify.com/) - Deployment ohne jegliche Konfiguration
- [VS Code Erweiterungen](./.vscode/extensions.json)
  - [Velocita](https://marketplace.visualstudio.com/items?itemName=nyxb.velocita) - Startet den Vite-Server automatisch
  - [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) - IDE-Unterstützung für Vue 3 `<script setup>`
  - [Iconify IntelliSense](https://marketplace.visualstudio.com/items?itemName=antfu.iconify) - Icons werden direkt angezeigt und vervollständigt
  - [i18n Ally](https://marketplace.visualstudio.com/items?itemName=lokalise.i18n-ally) - Unterstützung für I18n in einem

## Ablegerprojekte

Weil dieses Template für spezifische Anwendungsfälle gemacht ist, findest du hier eine Liste von Ablegern aus der Community mit verschiedenen Vorlieben und Funktionssätzen. Schau sie dir an. Und klar, du kannst auch gerne einen Pull Request mit deinem eigenen Projekt einreichen!

###### Offiziell

- [velocita-lite](https://github.com/nyxb/velocita-lite) - Die leichte Version von Velocita
- [velocita-nuxt3](https://github.com/nyxb/velocita-nuxt3) - Die Nuxt 3 Version von Velocita
- [velocita-nuxt-bridge](https://github.com/nyxb/velocita-nuxt-bridge) - Die Nuxt2 Bridge-Version von Velocita
- [velocita-webext](https://github.com/nyxb/velocita-webext) - Ein sofort einsatzbereites Template

 für Browser-Erweiterungen mit Vite

###### Community

[Schau dir die englische Version an](./README.md#community)

## Probier's aus!

> Velocita benötigt Node.js Version >=14.18

### GitHub Template

[Erstelle ein Repository mit diesem Template](https://github.com/nyxb/velocita/generate).

### Lokal klonen

Wenn du es vorziehst, das manuell mit einer sauberen Git-Historie zu tun:

```bash
npx degit nyxb/velocita my-velocita-app
cd my-velocita-app
pnpm i # Wenn du pnpm noch nicht hast, installiere es zuerst: npm install -g pnpm
```

## Checkliste

Wenn du dieses Template nutzt, aktualisiere deine eigenen Informationen nach dieser Checkliste:

- [ ] Ändere den Autorennamen in `LICENSE`
- [ ] Ändere den Titel in `App.vue`
- [ ] Ändere den Hostnamen in `vite.config.ts`
- [ ] Ändere das Favicon im `public`-Verzeichnis
- [ ] Entferne die Infos über Sponsoren im `.github`-Ordner
- [ ] Überarbeite die README und lösche die Anleitungen

Danach, genieße es :)

## Nutzung

### Entwickeln

Mit dem folgenden Befehl kannst du die Anwendung unter http://localhost:3333 sehen:

```bash
pnpm dev
```

### Bauen

Um die Anwendung zu bauen, führe einfach den folgenden Befehl aus:

```bash
pnpm build
```

Danach siehst du den für die Veröffentlichung vorgesehenen `dist`-Ordner.

### Deployment auf Netlify

Geh zu [Netlify](https://app.netlify.com/start) und wähle dein Repository aus, klicke dich durch mit `OK`, und nach einer kurzen Wartezeit wird deine Anwendung erstellt.
