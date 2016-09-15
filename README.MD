Zabbix Db Postgres
------------------

This is a gcavalcante8808/zabbix-db-postgres image with with Zabbix Database Creation Scripts (schema, image and data) imported, based on postgres docker official image.

Build the Image
---------------

```docker build -t gcavalcante8808/zabbix-db-postgres . ```

If you want to build the image with a specific version of Zabbix (3.2.0 in the sample), you can do the following:

``` docker bulid --build-arg ZBX_VERSIOn=3.2.0 -t gcavalcante8808/zabbix-db-postgres . ```

Usage
-----

The image is based on the postgres official, refer to its the documentation, which is avaiable at:

https://hub.docker.com/_/postgres/

Author
------

Author: Gabriel Abdalla Cavalcante Silva (gabriel.cavalcante88@gmail.com)
