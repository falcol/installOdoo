# installOdoo
# Docker: postgresql, odoo, pgadmin4

## FIRST
change info in docker-compose

## run
```bash
docker-compose up -d
```

## run postgresql in termianl
```bash
docker exec -it ID_CONTAINER_POSTGRES psql -U odoo -W postgres
```

# pass permisson deny
## username is your computer name
```bash
sudo chown -R username:username addons
```

## Connect with pgadmin4  
host: postgresql  
username: odoo  
password: myodoo  
