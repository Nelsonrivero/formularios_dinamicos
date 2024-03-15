# Sistema Dinámico de Formularios

Este es un proyecto desarrollado en Laravel que permite a los usuarios crear formularios de manera dinámica y almacenar su estructura en una base de datos.

## Comenzando

Sigue estas instrucciones para obtener una copia del proyecto en tu máquina local y comenzar a desarrollar.

### Prerrequisitos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu máquina:

- PHP
- Composer
- Node.js y npm

### Instalación

Sigue estos pasos para instalar el proyecto:

1. Instala las dependencias de PHP con Composer:

```bash
composer install
```

2. Instala las dependencias de Node.js:
```bash
npm install
```
3. Compila los assets para el frontend:
```bash
npm run dev
```
4. Copia el archivo de configuración .env.example y renómbralo a .env. Luego, genera una nueva clave de aplicación::
```bash
cp .env.example .env
php artisan key:generate
```
5.Configura tu base de datos en el archivo .env y ejecuta las migraciones para crear las tablas en la base de datos:
```bash
php artisan migrate
```
