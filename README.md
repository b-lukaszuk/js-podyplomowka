# js-podyplomowka

**Deployed version ->** [Here](https://b-lukaszuk.github.io/deployedProjects/moviesTiles/moviesTiles.html)

Zadanie zaliczeniowe na koniec semestru 1 z 'Podstawy JavaScript'<br>
Podyplomowka PB Front-End Develpment 2019/2020<br>
Pisane w czystym JS-ie. Staralem sie jak najmniej dawac w HTML i Css, a jak najwiecej w JS <br>
Testowane, ale nie optymalizowane.<br>

**Nie rozbite na podpliki (moduly JS)** wtedy jeszcze tego za bardzo nie mielismy

## Tresc zadania

### Lista filmow - Kafelki

Na podstawie podanej listy filmów:
https://jsbin.com/nosinujixa/edit?js
stwórz listę kafelków.

Każdy z tych kafelków powinien wyświetlać:
+ rok premiery filmu,
+ nazwę filmu

Rok premiery wytnij z napisu i wyświetlaj w osobnym elemencie
kafelka. Ostyluj elementy, a co drugiemu kafelkowi nadaj
inną klasę, która zmieni mu tło.

### Select - lista filmow - filtrowanie po roku

Na podstawie lat premier filmów stwórz i wypełnij listę `<select>`.
Zadbaj, aby lata nie powtarzał się na niej i
były uporządkowane rosnąco.
Wybranie roku z listy powinno spowodować przefiltrowanie kafelków -
widoczne pozostaną jedynie filmy ze wskazanego roku,
zaś pozostałe zostaną ukryte.

### Wyswietlanie danych ogolnych o filmach

Powyżej listy filmów wyświetl napis mówiący o liczbie wszystkich
filmów oraz o liczbie aktualnie widocznych (nie ukrytych).

### Chmura tagow

Na podstawie nazw filmów stwórz tzw. chmurę tagów,
czyli listę wszystkich słów występujących w liście filmów.
Zadbaj, aby dane słowo nie występowało kilka razy na liście
(wielkie i małe znaki traktuj jednakowo).
Słowa uporządkuj alfabetycznie.

Ustaw rozmiar czcionki tagu/słowa na podstawie liczby jego
wystąpień w tytułach filmów:
- 8px jeśli tag występuje tylko raz
- 12px jeśli występuje dwa razy
- 16 px ...
- 20px ...
- 24px jeśli występuje 5 lub więcej razy.

#### Filtrowanie po tagach

Kliknięcie w tag powoduje odfiltrowanie filmów -
wyświetlone zostaną tylko te, których tytuł zawiera wskazane słowo
(pamiętaj o aktualizacji napisu wyświetlającego liczbę widocznych
filmów). Dodaj również specjalny tag "wszystkie" w celu
wyświetlenia wszystkich filmów.

### Tryb nocny-dzienny

W dokumencie znajduje się przełącznik
(odpowiednio ostylowany element) pozwalający na włączenie
"trybu nocnego". Domyślnym trybem jest tryb dzienny
(elementy mają jasne tło). Włączenie trybu nocnego zmienia
wyświetlanie elementów (ciemne tło). Ponownie kliknięcie
przełącznika przywróci tryb dzienny.

### Przyciski - sortowanie po nazwie i roku premiery

Dwa przyciski pozwalające na sortowanie filmów - alfabetycznie oraz po roku premiery.
Spróbuj pozwolić na sortowanie rosnąco (po pierwszym naciśnięciu przycisku) i malejąco
(po drugim naciśnięciu przycisku).

### Formularz - dodawanie filmow

Stwórz formularz z dwoma polami (rok i nazwa filmu)
umożliwiającymi dodanie nowego filmu i dodanie do go obecnej
listy filmów. Formularz powinien mieć walidacje uniemożliwiającą
wysłanie pustego formularza oraz komunikat po poprawnym dodaniu
filmu do listy. Po dodaniu filmu sekcja wyświetlająca liczbę
filmów powinna zostać zaktualizowana. Upewnij się że wszystkie
funkcjonalności działają również dla nowo dodanego filmu.

## Do własnego użytku, nie powinno być używane przez nikogo innego.<br>
## For my personal use only, should not be used by anyone else.
