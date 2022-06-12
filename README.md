# Lego-maze-solver
W ramach projektu zbudowano robota mobilnego typu maze solver z Lego Mindstorms NXT 2.0, którego celem było znalezienie i pokonanie najkrótszej trasy
w labiryncie.
Oprogramowanie robota napisano w dedykowanym do tej platformy środowisku ROBOTC w języku NXC (uproszczona wersją języka C).
Bazą programu był kontroler wcześniej napisany i przetestowany w środowisku symulacyjnym Webots, 
co miało na celu pokazanie możliwości efektywnego testowania i prototypowania oprogramowania z użyciem symulacji.

Główną różnicą względem pierwowzoru było dodanie regulatora PI do kontrolowania pozycji robota względem ścian.

Zamodelowano labirynt 6x6 komórek z celem w postaci 4 komórek w centrum.
Do znalezienia najkrótszej trasy w dziedzinie odległości wykorzystano algorytm zalewania wodą (floodfill).

Model robota posiada 2 koła napędowe oraz 1 koło nastawne w postaci stalowej kulki.
Do mierzenia odległości wykorzystano 3 czujniki ultradźwiękowe.
