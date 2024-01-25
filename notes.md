GitHub is useful for saving work and seeing changes, if your computer dies the work is still in GitHub! Commit often!!!
## Notes
- IP 18.207.56.180
- made elastic so that it has the same IP address and doesn't change
- Command to remote shell into server: ssh -i [key pair file] ubuntu@[ip address]
- keep pair secret, keep pair safe
- brings you to console window for the web server you just launched and in ubuntu user's home directory

- the * can be put in the subdomain so that anything.yourdomain will bring up your website
- domain name journey2paradise.click
**Caddy**
-   handles all creation and rotation web certificates, allows easy set up HTTPS
-   serves up all your HTML, CSS, JavaScript files, all early application work hosted on static files
-   acts as gateway for subdomain requests to your Simon and startup application services - when request made to simon.yourdomain Caddy will proxy the request to the Simon application running with node.js as an internal web service
