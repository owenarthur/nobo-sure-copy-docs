# Sure Copy docs site — ready to publish

9 static HTML pages (docs + privacy + EULA), zero dependencies. Publish any way:

**GitHub Pages (fastest):**
```
cd site && git init && git add . && git commit -m "Sure Copy docs"
gh repo create nobo-sure-copy-docs --public --source=. --push   # needs gh auth
# then: repo Settings → Pages → deploy from main /(root)
# URLs → https://<user>.github.io/nobo-sure-copy-docs/{index,privacy,eula}.html
```
**Netlify/Cloudflare Pages:** drag the `site/` folder into a new project.
**nobo.dev:** upload `site/*` to any path; use those URLs.

Once live, the listing needs: documentation = index.html, privacy = privacy.html, EULA = eula.html.
