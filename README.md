# RecipeBox — privacy policy and support pages

This repository exists only to publish two pages that App Store Connect
requires as public URLs. It is public because GitHub Pages does not serve a
private repository on the free plan; the app's source stays private.

| Field in App Store Connect | URL |
|---|---|
| Privacy Policy URL | https://hyorinmaruk.github.io/recipebox-site/privacy/ |
| Support URL | https://hyorinmaruk.github.io/recipebox-site/support/ |
| Marketing URL (optional) | https://hyorinmaruk.github.io/recipebox-site/ |

## Do not edit these files here

`docs/` in the private `recipebox` repository is the source. To publish a
change, make it there and copy it over:

```
cp -R ~/recipebox/docs/. ~/recipebox-site/
cd ~/recipebox-site && git add -A && git commit -m "Sync from recipebox/docs" && git push
```

`store/privacy-policy.md` in that repository holds the same policy text in
Markdown and is edited together with the HTML.
