
# ⚽ Camp Barca
Camp Barca es una aplicación muy sencilla diseñada para demostrar cómo crear instancias de una clase en Java. Además, contiene información histórica sobre el **Fútbol Club Barcelona**, uno de los clubes de fútbol más exitosos del mundo.

## Descripción
El Fútbol Club Barcelona, comúnmente conocido como Barça, fue fundado en 1899 y tiene una rica historia en el mundo del fútbol. A lo largo de los años, el club ha ganado numerosos trofeos, incluyendo varias Ligas de Campeones de la UEFA y títulos de La Liga española.

La aplicación Camp Barca te permitirá crear instancias de jugadores de fútbol usando una clase en Java, mostrando así cómo se puede modelar un equipo de fútbol en un entorno de programación.


Esta aplicación contiene una clase llamada Jugador. Aquí tienes un ejemplo de cómo crear instancias de esta clase en Java:
```java
public class Jugador {
    String nombre;
    int edad;
    String posicion;

    public Jugador(String nombre, int edad, String posicion) {
        this.nombre = nombre;
        this.edad = edad;
        this.posicion = posicion;
    }

    public void mostrarInformacion() {
        System.out.println("Nombre: " + nombre);
        System.out.println("Edad: " + edad);
        System.out.println("Posición: " + posicion);
    }

    public static void main(String[] args) {
        Jugador messi = new Jugador("Lionel Messi", 36, "Delantero");
        Jugador iniesta = new Jugador("Andrés Iniesta", 39, "Mediocampista");

        messi.mostrarInformacion();
        iniesta.mostrarInformacion();
    }
}
```

En este ejemplo, se crean dos instancias de la clase Jugador: Lionel Messi y Andrés Iniesta, y se imprime su información en la consola.

## Características
- Sencillo de usar: Creación de instancias de clase en Java.
- Modular: Fácil de expandir con nuevos jugadores.
- Histórico: Relacionado con la rica historia del FC Barcelona.

### Historia del FC Barcelona
Fundado en 1899 por un grupo de jugadores de diferentes nacionalidades.
El Barça ha ganado más de **25 títulos de La Liga**.
Es conocido por su estilo de juego basado en la posesión y la filosofía del **"tiki-taka"**.
Ha sido el hogar de leyendas como [**Lionel Messi**](https://es.wikipedia.org/wiki/Lionel_Messi), [**Johan Cruyff**](https://es.wikipedia.org/wiki/Johan_Cruyff), y [**Xavi Hernández**](https://es.wikipedia.org/wiki/Xavi_Hern%C3%A1ndez).

Tareas Pendientes
 1. Agregar más jugadores históricos.
 2. Implementar una interfaz gráfica (GUI) para la aplicación.
 3. Añadir funcionalidad para gestionar estadísticas de los jugadores.
 4. Crear una base de datos de jugadores.

### Tabla de Jugadores Históricos
|Nombre	|Posición|
|-------|--------|
|Lionel Messi	|Delantero|
|Andrés Iniesta|	Mediocampista|
|Xavi Hernández|Mediocampista|
|Ronald Koeman|Defensa Central|



![¡Una vista del Camp Nou, estadio del FC Barcelona!](https://wallup.net/wp-content/uploads/2019/09/994280-camp-nou-estadio-fc-barcelona.jpg)


### Enlaces de Interés:
- [Página oficial del FC Barcelona](https://www.fcbarcelona.es/es/)
- [Historia del club en Wikipedia](https://es.wikipedia.org/wiki/F%C3%BAtbol_Club_Barcelona)
- [Perfil de Lamine Yamal en Transfermarkt](https://www.transfermarkt.es/lamine-yamal/profil/spieler/937958)


