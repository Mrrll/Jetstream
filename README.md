# Jetstream

<a name="top"></a>

## Indice de Contenidos.

- [Instalación](#item1)
- [Crear Avatar](#item2)
- [Términos y condiciones](#item3)

<a name="item1"></a>

## Instalación
###### Kit de inicio Jetstream en laravel

>Typee: en la Consola:
```console
composer require laravel/jetstream
```

>Typee: en la Consola:
```console
php artisan jetstream:install livewire
```

**`Nota :` `Livewire` trabaja mas como `Blade` y `inertia` trabaja mas como `Vue.js`.**

>Typee: en la Consola:
```console
npm install

npm run build
php artisan migrate
php artisan serve
```
[Subir](#top)

<a name="item2"></a>

## Crear Avatar

>Abrimos el archivo `jetstream.php` que esta en la carpeta `config\jetstream.php` y en `features` des-comentamos lo siguiente.

```php
Features::profilePhotos(),
```

>Abrimos el archivo `.env` que esta en la carpeta `/` y en `APP_URL`  lo cambiamos a lo siguiente.

```php
APP_URL=http://127.0.0.1:8000
```

>Y en `FILESYSTEM_DISK`  lo cambiamos a lo siguiente.

```php
FILESYSTEM_DISK=public
```

>Abrimos el archivo `jetstream.php` que esta en la carpeta `config\jetstream.php` y en `features` des-comentamos lo siguiente.

```php
Features::profilePhotos(),
```

<a name="item3"></a>

## Términos y condiciones

>Abrimos el archivo `jetstream.php` que esta en la carpeta `config\jetstream.php` y en `features` des-comentamos lo siguiente.

```php
Features::termsAndPrivacyPolicy(),
```

###### Editar términos y condiciones

>Abrimos el archivo `policy.md` que esta en la carpeta `resources\markdown\policy.md` y podemos editar las términos.

>Abrimos el archivo `terms.md` que esta en la carpeta `resources\markdown\terms.md` y podemos editar los  condiciones.

[Subir](#top)
