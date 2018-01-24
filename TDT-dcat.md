# steps


> __recovery protection__
> Before doing these steps ensure you have a backup of the mysql database of the datatank instance.

1. login in the datatank
2. ```
    cd /app/tdt-core
    php artisan
   ```
3. reseed the datatank
   ```
   php artisan datatank:licenses
   ```
4. 


## patch the license seeder


## create license file
The licenses to support have to be supplied as a json-ld file.

Validate the syntax with the https://json-ld.org playground.

