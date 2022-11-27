# AzureObjCounter-S
## Cel
Celem projektu jest ułatwienie ludziom liczenia owoców i warzyw na zdjęciach. Nasz projekt może mieć zastosowanie podczas zbiorów warzyw lub owoców z pól uprawnych i sadów, potrzebujemy oszacować liczbę zbiorów w krótkim czasie.
## Opis projektu
Użytkownik może zamieścić wybrane zdjęcie z wybranymi owocami lub warzywami na naszej stronie internetowej, która przekaże to zdjęcie do bloba. Stamtąd jest ona przekazywana do wytrenowanego modelu Custom Vision, następnie wynik jest przekazywany spowrotem na stronę, prosto do użytkownika.
## Schemat działania naszego rozwiązania

## Diagram architektury
![316431571_508896637964841_6962589888494709220_n](https://user-images.githubusercontent.com/73585472/204158222-f5066195-ce66-4457-a8c2-8f614bc4851e.png)

## Opis wybranych serwisów
### WebApp Service 
Oparta na chmurze platforma służąca do hostowania stron internetowych, zezwalająca na stworzenie API dzięki któremu mogliśmy przesyłać zdjęcia między Azure Blob Storage a wytrenowanym modelem Custom Vision
### Azure Blob Storage 
Przechowuje obiekty, z których w prosty sposób można korzystać w chmurze - stworzony głównie pod ogromne ilości nieustrukturyzowanych danych takich jak zdjęcia, które są nieodłączną częścią naszego projektu.
### Custom Vision 
Pozwala na wytrenowanie modelu do wykrywania wybranych obiektów na zdjęciach, udostępnia API aby móc w łatwy sposób odebrać wymagane wyniki.

## Zespół
Jakub Urbański https://github.com/urbanski220
Jakub Goliszewski https://github.com/jgoliszewski
Mikołaj Guryn https://github.com/Majkel572

## Link do demo rozwiązania
