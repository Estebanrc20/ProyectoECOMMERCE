Las instrucciones para pruebas son las siguientes:

http://localhost:5000/api/usuarios/registro --> Creacion usuario
http://localhost:5000/api/usuarios/iniciarsesion --> Iniciar con el usuario creado
http://localhost:5000/api/productos --> crear producto
http://localhost:5000/api/productos/6748e88461991de9e294c7d7 --> eliminar un producto especifico con el id
http://localhost:5000/api/usuarios/perfil --> consulta del id del usuario
http://localhost:5000/api/carrito/crear --> crear carrito
http://localhost:5000/api/carrito/actualizar --> actualizar carrito
http://localhost:5000/api/ordenes/5/crear --> crear orden con el id del usuario creado



Rutas de Usuario

    POST /api/usuarios/registro
    POST /api/usuarios/iniciarsesion
    GET /api/usuarios/perfil
    PUT /api/usuarios/perfil
Rutas de Productos

    POST /api/productos/
    GET /api/productos/
    GET /api/productos/:id
    PUT /api/productos/:id
    DELETE /api/productos/:id
Rutas de Categorías

    POST /api/categorias/
    GET /api/categorias/
    PUT /api/categorias/:id
    DELETE /api/categorias/:id

Rutas de Carrito

    POST /api/carrito/crear
    GET /api/carrito/:usuarioId
    PUT /api/carrito/actualizar
    DELETE /api/carrito/vaciar/:usuarioId

Rutas de Órdenes

    POST /api/ordenes/:usuarioId/crear
    GET /api/ordenes/:usuarioId/orden/:ordenId
    GET /api/ordenes/:usuarioId
