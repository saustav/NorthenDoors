# northerndoors.com.np

Website for Northern Doors, Kailashchaur Marg, Uttar Dhoka, Kathmandu.
Hosted on Mantra Digital's cPanel (account hprnepal, addon domain,
document root `/home2/hprnepal/northerndoors.com.np`). Never deploy to
`public_html`: that is hprnepal.org.np. Every push to `main` deploys automatically
through GitHub Actions (`.github/workflows/deploy.yml`) over FTPS.

Server: `fishtail.mysecurecloudserver.com` (set in the workflow; the domain is
proxied by Cloudflare, so `ftp.<domain>` does not reach cPanel).

## Repository secrets (Settings > Secrets and variables > Actions)

| Secret | Example |
| --- | --- |
| FTP_USERNAME | deploy@northerndoors.com.np |
| FTP_PASSWORD | (password of the cPanel FTP account) |
| FTP_SERVER_DIR | `./` (the deploy FTP account opens in /home2/hprnepal/northerndoors.com.np) |

## Brand

Charcoal #262422 / #262520, Terracotta #B5532F, Sand #E6D8C3, Cream #F6F1E9.
Fonts: Fraunces (headlines), DM Sans (body). Slogan: "The answer is north."
