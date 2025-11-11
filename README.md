# Tarea 11_SXE

## Paso 1

Primero entramos a Intellij y creamos nuestro ```docker-compose.yml``` donde meteremos todos los parametros necesarios para la instalacion de nuestro proyecto.

<img width="471" height="544" alt="image" src="https://github.com/user-attachments/assets/91470394-efc0-4bf8-8d6c-f75e1b9e5dff" />
<img width="541" height="418" alt="image" src="https://github.com/user-attachments/assets/2332473f-ac22-44b8-a346-c26224610db9" />


## Paso 2

Abrimos la terminal y escribimos ```docker compose up``` para que corra (en caso de presentar algun fallo usar el comando ```docker compose down -v``` para borrar todo y volver a levantarlo)

<img width="949" height="261" alt="image" src="https://github.com/user-attachments/assets/993a966c-21a1-47c8-964d-fac6d714364f" />


## Paso 3

Comprobamos que esta todo funcionando correctamente y entramos a http://localhost:8081/ y a http://localhost:8069/ y deberia de salir asi

<img width="1093" height="905" alt="Captura de pantalla 2025-11-10 145335" src="https://github.com/user-attachments/assets/edf75e3e-2676-4349-96bc-30607a621d25" />
<img width="1261" height="502" alt="Captura de pantalla 2025-11-10 145304" src="https://github.com/user-attachments/assets/7244d6f5-ae6a-4587-80f0-5d78452d8b28" />


### Extensiones Instaladas

| Plugin | Descripción / Funcionalidad |
|---------|-----------------------------|
| **Docker** | Facilita la administración de contenedores y sus imágenes directamente desde el entorno de desarrollo |
| **.env Files** | Mejora la lectura y edición de archivos `.env`, destacando la sintaxis y permitiendo un manejo más claro de las variables de entorno |


### Configuracion Odoo

<img width="965" height="903" alt="image" src="https://github.com/user-attachments/assets/0f966187-06d0-4cf3-8d64-dfbf17a97d89" />

Despues de loguearte deberia salirte esta pestaña

<img width="1904" height="905" alt="image" src="https://github.com/user-attachments/assets/89f32693-c467-4124-83ea-489517219c78" />

En PgAdmin abrimos sesion y este es lo que deberiamos ver, con nuestro server corriendo

<img width="1913" height="649" alt="image" src="https://github.com/user-attachments/assets/ec91fd44-0a75-4c86-81e8-9d89fcff523f" />


Luego dentro de Odoo > Ventas descargamos esto
<img width="342" height="129" alt="image" src="https://github.com/user-attachments/assets/4862ca7a-94cb-4e41-bf58-bf0cfa7b1546" />

y luego de hacerlo deberiamos de ver algo asi

<img width="1902" height="724" alt="image" src="https://github.com/user-attachments/assets/482eda43-e262-4004-a07b-9ddb5b716986" />

