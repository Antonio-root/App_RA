# App_RA
A web application that we develop as a University Project

Aqui se hara la aplicacion para el RA de 4to tetramestre


Frontend (Angular)
src/app:
    components: Contiene los componentes de Angular.
        example-component:
        example-component.component.ts: Lógica del componente.
        example-component.component.html: Plantilla del componente.
        example-component.component.css: Estilos del componente.
    services: Contiene los servicios de Angular para interactuar con la API.
        example.service.ts: Servicio para manejar las solicitudes HTTP.
    app.module.ts: Módulo principal de la aplicación.
    app-routing.module.ts: Configuración de las rutas de la aplicación.

    
Backend (PHP)
app:

    controllers: Contiene los controladores que manejan las solicitudes HTTP.
        ExampleController.php: Controlador para manejar las solicitudes relacionadas con "example".
    models: Contiene los modelos que representan la lógica de negocio.
        ExampleModel.php: Modelo para manejar los datos de "example".
    views: Contiene las vistas que se devuelven al cliente.
        example-view.php: Vista para mostrar los datos de "example".
    public:
        index.php: Punto de entrada de la aplicación PHP.
        assets: Contiene archivos estáticos como imágenes, CSS, y JavaScript.
    config:
        database.php: Configuración de la base de datos.



        
##Reparticion de tareas 

ANTONIO.
    Frontend (Angular)
    Configuración Inicial:
        Configurar el proyecto Angular.
        Integrar Bootstrap para el diseño responsivo.

    Módulo de Autenticación y Seguridad:
        Implementar las páginas de registro y login.
        Integrar la autenticación con redes sociales (Google, Facebook).
        Crear la página de recuperación y restablecimiento de contraseña.

    Módulo de Redes Sociales:
        Desarrollar los perfiles de usuario con foto y publicaciones.
        Implementar la creación, edición y eliminación de publicaciones.
        Añadir funcionalidades de comentarios y likes en publicaciones.
    
    

    Backend (PHP)
    Módulo de Autenticación y Seguridad:
        Implementar el registro y login de usuarios.
        Configurar la autenticación con redes sociales (Google, Facebook).
        Desarrollar la funcionalidad de recuperación y restablecimiento de contraseña.
        Gestionar roles y permisos de usuarios.

    Módulo de Redes Sociales:
        Desarrollar la API para los perfiles de usuario y publicaciones.
        Implementar la API para comentarios y likes en publicaciones.



YERALDO:
    Frontend (Angular)

    Módulo de E-commerce:
        Desarrollar el catálogo de productos con filtros y búsqueda avanzada.
        Crear las páginas de detalles del producto.
        Implementar el carrito de compras.

    Módulo de E-commerce:
        Implementar el sistema de calificación y reseñas de productos.


    Backend (PHP)

    Configuración Inicial:
        Configurar el servidor PHP y la base de datos MongoDB.
        Crear la estructura de la API REST.

    Módulo de E-commerce:
        Crear la API para el catálogo de productos.
        Desarrollar la API para las páginas de detalles del producto.
        Implementar la API para el carrito de compras y métodos de pago (PayPal).
        Gestionar pedidos y seguimiento.
