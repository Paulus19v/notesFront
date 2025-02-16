# notesFront
# Aplicación CRUD de Notas

## Descripción
Esta aplicación permite gestionar notas de manera sencilla. Se pueden crear, leer, editar y eliminar notas. La aplicación se conecta a una base de datos externa mediante una API.

## Funcionalidades
- **Crear Notas**: Permite añadir nuevas notas con título y contenido.
- **Leer Notas**: Se pueden visualizar todas las notas guardadas.
- **Editar Notas**: Modificar notas existentes.
- **Eliminar Notas**: Borrar notas que ya no sean necesarias.

## Tecnologías Utilizadas

### Frontend
- **JavaScript**
- **Angular**
- **HTML**
- **CSS**
- **TypeScript**

## Arquitectura
La aplicación sigue una arquitectura cliente-servidor:
1. El **frontend** desarrollado en Angular consume la API para realizar operaciones CRUD.
2. El **backend** desarrollado en Flask gestiona la lógica de la aplicación y la conexión con la base de datos externa.
3. La **base de datos** almacena las notas y responde a las solicitudes del backend.

## API
La API expone endpoints REST para interactuar con la base de datos:
- `GET /notes`: Obtiene todas las notas.
- `POST /notes`: Crea una nueva nota.
- `PUT /notes/{id}`: Edita una nota específica.
- `DELETE /notes/{id}`: Elimina una nota específica.

## Instalación y Ejecución
1. Clonar el repositorio.
2. Instalar dependencias tanto en el frontend como en el backend.
3. Configurar la conexión a la base de datos.
4. Ejecutar el backend con Flask.
5. Levantar el frontend con Angular.

## Próximos Pasos
- Implementar autenticación de usuarios.
- Agregar categorías a las notas.
- Mejorar la interfaz de usuario con estilos avanzados.
