# ppr-biblioteca-db-script

Este repositorio contiene el script de la base de datos para el proyecto **ppr-apibiblioteca**. Este script está diseñado para inicializar la base de datos con la estructura necesaria y, en algunos casos, cargar datos de ejemplo.

> [!NOTE]
> **PPR:** Este proyecto es de carácter personal y se ha creado con el propósito de práctica y aprendizaje. La abreviatura "PPR" se refiere a "Proyecto Personal de Práctica".

## Contenido

- `schema.sql`: Este archivo contiene la estructura de la base de datos, incluyendo tablas, índices y relaciones necesarias.

- `data.sql`: En caso de que se proporcionen datos de ejemplo, este archivo contiene instrucciones para cargar datos iniciales en la base de datos.

> [!IMPORTANT]
> Al ejecutar el archivo `data.sql`, ten en cuenta lo siguiente.

## Contraseñas de Usuarios Generadas

### Usuario Administrador

- **Email de usuario:** admin@admin.com
- **Contraseña Predeterminada:** admin

### Usuario Personal

- **Email de usuario:** personal@personal.com
- **Contraseña Predeterminada:** personal

### Usuario Normal

- **Email de usuario:** usuario@usuario.com
- **Contraseña Predeterminada:** usuario

## Instrucciones

Para utilizar este script, sigue los pasos a continuación:

1. **Estructura de la Base de Datos:**

   - Ejecuta el siguiente comando para crear la estructura inicial de la base de datos.
     ```shell
     mysql -u tu_usuario -p nombre_de_bd < schema.sql
     ```
     Asegúrate de reemplazar `tu_usuario`, `nombre_de_bd` con los valores adecuados.

2. **Cargar Datos de Ejemplo (Opcional):**
   - Si se proporciona un archivo `data.sql` y deseas cargar datos de ejemplo, ejecuta el siguiente comando.
     ```shell
     mysql -u tu_usuario -p nombre_de_bd < data.sql
     ```
     Asegúrate de reemplazar `tu_usuario`, `nombre_de_bd` con los valores adecuados.

Ten en cuenta que este script puede requerir variables de entorno específicas definidas en el proyecto principal (`ppr-apibiblioteca`). Consulta el README del proyecto principal para obtener más información sobre la configuración de variables de entorno.
