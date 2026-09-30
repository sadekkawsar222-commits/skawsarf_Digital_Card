# Sadek Kawsar: digital card

A single-page digital visiting card. Static site: no build step, no dependencies.

## Files
| File | What it is |
|---|---|
| `index.html` | The whole card (styles, scripts and profile photo are inside it) |
| `og.jpg` | Picture shown in WhatsApp / LinkedIn link previews |
| `vercel.json` | Vercel settings |

## Put it on GitHub
1. On github.com click **New repository**. Name it `digital-card`. Leave it empty.
2. Click **uploading an existing file** and drag in everything from this folder (include the hidden files if your system shows them). Click **Commit changes**.

## Publish it (pick one)
**Vercel (recommended)**
1. On vercel.com choose **Add New, Project** and import the `digital-card` repository.
2. Framework preset: **Other**. Leave build and output settings empty. Click **Deploy**.
3. You get an address such as `https://digital-card.vercel.app`.

**GitHub Pages**
1. In the repository open **Settings, Pages**.
2. Source: **Deploy from a branch**. Branch: `main`, folder `/ (root)`. Save.
3. Your address is `https://YOUR-USERNAME.github.io/digital-card/`.

## One edit after the first deploy
`index.html` has three lines (in the `<head>`) containing `YOUR-PROJECT.vercel.app`.
Replace it with your real address and commit. This makes the link preview show your photo and name in WhatsApp and LinkedIn. The card works without this step.

## Changing your details
Everything personal is in the `CONFIG` object near the bottom of `index.html`:
name, role, company, links, phone, emails, quote, photo, and the optional watermark.
