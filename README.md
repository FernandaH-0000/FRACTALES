# Fractal Tree

## Descripción

El Árbol Fractal es una estructura generada mediante recursión en la que cada rama produce dos nuevas subramas de menor tamaño. A medida que aumenta la profundidad de recursión, el patrón se vuelve más complejo y se asemeja a la ramificación natural de un árbol.

## Funcionamiento

La función dibuja una rama principal y, posteriormente, genera dos subramas mediante llamadas recursivas: una hacia la izquierda y otra hacia la derecha. Después de dibujar ambas ramas, la tortuga recupera su orientación y posición originales para continuar construyendo correctamente el resto de la estructura. El proceso se repite hasta alcanzar el caso base, momento en el que finaliza la recursión.

---

# Lévy C Curve

## Descripción

La Curva de Lévy C es un fractal generado mediante la subdivisión recursiva de segmentos rectos. Cada segmento se reemplaza por dos segmentos más pequeños unidos por un ángulo, produciendo una figura cada vez más detallada.

## Formación de la curva

En cada nivel de recursión, la tortuga gira 45° a la izquierda y dibuja la primera mitad de la curva. Luego gira 90° a la derecha para dibujar la segunda mitad. La combinación de ambos segmentos genera la característica forma fractal de la Curva de Lévy C.

## Funcionamiento

El algoritmo transforma cada segmento recto en dos segmentos más pequeños cuya longitud se reduce por un factor de √2. Este proceso se repite recursivamente hasta alcanzar el caso base. Gracias a las subdivisiones sucesivas y a los cambios de dirección, se obtiene la estructura fractal conocida como Curva de Lévy C.
