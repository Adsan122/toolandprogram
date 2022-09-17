# Instalar Mysql en laragon

## ir a la pagina https://mariadb.org/download para descargar mysql
<p>Alli eligiras la version de mysql, el sistema operativo, la arquitectura y el tipo de paquete preferiblemente "zip".</p>

##### para tener en cuenta
- No elijas las versiones que digan "Alpha","Beta" o "RC" ya que no son versiones estables .
- cada version que elijas te fijes asegurate que los cambies a siempre a zip.
- <em>Un "archivo.zip"</em> de 300mb puede tener un tamaño de 2Gb despues de descomprimir.


## Ejemplo:
mariadb 10.4.24 https://mariadb.org/download/?t=mariadb&o=true&p=mariadb&r=10.4.24&os=windows&cpu=x86_64&pkg=zip

|Opciones| Eleccion  |
| ------------ | ------------ |
|MariaDB Server Version|MariaDB Server 10.4.24|
|Operating System|Windows|
|Architecture| X86_64|
|Package Type |zip

| Release date: 2022-02-14 |
| File name: mariadb-10.4.24-winx64.zip |
| File size: 69.3 MB |

## Instalar la versión en laragon

**Despues de haber descomprimido el "archivo mariadb.zip" que se descargó**
- Lo movemos a la carpeta laragon en: `laragon\bin\mysql\mysqldescargado`
 ***¡Puedes descargar las vesiones que quieras en la carpeta mysql!***
