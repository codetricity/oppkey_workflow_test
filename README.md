# Oppkey workflow with Sparrow bootstrap template

1. `npm run start` to monitor changes
1. put images in `public/assets/img/oppkey/`
1. edit `src/pug/mixins/homes/Oppkey.pug`
1. edit `package.json` for version
1. `npm run live` to build live version
1. edit `package.json` script for `publish` and add prefix for the live version
   example:     `"publish": "git subtree push --prefix live/v1.0.0 origin gh-pages",`
1. `git add` and `git commit -m "message"`
1. `git push origin main`
1. `npm run publish` to publish to gh-pages
