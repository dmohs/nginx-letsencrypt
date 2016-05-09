# nginx-letsencrypt

Nginx with Let's Encrypt installed for TLS certificate generation.

## Generate or renew a certificate

```bash
/opt/certbot-*/letsencrypt-auto \
  --email 'your-email@example.com' \
  --agree-tos \
  certonly \
  --webroot -w /usr/share/nginx/html \
  -d 'your.domain.com'
```
