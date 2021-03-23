#Configuración de PHP y APACHE2
Habilitar el modo rewrite de APACHE
Instalar apt-get install php-pgsql
Habilitar las extensiones de PGSQL PDO
En apache2.conf CAMBIAR el document root /var/www/ AllowOverride None -> a AllowOverride All

#Instalar Laravel 6.0
#Instalar composer
#Instalar node y npm

#Luego de clonar ir a /directorio_proyecto/ 
composer install 
npm install 
npm run dev

#Comando para solución a errores de npm
rm -rf node_modules
rm package-lock.json yarn.lock
npm cache clear --force
npm install

#Solución a error de fsevents
npm i fsevents@latest -f --save-optional