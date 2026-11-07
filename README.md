# esteemworks.github.io

The website of EsteemWorks, a small family of free Windows apps: StartQueue and DynaTones.

Plain static HTML in English and German, one stylesheet, no JavaScript. It makes no requests to other hosts: the font
(Bricolage Grotesque, SIL Open Font License, in `assets/fonts`) and all images are part of the site. Light and dark
follow the color mode of the device.

| Path | Page |
| --- | --- |
| `index.html`, `de/index.html` | Home |
| `startqueue/`, `de/startqueue/` | StartQueue |
| `dynatones/`, `de/dynatones/` | DynaTones |
| `imprint/`, `de/impressum/` | Imprint (draft) |
| `privacy/`, `de/datenschutz/` | Privacy (draft) |

## Preview

Open `index.html` in a browser. All links are relative, so the site works straight from the folder.

## Before it goes live

- Fill the placeholders `[NAME]`, `[ANSCHRIFT]` and `[E-MAIL]` on the imprint and privacy pages in both languages, have
  both pages checked, and remove the draft note at the top of each
- The screenshots in `assets/img` (`startqueue-light.png`, `startqueue-dark.png`, `dynatones-light.png`,
  `dynatones-dark.png`) come from the apps' `docs/images`; replace them under the same names when they are taken again
- Versions and setup sizes on the app pages are written in the HTML; update them with each release

## Publishing

The site goes live through GitHub Pages at https://esteemworks.github.io/ only once this repository is made public and
Pages is switched on for the `main` branch. `.nojekyll` makes Pages serve the files as they are.
