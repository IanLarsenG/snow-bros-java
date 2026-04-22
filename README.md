#Snow Bros - Java Clone

Una recreación funcional del clásico arcade "Snow Bros", inspirada pero modificada, desarrollada íntegramente en Java. Este proyecto se enfoca en la aplicación de principios de ingeniería de software para gestionar la lógica de un videojuego 2D, desde la física de los personajes hasta la persistencia de datos. 

Este modelado tiene:
-2 Dominios de aplicacion deonde solo se modificacn los sprites.
-3 Modos de juego (Clasico, Contra reloj, Supervivencia).
-2 Niveles, compuestos por pisos
-9 Enemigos
-6 PowerUps
-2 Jefes (Cada uno al final de cada nivel).

#Características Principales

- *Mecánicas Clásicas:*Implementación de movimiento, salto, lanzamiento de nieve y colision de enemigos.
- *Sistema de Niveles:* Incluye un parseador de archivos a medida que permite cargar diferentes escenarios de forma dinámica.
- *Gestión de Puntuación:* Sistema de ranking funcional para registrar las mejores marcas de los jugadores.
- *Interfaz Gráfica:* GUI desarrollada para una experiencia retro.

#Desafíos Técnicos y Arquitectura

El desarrollo de este clon se centró en la creación de un motor de juego escalable y limpio, aplicando los siguientes conceptos:

- *Patrones de Diseño:* Uso de **Singleton** para la gestión de recursos globales y **Factory** para la creación dinámica de entidades y enemigos.
- *Programación Orientada a Objetos (OOP):* Estructura basada en herencia y polimorfismo para gestionar el comportamiento de los distintos tipos de entidades.
- *Multithreading:* Implementación de hilos para separar la lógica del **game loop** del renderizado de la interfaz, asegurando un rendimiento constante.
- *Lógica de Colisiones:* Desarrollo de un sistema de detección de colisiones preciso para las interacciones entre personajes y entorno.

#Tecnologías Utilizadas

- *Lenguaje:* Java 
- **Herramientas:** [Ej: IntelliJ IDEA / Eclipse]
- *Gestión de Versiones:* Git & GitHub

#Instalación y Uso

1. Clonar el repositorio:
   git clone [https://github.com/tu-usuario/snow-bros-java-clone.git](https://github.com/tu-usuario/snow-bros-java-clone.git)


Proyecto snow-bros desarrollado por: 

    ANGELES, JANO ISMAEL
    BOURNAUD, EMANUEL
    LARSEN, IAN
    TRUNINGER, JUSTO ULRICH SCOTT
    VAZZANO, FEDERICO NICOLÁS
=======