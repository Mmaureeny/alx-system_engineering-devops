0.Block all incoming traffic but
Configure ufw so that it blocks all incoming traffic, except the following TCP ports:
22 (SSH)
443 (HTTPS SSL)
80 (HTTP)
1.Port forwarding
Configure web-01 so that its firewall redirects port 8080/TCP to port 80/TCP.
Your answer file should be a copy of the ufw configuration file that you modified to make this happen
