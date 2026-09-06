# zhannaborodina.com

Личный сайт финансового советника Жанны Бородиной. Статический, без сборки.

- `index.html` — лендинг
- `privacy.html`, `consent-pdn.html`, `consent-ads.html`, `offer.html` — юридические документы
- `assets/` — общий `styles.css`, фото, эмблема, QR, OG-картинка
- `CNAME` — привязка домена для GitHub Pages

## Публикация

GitHub Pages: Settings → Pages → Source = `Deploy from a branch` → ветка `main`, папка `/ (root)`.
Любой `git push` в `main` обновляет сайт.

## Локальный просмотр

```
python3 -m http.server 8000
```
и открыть http://localhost:8000
