# Install-Odoo
Script que instala el ERP-CRM Odoo v15 facilmente.

El script realiza las siguientes acciones :
  - Instala las dependencias ( incluida dependencia para generar PDFs ).
  - Crea un usuario dentro del sistema llamado "odoo" junto con un grupo del mismo nombre.
  - Crea un usuario en la base de datos de postgres.
  - Crea la configuracion de Odoo.
  
El script inicia por defecto el servicio una vez su instalacion este completada.


## Instalacion

El primer paso evidentemente es la clonación del repositorio.
```sh
git clone https://github.com/Jibuza/Install-Odoo
cd Install-Odoo
```

Después de clonarse es necesario acceder al repositorio que tenemos en local y otorgarle los permisos necesarios al script para que pueda ejecutarse correctamente, posteriormente podremos ejecutar el script conformé aparece un poco más abajo.
```sh
sudo chmod u+x odooInstaller.sh
sudo sh odooInstaller.sh
```

## verificacion de estado

Si queremos verificar el estado del servicio, simplemente tenemos que copiar el siguiente comando:
```sh
service odoo status
```
