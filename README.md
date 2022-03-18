# hugo-webserver-docker
A simple docker-compose for running a webserver in Docker for Hugo static-sites.
Everytime you run "hugo" to generate or re-generate your static-site, the public folder is updated. With this container, the changes are live immediately.

Download with cURL:
curl -LJO https://github.com/RobertDWhite/hugo-webserver-docker/main/docker-compose.yml

Download with wget:
wget --no-check-certificate --content-disposition https://github.com/RobertDWhite/hugo-webserver-docker/main/docker-compose.yml
