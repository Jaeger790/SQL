# SQL Labs

Database coursework and saved SQL scripts. SQL Server deployment files and PostgreSQL reporting work are kept separately.

## Browse

- `CoffeeDatabase/C170PA.sqlproj`: original SQL Server SSDT project. It currently contains no schema build items.
- `CoffeeDatabase/scripts/sqlserver/`: preserved generated SQLCMD deployment scripts.
- `CoffeeDatabase/scripts/postgresql/rental_reports.sql`: PostgreSQL reporting exercise using the rental, inventory and film tables.

## Run

Review each script before execution and use a disposable lab database. `Coffee_Create.sql` drops and recreates its target database. The PostgreSQL exercise requires an existing rental sample schema; it cannot run against the SQL Server project.

## Maintenance

SQL files have been moved out of `bin/Debug` so they are not mixed with build output. IDE caches, compiled assemblies and local project settings are removed. The preserved scripts are historical exercises; this organization pass does not establish that they execute correctly on a fresh database.
## Related projects

See the [project index](https://github.com/Jaeger790#projects) for the rest of my work.
