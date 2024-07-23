Bibliotech

Es un proyecto realizado para un curso de Data Analytics en Coderhouse.
Simula una BD que podría tener una biblioteca virtual.
Consta de:
- 5 tablas de dimension ('dimlibros';'dimfecha';'dimlibros';'dimplanes';'dimusuarios'), que muestran los datos descriptivos de las entidades del negocio.
- La tabla de hechos('factventas') que muestra los datos cuantitativos del negocio.
- 2 tablas accionadas por un trigger que contienen los movimientos o updates de las tablas de ventas y libros respectivamente.('log_ventas';'movimientos_libros')
-5 vistas:
comprasusuarios: muestra las compras de cada usuario, mediante un join entre la tabla de ventas y de usuarios.
empleadosat: resume la tabla de dimempleados para que solo se muestren los empleados de atención al cliente.
gananciaplanes: hace una suma de todos los planes adquiridos agrupados por nombre.
planbronce: muestra solo los planes bronce.
planusuarios: muestra solo el nombre y plan de los usuarios.
- 2 Procedimientos almacenados:
Ordenar_campo: en base a 3 inputs se puede manipular el ordenamiento de una tabla.
Planes_Menores: Crea una tabla de todos los usuarios que posean planes "Plata" o "Bronce".

-2 Funciones:
Cuotas: Ubicando el precio del libro y las cuotas que se quieren pagar, se puede calcular el valor de la cuota mensual.
PlanLibro: Poniendo el precio del libro se puede ver con que plan puedes acceder a él.

Objetivos

Practicar la manipulación de datos y creación de tablas.
Comprender las distintas funcionalidades que la herramienta contiene y ver su aplicación.

Uso

Para usar el proyecto lo unico que tienes que hacer es tener MySQL descargado y copiar y pegar el codigo.
Una vez que lo hayas pegado, busca en el codigo todos las veces que figure 'tuUsuarios' y cambialo por tu usuario.

Agradecimientos

Gracias a Coderhouse y a todos los profesores y tutores que tuve, fueron gran apoyo para esta primera incursión en Data Analytics.

Autor

Nuñez, Facundo 

02-01-2022
