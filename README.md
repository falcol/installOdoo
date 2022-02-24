# installOdoo
# Docker: postgresql, odoo, pgadmin4

run
```bash
docker-compose up -d
```

# run postgresql in termianl
```bash
docker exec -it ID_CONTAINER_POSTGRES psql -U odoo -W postgres
```

# Connect with pgadmin4  
host: postgresql  
username: odoo  
password: myodoo  
