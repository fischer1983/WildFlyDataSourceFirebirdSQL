# WildFly with DataSource FirebirdSQL
Settings required to create a datasource that connects to the database FirebirdSQL

In standalone / configuration folder, paste the standalone-full.xml file. You need to modify the settings for database connection. Check the datasource tag.


In the \ modules \ system \ layer \ base \ org create the following folder structure:

-- firebirdsql
    -- main
    
Inside this folder place the jdbc driver file for Firebird (Jaybird) and Module.xml file, that contains the driver file name and other settings required.

This setup was held at WildFly 8.1.0 Final Windows Operating System 7, 8 and 10.
