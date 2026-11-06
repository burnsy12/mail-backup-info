# Greg's Mail Backup: public information pages

Static application information and policies only. No credentials, mailbox contents, backup archives or runtime configuration belong in this repository.

Planned domain: https://backup.burnsemail.com/

Publish the main branch root with GitHub Pages. Configure the custom domain in GitHub before adding the DNS CNAME:

- Type: CNAME
- Name/host: backup
- Target: burnsy12.github.io

Use HTTPS once the certificate is provisioned. In Google Auth Platform Branding, use the site root, privacy.html and terms.html. Add burnsemail.com as the authorised domain. If Google requests ownership verification, verify burnsemail.com in Search Console while signed in as the OAuth project owner; add its generated TXT record without replacing existing records.
