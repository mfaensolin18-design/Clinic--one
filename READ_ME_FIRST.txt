CLINIC ONE - UPLOAD PACKAGE FOR INFINITYFREE

1. In InfinityFree: create a MySQL database. Write down the host, database name, username and password.
2. Open phpMyAdmin, select that database, click Import, and choose
   IMPORT_IN_phpMyAdmin/database_import.sql
3. Open UPLOAD_TO_htdocs/config.php in Notepad and replace:
     sqlXXX.infinityfree.com        -> your MySQL host
     if0_XXXXXXXX_clinic            -> your database name
     if0_XXXXXXXX                   -> your database username
     YOUR_DATABASE_PASSWORD         -> your database password
4. Upload everything INSIDE the UPLOAD_TO_htdocs folder into htdocs
   (Online File Manager or FileZilla). Delete the default index2.html there.
5. Open yourdomain/install.php once to create the demo users, then delete install.php.
6. Open yourdomain/duty.php (public page) and log in at yourdomain/login.php

Demo logins: staff / staff123, drsantos / doctor123, midwife / midwife123
Change these passwords and the sample GCash, Maya and bank numbers before real use.

The folder demo/ is a browser-only copy (open yourdomain/demo/). It does not share data between devices.
