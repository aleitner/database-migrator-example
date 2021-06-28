# Example Database Migration

## Dependencies

* Docker

## Makefile

* download-postgres - Download latest postgres image
* postgres - Run postgres container
* createdb - Create db on postgres container
* dropdb - Drop db from postgres container
* migrateup - Run db migrations
* migratedown - Undo db migrations
