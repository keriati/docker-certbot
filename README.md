# Docker Certbot Cloudflare DNS

Get certificates with certbot using cloudflare dns in docker.

See: 
- 
- https://eff-certbot.readthedocs.io/en/stable/install.html#running-with-docker
- https://hub.docker.com/r/certbot/dns-cloudflare
- https://certbot-dns-cloudflare.readthedocs.io/en/stable/

## Step 1:

Set your cloudflare token in cloudflare.ini dns_cloudflare_api_token

## Step 2:

Set your environment variables:

- APP_DIR
- CERT_DOMAIN
- CLOUDFLARE_EMAIL

## Step 3:

Run your container.

Results will be in __etc-letsencrypt__ directory