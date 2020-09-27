# INSTALL GUIDE

### TODO
change database in function of the odoo version

odoo database is not initialized, you must initialized manually:
```
docker-compose exec --user odoo odoo odoo --no-http --stop-after-init -i base,website_sale --db_host db -w odoo -d odoo
```
