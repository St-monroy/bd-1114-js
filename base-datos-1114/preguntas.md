1. ¿Que pasa con este codigo si necesito 5 filtros? Y si necesito 10?

R/ SQLite no tiene problema con tener 5, 10 o más filtros. Lo importante es que la cantidad de ? coincida con la cantidad de valores 
  que pasas al ejecutar all() o get().


2. Si cierro el programa, donde quedaron los datos?

R/ Los datos quedan guardados en el archivo escuela.db, por lo que aunque cierres el programa, la información no se pierde y estará disponible cuando vuelvas a abrir la base de datos; sin embargo, tu código actual vuelve a insertar los mismos alumnos cada vez que lo ejecutas, así que puede generar duplicados.


3. Que alumnos se inscribieron a "Base de Datos"?

R/ Son 0, porque la tabla inscripciones está vacía.


4. Cuantos cursos tiene cada alumno?

R/ No se puede saber cuántos cursos tiene cada alumno, porque la tabla inscripciones está creada pero no tiene ninguna inscripción registrada. Por ahora, cada alumno tiene 0 cursos.







