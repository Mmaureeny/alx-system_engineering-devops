# 0x10. HTTPS SSL

Configure your domain zone so that the subdomain www points to your load-balancer IP (lb-01)

Create a certificate using certbot and configure HAproxy to accept encrypted traffic for your subdomain www.


 Configure HAproxy to automatically redirect HTTP traffic to HTTPS.
