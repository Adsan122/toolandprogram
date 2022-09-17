# Error mysql

Error en la version descargada no se encuentra la carpeta `mysql/data/`.
"Failed `inicializing data`"

## Solucion

<p>
En la carpeta bin de mysql que hayas descargado abre el CMD como admintrador</p>

- `cd C:\laragon\bin\mysql\mariadb-10.4.24-winx64\bin`.
- El CMD debe estar como ***administrator*** y escribe el siguiente comando.
		- `net start mysql` o `net start mysqld`
- Verifica con `mysql -u root -p` En la consola y listo **ha sido creado**.
- Cierra con `exit` para cerrar el servicio y poder abrirlo en "laragon".
