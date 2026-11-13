# Sito sunser.it

- `sito/` contiene tutti i file pubblicati su https://sunser.it
- `wrangler.jsonc` dice a Cloudflare cosa pubblicare e su quali domini (sunser.it, www.sunser.it)
- Ogni modifica salvata sul ramo `main` viene pubblicata automaticamente da Cloudflare (Workers Builds)
- Per pubblicare a mano: Cloudflare > Workers & Pages > sunser-website > New deployment, caricando il contenuto di `sito/`
