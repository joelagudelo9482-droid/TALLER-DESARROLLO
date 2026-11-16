# TALLER-DESARROLLO
El Sistema de Inventario de Videojuegos es una aplicación desarrollada en Python que permite administrar un inventario de videojuegos mediante un menú interactivo en consola.
El sistema utiliza SQLite para almacenar la información de manera permanente y aplica el patrón DAO (Data Access Object) para separar las operaciones de acceso a datos de la lógica del negocio.
Su objetivo es facilitar el registro, consulta, actualización, eliminación y control de ventas de videojuegos.

<img width="388" height="328" alt="image" src="https://github.com/user-attachments/assets/5aab4323-0b7f-4b0c-9945-1e69e1405424" />

<img width="599" height="321" alt="WhatsApp Image 2026-11-16 at 6 10 55 PM" src="https://github.com/user-attachments/assets/094395ec-0ca9-46df-ba08-9aced0db60e6" />

 Funcionalidades implementadas

El sistema cuenta con las siguientes opciones:

Registrar videojuego: permite ingresar el nombre, precio y cantidad disponible.

Mostrar inventario: presenta todos los videojuegos registrados con su ID, nombre, precio y stock.

Buscar videojuego: permite consultar un videojuego mediante su identificador.

Actualizar videojuego: permite modificar el nombre, precio y stock de un producto existente.

Eliminar videojuego: elimina un videojuego del inventario utilizando su ID.

Vender unidades: descuenta del inventario la cantidad de unidades vendidas, siempre que exista stock suficiente.

Salir: finaliza correctamente la aplicación.

Validaciones implementadas

Para garantizar el correcto funcionamiento del sistema, se implementaron las siguientes validaciones:

No permite registrar nombres vacíos.

No acepta precios menores o iguales a cero.

No permite cantidades de inventario negativas.

No permite realizar ventas con cantidades menores o iguales a cero.

Evita vender más unidades de las disponibles.

Informa cuando se consulta un ID inexistente.

Controla las entradas incorrectas para evitar que el programa se cierre inesperadamente.

 Tecnologías utilizadas

Python: lenguaje de programación utilizado para desarrollar la aplicación.

SQLite: sistema de gestión de bases de datos para almacenar los videojuegos.

Git y GitHub: herramientas utilizadas para el control de versiones y publicación del proyecto.
