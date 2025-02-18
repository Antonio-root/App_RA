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