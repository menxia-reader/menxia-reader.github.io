# menxia-reader.github.io

Org root site for [门下 (menxia)](https://menxia-reader.github.io/menxia/).

- `.well-known/apple-app-site-association` — Universal Links for the iOS app (`/menxia/*`).
- `.nojekyll` — required, otherwise Jekyll skips `.well-known/`.
- `index.html` — redirects to `/menxia/`.

The reader itself lives in [menxia-reader/menxia](https://github.com/menxia-reader/menxia). It sits on its own org origin so its token in localStorage is not shared with any other Pages site.
