# Odoo

[Odoo](https://www.odoo.com/) (antes conocido como OpenERP) es un conjunto de aplicaciones empresariales de código abierto.

Este repositorio utiliza [la imagen oficial de Odoo en Docker Hub](https://hub.docker.com/_/odoo) y la complementa con un archivo `docker-compose-arm64v8.yml` para facilitar su uso en equipos con chip Apple M1 o M2.

## Soporte de arquitecturas

- Linux x86-64 (`docker-compose-amd64.yml`)
- ARMv8 (64 bits) - Apple M1/M2 (`docker-compose-arm64v8.yml`)
