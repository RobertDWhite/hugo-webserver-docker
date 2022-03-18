# hugo-webserver-docker
A simple docker-compose for running a webserver in Docker for Hugo static-sites.
Everytime you run "hugo" to generate or re-generate your static-site, the public folder is updated. With this container, the changes are live immediately.

Download with cURL:
curl -LJO https://raw.githubusercontent.com/RobertDWhite/hugo-webserver-docker/main/docker-compose.ymlml

Download with wget:
wget --no-check-certificate --content-disposition https://raw.githubusercontent.com/RobertDWhite/hugo-webserver-docker/main/docker-compose.yml
