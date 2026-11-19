# northerndoors.com.np

Website for Northern Doors, Kailashchaur Marg, Uttar Dhoka, Kathmandu.
Hosted on Mantra Digital's cPanel. Every push to `main` deploys automatically
through GitHub Actions (`.github/workflows/deploy.yml`) over FTPS.

## Repository secrets (Settings > Secrets and variables > Actions)

| Secret | Example |
| --- | --- |
| FTP_SERVER | ftp.northerndoors.com.np |
| FTP_USERNAME | deploy@northerndoors.com.np |
| FTP_PASSWORD | (password of the cPanel FTP account) |
| FTP_SERVER_DIR | `./` if the FTP account opens in public_html, otherwise `/public_html/` (must end with `/`) |

## Brand

Charcoal #262422 / #262520, Terracotta #B5532F, Sand #E6D8C3, Cream #F6F1E9.
Fonts: Fraunces (headlines), DM Sans (body). Slogan: "The answer is north."
