# 1DAM-Cafeinomanos
1ºDAM , Prácticas presencial 31/01/2025


📌 Tablas y su propósito
Tabla	Descripción
Instalaciones	Representa los espacios deportivos disponibles (gimnasio, piscina, etc.).
Usuarios	Almacena la información de los clientes o usuarios que hacen reservas.
Reservas	Guarda las reservas que los usuarios hacen en las instalaciones.
Actividades	Contiene las clases o actividades disponibles (Yoga, Pádel, Fútbol, etc.).
Entrenadores	Almacena los datos de los entrenadores que imparten actividades.
Imparten	Relaciona entrenadores con actividades que imparten.


🔗 Relaciones entre las tablas
Un usuario puede hacer muchas reservas → Relación entre Usuarios y Reservas.
Una reserva pertenece a una instalación → Relación entre Reservas e Instalaciones.
Un entrenador puede impartir varias actividades → Relación muchos a muchos entre Entrenadores y Actividades (gestionada por la tabla Imparten).


🔄 Ejemplo de cómo interactúa la base de datos
1️⃣ Un usuario se registra en el sistema.
2️⃣ El usuario reserva una instalación en una fecha y hora específica.
3️⃣ Puede también inscribirse en una actividad (ej. Fútbol, Yoga).
4️⃣ Los entrenadores imparten actividades según su especialidad.

