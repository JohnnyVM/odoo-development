# INSTALL GUIDE

Still no well tuned, but you control de odoo image with the .env file

### TODO
change database in function of the odoo version

odoo database is not initialized, you must initialized manually:
```
docker-compose exec --user odoo odoo odoo --no-http --stop-after-init -i base,website_sale --db_host db -w odoo -d odoo
```
