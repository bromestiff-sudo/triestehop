# Trieste Hop

A 2D platformer set in Trieste, by Kokoro Studio. Play it at https://triestehop.pages.dev/

Every push to `main` publishes the site to Cloudflare Pages through `.github/workflows/deploy.yml`.
The workflow needs two repository secrets: `CLOUDFLARE_API_TOKEN` (permission: Account → Cloudflare Pages → Edit) and `CLOUDFLARE_ACCOUNT_ID`.
