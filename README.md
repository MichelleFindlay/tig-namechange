# Your Name-Change Journey ✦

A single-page checklist for updating your UK documents after a name / gender marker change, themed with an ever-shifting mesh of the transgender and non-binary flag colours. 💙🤍💗💛🤍💜🖤

## Covers

- 📜 Deed poll / statutory declaration
- 🛂 Passport (deed poll + doctor's letter for gender marker)
- 🚗 Driving licence (DVLA)
- 💷 HMRC (tax / National Insurance)
- 🩺 NHS / GP records
- 👑 Bonus: Gender Recognition Certificate (extra sparkly)

## Features

- Animated mesh background cycling between trans and non-binary flag colours
- Floating documents and pens
- Circular button layout (stacks vertically on narrow screens)
- Mark-as-complete buttons with a progress bar
- Respects `prefers-reduced-motion`

## Use it

Just open `index.html` in a browser — no build step, no dependencies.
Or enable GitHub Pages (Settings → Pages → deploy from `main`) and it'll be live at your Pages URL.

## PHP version (with export / import)

`index.php` is the same page with two extra header buttons:

- **💾 Export (.xml)** downloads an XML file of everything you've filled in (deed poll, DVLA letter) plus your checklist ticks.
- **📂 Import (.xml)** loads one of those files back into the page, so you can pick up where you left off.

Nothing is stored on the server — the export is streamed straight back to you and an import only pre-fills the page you're looking at. Needs PHP 7.4+ with the `xmlwriter`, `dom` and `mbstring` extensions (all on by default). To try it locally:

```sh
php -S localhost:8080
```

then open http://localhost:8080/index.php.

> ⚠️ Fees and evidence requirements change — always double-check GOV.UK.
