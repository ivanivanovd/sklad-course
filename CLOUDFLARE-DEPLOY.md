# Cloudflare Pages deploy

В репозитории уже есть другой `index.html`, поэтому для Cloudflare Pages используйте отдельную папку `cloudflare-site` как Build output directory.

- Framework preset: None
- Production branch: `codex/maya-english-site`
- Build command: `exit 0`
- Build output directory: `cloudflare-site`
- Root directory: оставить пустым

В `cloudflare-site` лежат `index.html` сайта Майи и папка `assets` с её фото. После успешной первой публикации добавьте свой домен в Pages → Custom domains. DNS и домен выбираются из зон, которые доступны в аккаунте Cloudflare.
