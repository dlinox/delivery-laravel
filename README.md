# delivery_admin-v1.1

## Requisitos previos
Tener instalado composer

PHP >= 7.2.5

## Instalamos el cliente de laravel de manera global con composer desde la consola o powershell:
```
composer global require laravel/installer
```


## el repositorio se debe de clonar en la direccion  C:/laragon/www (o del gestor que se use)
## Instalamos las dependecias
```
npm install
```
## Crear una base de datos con el nombre de: 
### delivery_db
## Configuracion del gestor de base de datos (user:root | password:'') 
## si la configuracion fuese diferente cambiarlo en el ".env"

## migramos la base de datos con: 
```
php artisan migrate
```

## Para poder usar los componestes de Vuejs (opcional)
```
npm run watch
```
