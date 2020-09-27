# INSTALL GUIDE

odoo database is not initialized, you must initialized manually:
```
docker-compose exec --user odoo odoo odoo --no-http --stop-after-init -i base --db_host db -w odoo -d odoo
```
