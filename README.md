# Android-Assignment-11.1

1. A helper class allows database management, creation, and version management. This is the class where we will create all the tables, and upgrade tables.
2. On Upgrade is basically for handling new db changes (could be new columns addition, table addition) for any new version of your app.
3. Use table layout with cursor. Showing database information will be better suited with table layout. Since table layout is not an adapter view, you can't use cursor adapter with it. So use table layout with cursor to show database table information.
