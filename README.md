
# Docker Compose examples for Nginx Reverse Proxy with Letsencrypt

This repo based on : 
-   nginx-proxy  [@jwilder](https://github.com/jwilder/nginx-proxy)
-   docker-letsencrypt-nginx-proxy-companion  [@JrCs](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion)

Test it with :

    $ docker-compose -f docker-compose-whoami-example.yml up -d

Wait around 30 seconds...

    $ curl -k https://some-sexy-domain-with-ssl.com
    I'm b71e6948f036



