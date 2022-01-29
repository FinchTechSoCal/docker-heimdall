# docker-heimdall

### Install Instructions
```bash
git clone git@github.com:FinchTechSoCal/docker-heimdall.git ~/docker-files/heimdall
cd  ~/docker-files/heimdall
mkdir ~/appdata/heimdall

ln -s /home/finchtech/docker-files/env/ft-cloud-1.prod.env /home/finchtech/docker-files/heimdall/.env

docker-compose up -d
```