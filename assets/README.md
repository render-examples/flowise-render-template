# Template assets

The template README references two image files that must live in this folder before publishing to the Render gallery.

## Required

| File | Size | Notes |
|------|------|-------|
| `hero.png` | 1600×900 | Screenshot of the Flowise chatflow editor with real data (no Lorem Ipsum). This is the primary image on the gallery card. |
| `logo.png` | 512×512 | Flowise logo on a transparent background. Pull from [FlowiseAI/Flowise/assets](https://github.com/FlowiseAI/Flowise/tree/main/assets). |

## How to produce `hero.png`

1. Deploy this template once to your own Render account.
2. Log in to the running Flowise instance.
3. Build a small but realistic-looking chatflow (e.g. document loader → vector store → ChatOpenAI → conversation chain).
4. Take a 1600×900 screenshot of the editor canvas with the chatflow visible.
5. Save as `hero.png` in this folder.

## Optional

| File | Size | Notes |
|------|------|-------|
| `architecture.png` | any | Only if the mermaid diagram in the README isn't clear enough. Usually skip. |
