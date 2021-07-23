# **Delilah Restó**
API para pedidos de comida deliciosa. Como cliente, podrás registrarte, ver el listado de nuestros productos y realizar una orden. Los administradores del restaurante tienen la posibilidad de recibir pedidos y actualizaciones.

## **Comenzando**
A continuación encontrarás una serie pasos para ejecutar el proyecto en tu equipo.

### **Prerrequisitos**
Antes de comenzar con la instalación debes de contar con los siguientes requisitos:
- nodejs (Recomendado V16.4.1)
- npm (Recomendado V7.18.1)
- mySQL (Recomendado Ver 8.0.26)

### **Descarga e Instalación**
Una vez satisfechos todos los prerrequisitos, puedes comenzar con la instalación del proyecto.

- Primero clona el repositorio ejecutando el siguiente comando en la consola o terminal de tu preferencia:

    ```bash
    git clone https://github.com/Enaldo1709/DelilahResto.git
    ```

- Luego instala las dependencias necesarias para la ejecución del proyecto, para ello ejecuta el siguiente comando:
    ```bash
    cd DelilahResto/
    npm install
    ```

- Una vez instaladas las dependencias, es momento de preparar la base de datos, para ello ejecuta los siguientes comandos:
    - Primero creamos la base de datos:
    ```bash
    mysql -u <username> -p
    ```

    - Dentro de mysql shell ejecutamos:
    ```SQL
    CREATE DATABASE delilahresto;
    exit;
    ```

    - Luego desde la consola ejecutamos:
    ```bash
    mysql -u <username> -p delilahresto < delilahresto.sql
    ```

    Listo ya estará creada la base de datos con la estructura seleccionada.

Ejecuta el siguiente comando para iniciar el proyecto:
```bash
npm start
```

## **Construido con**
Delilah Restó está construido con las siguientes tecnologías:
- [**Express**](https://www.npmjs.com/package/express) - Framework de servidor WEB del proyecto.
- [**Swagger**](https://swagger.io/) - Herramienta utilizada para generar la documentación.

## **Autores**
Estos son los autores del proyecto:
- **Enaldo Narváez Yepes** - Desarrollador del proyecto - [Enaldo1709](https://github.com/Enaldo1709)

## **Licencia**
El proyecto está bajo la licencia **MIT**. Puedes leer [LICENSE](https://github.com/Enaldo1709/DelilahResto/blob/master/LICENSE) para mas información.

## **El proyecto Delilah Restó**
El proyecto Delilah Restó hace parte del Sprint 3 del curso de Desarrollo WEB Full Stack de Acámica, este proyecto es presentado por Enaldo Narváez Yepes como evidencia del curso Desarrollo WEB Full Stack de Acámica con Protalento.