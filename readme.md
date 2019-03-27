# AJAX CRUD para Laravel 5.7

## Instalacion

Clona el repositorio
```
git clone https://github.com/GranPapiVAINGLORY/Crud-para-las-Rutas.git
```

Dirigete a la carpeta que has clonado e instala las dependecias:
```
cd ajax-crud
composer install
```

Crea o adapta ya a tus base de datos:
```
php artisan make:migration (el nombre que le daras a tu base)
php artisan migrate (si es que ya la tienes y en el archivo .env configura tus credenciales)
```

Te recomiendo generar una llave
```
php artisan key:generate
```

Abrelo con el navegador que estas trabajando el proyecto, yo use la edicion developer de Firefox es mas completa

## Funciones
1. Crear nuevo post
2. Mostrar detalles de un post
3. Editar un post
4. Eliminar un post
5. Marcar un post como publicado/no publicado
