# Gentleflow · Legal

Public home for the **privacy policies** and **terms of use** of Gentleflow apps.
Served via GitHub Pages. Each app gets its own folder; every page is bilingual (English / 中文).

## Live URLs

- Home — https://gentleflow.github.io/legal/
- **Sweeple · 益智扫雷**
  - Support — https://gentleflow.github.io/legal/sweeple/
  - Privacy Policy — https://gentleflow.github.io/legal/sweeple/privacy/
  - Terms of Use — https://gentleflow.github.io/legal/sweeple/terms/
- **Ninefold Sudoku · 九重数独**
  - Support — https://gentleflow.github.io/legal/ninefold/
  - Privacy Policy — https://gentleflow.github.io/legal/ninefold/privacy/
  - Terms of Use — https://gentleflow.github.io/legal/ninefold/terms/
- **LifeForest · 人生森林**
  - Support — https://gentleflow.github.io/legal/lifeforest/
  - Privacy Policy — https://gentleflow.github.io/legal/lifeforest/privacy/
  - Terms of Use — https://gentleflow.github.io/legal/lifeforest/terms/

## Structure

```
/                       landing (app list)
/style.css              shared styles (light/dark aware)
/<app>/                 app support + contact page  → App Store "Support URL"
/<app>/privacy/         privacy policy              → App Store "Privacy Policy URL"
/<app>/terms/           terms of use / EULA
```

## Adding a new app

1. Copy the `ninefold/` folder to `<newapp>/`.
2. Update the app name, effective date, and the feature specifics (subscription contents, data practices) — keep it **truthful** to what the app actually does.
3. Add the app to the list in `/index.html`.
4. Commit; GitHub Pages redeploys automatically.

## Custom domain (optional)

To serve these at `gentleflow.app`, add a `CNAME` file and point DNS at GitHub Pages.
The in-app and App Store links would then change from `gentleflow.github.io/legal/...`
to the custom domain.

## Contact

gentleflowoverseas@gmail.com
