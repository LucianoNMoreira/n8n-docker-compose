# n8n-docker-compose

# Sample file to run [n8n automation](https://n8n.io/) with docker-compose

1. pull repo
2. create your .env
3. update nginx/my.conf, replacing "YOUR_DOMAIN" with your app domain
4. update init-letsencrypt.sh file with your domain and e-mail
5. run ./init-letsencrypt.sh
6. run `docker-compose up -d`
7. be happy :)
