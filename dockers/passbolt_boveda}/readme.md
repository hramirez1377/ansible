## Crear un usuario para iniciar login
docker exec passbolt su -m -c "bin/cake passbolt register_user -u hernan.ramirez@smartqs.com -f Hernan -l Ramirez -r admin" -s /bin/sh www-data