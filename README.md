# Tarea_Unidad_2
Este proyecto es una práctica de Programación Orientada a Objetos en Java. Modela contenidos audiovisuales (películas, documentales y series) para mostrar cómo usar herencia, encapsulación y polimorfismo. Sirve para crear objetos, añadir miembros (actores, investigadores, temporadas) y ver sus detalles desde la clase de prueba.
## Clases y funcionalidades añadidas
ContenidoAudiovisual — clase base con id autoincremental, título, duración y género. 

Pelicula — contiene estudio y lista de Actor. Método para añadir actores: agregarActores(Actor).

Documental — contiene tema y lista de Investigador. Método de conveniencia: agregarInvestigadores(String nombre) (crea e añade el investigador).

SerieDeTV — controla temporadas y permite agregarTemporada(int).

Clases auxiliares — Actor, Investigador, Temporada.
## Cómo clonar

En la terminal de git pega este comando:

git clone https://github.com/Joniel-Ortiz/poo_unidad1.git