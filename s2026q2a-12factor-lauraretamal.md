### 1. Codebase (Código Base)
Tener el código del proyecto en un repositorio como Git permite mantenerlo organizado y llevar un registro de todos los cambios realizados. También facilita recuperar versiones anteriores, trabajar con diferentes ramas y mantener una estructura más clara durante el desarrollo.

### 2. Config (Configuración)
Es importante mantener separada la configuración del código de la aplicación. Datos como credenciales, URLs, claves de acceso o variables específicas de cada entorno pueden manejarse mediante variables de entorno. De esta forma, se puede utilizar el mismo código en desarrollo, pruebas o producción sin tener que modificarlo cada vez.

### 3. Backing Services (Servicios de apoyo)
Este factor es importante porque una aplicación puede depender de diferentes servicios externos, como bases de datos, almacenamiento, APIs o servicios de AWS. Al tratarlos como recursos independientes, resulta más sencillo cambiar, reemplazar o escalar alguno de estos servicios sin tener que modificar directamente la lógica principal de la aplicación.

### 4. Build, Release, Run (Construir, distribuir y ejecutar)
Separar estas tres etapas permite tener un proceso más organizado desde que se desarrolla el código hasta que la aplicación se ejecuta. Primero se construye la aplicación, después se prepara una versión específica para distribuir y finalmente se ejecuta en el entorno correspondiente. Esto facilita controlar las versiones y automatizar los despliegues mediante herramientas como Docker, GitHub Actions o servicios de la nube.
