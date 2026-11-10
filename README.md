# kronopuzzle.github.io

The public site of Krono Puzzle: the privacy policy and the support page in
English, Spanish (Spain), and Portuguese (Brazil).

| Page           | English     | Spanish (Spain) | Portuguese (Brazil) |
| -------------- | ----------- | --------------- | ------------------- |
| Home           | `/`         | `/es/`          | `/pt-br/`           |
| Privacy policy | `/privacy/` | `/es/privacy/`  | `/pt-br/privacy/`   |
| Support        | `/support/` | `/es/support/`  | `/pt-br/support/`   |

The pages are static HTML with one local stylesheet. They use no analytics, no
cookies, no scripts, no third-party fonts, and no embedded content.

## Support contact

The support address is defined only in `_config.yml` (`support_email`). Every
page reads it through `{{ site.support_email }}`, rendered by the built-in
GitHub Pages build. To change the address, edit that one line.

## Publishing

`main` is served by GitHub Pages, so merging to `main` publishes the site.
