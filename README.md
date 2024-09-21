Arkanoid Ricky y la Fábrica de chocolates
¡Bienvenido a Arkanoid de Ricardo Fort! Un juego clásico inspirado en el famoso Arkanoid, desarrollado en C++ utilizando la librería SFML, con un toque humorístico y divertido gracias a las imágenes y sonidos alegóricos de un popular personaje de la televisión argentina.

Características
Gráficos 2D: Implementados con la librería SFML para ofrecer una experiencia visual retro y nostálgica.
Imágenes cómicas: Las imágenes que rememoran la fábrica del mítico Willy Wonka si viviera en la Argentina.
Música y efectos sonoros: Sonidos cómicos y divertidos para amenizar la partida.
Control fluido: Mueve tu plataforma con facilidad y mantén la pelota en juego.
Requisitos del sistema
Sistema operativo: Windows, Linux o macOS
Compilador compatible con C++11 o superior
Librería SFML (versión 2.5 o superior)
Instalación
Clona el repositorio:

bash
Copy code
git clone https://github.com/tu_usuario/arkanoid-comico.git
Instala las dependencias: Asegúrate de tener la librería SFML instalada en tu sistema. En Ubuntu, por ejemplo, puedes instalarla con el siguiente comando:

bash
Copy code
sudo apt-get install libsfml-dev
En otros sistemas operativos, sigue las instrucciones de instalación correspondientes a SFML desde su documentación oficial.

Compilación:

bash
Copy code
cd arkanoid-comico
g++ -std=c++11 -o arkanoid main.cpp -lsfml-graphics -lsfml-window -lsfml-system
Ejecución:

bash
Copy code
./arkanoid
Cómo jugar
Usa las flechas izquierda y derecha para mover la plataforma.
Tu objetivo es romper todos los bloques con la pelota sin dejar que caiga.
A medida que avanzas, verás divertidas imágenes y sonidos del personaje de la televisión argentina que te motivarán (¡o te harán reír!) mientras juegas.
Controles
Flecha Izquierda: Mueve la plataforma a la izquierda.
Flecha Derecha: Mueve la plataforma a la derecha.
Espacio: Inicia el juego.
Contribuciones
Si deseas contribuir al proyecto, siéntete libre de hacer un fork, crear una nueva rama y enviar un pull request.

Haz un fork del proyecto.
Crea una nueva rama (git checkout -b mi-nueva-funcionalidad).
Realiza tus modificaciones y haz commit (git commit -am 'Añadí una nueva funcionalidad').
Sube los cambios (git push origin mi-nueva-funcionalidad).
Abre un Pull Request.