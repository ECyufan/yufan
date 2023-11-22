Be sure you copy the correct st_geometry library for the version of PostgreSQL and operating system you will be using. For example, for PostgreSQL 10 on Windows, please use the 10\Windows64\st_geometry.dll.
The location of the lib directory on Linux can vary depending on how you installed PostgreSQL. To determine the correct location for your PostgreSQL installation, execute pg_config as the postgres user. The value that is returned for PKGLIBDIR is the lib directory where you need to place the st_geometry library. Log in as the root user to copy the file to the lib location.
If PostgreSQL is installed on a Windows server, place the st_geometry.dll file in the %PostgreSQL%\lib directory.

If you have PostgreSQL installed on a Windows server, you must have the Microsoft Visual C++ 2017 Redistributable Package (x64) installed on the server. If it is not present on the PostgreSQL server, download it from the Microsoft site and install it.
