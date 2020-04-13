<img alt="Logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

#  Python prework - Zmienne i typy danych

#### Schemat rozwiązywania zadań:

* wszystkie zadania z tego działu wykonuj w odpowiednich plikach exercise_X.py,
* na tej stronie(https://docs.python.org/3/library/functions.html#built-in-funcs)  znajdują się funkcje wbudowane w Pythonie. Nie nazywaj swoich zmiennych żadną z tych funkcji wbudowanych.  Np. `sum = a + b` albo `int = 6`, albo `float = 5.4` - to są błędne zapisy.

Zobacz co się stanie jak popełnisz błąd:

```python
>>> print(sum([1,2,3,4]))
10
>>> sum = 10 + 5 + 10
>>> print(sum([1,2,3,4]))
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'int' object is not callable
```

#### Zadanie 1.

W odpowiednim pliku utwórz 5 zmiennych i wstaw do nich następujace dane:

* liczbę całkowitą,
* liczbę zmiennoprzecinkową,
* string (napis),
* wielolinijkowy napis,
* wartość logiczną.

Skomentuj odpowiednio każdą zmienną, podając informację jaki typ danych przechowuje.

Każdą zmienną wyświetl na ekranie, w postaci:
`Zmienna XXX typu YYY`


#### Zadanie 2.

Stwórz dwie zmienne i przypisz do nich dwie wartości logiczne, jakie znasz. Porównaj je za pomocą operatora ==, a
wynik zapisz do trzeciej zmiennej. Napisz w komentarzu swoje spostrzeżenia.

#### Zadanie 3.

W odpowiednim pliku utwórz następujące zmienne:

* `add1` o wartości całkowitej,
* `add2` o wartości zmiennoprzecinkowej,
* `sum_value`, która będzie sumą `add1` i `add2`.
* tip: nie używaj zmiennej sum, ponieważ jest to zarezerwowane słowo w Pythonie

Każdą zmienną wyświetl na ekranie razem z jej typem.

#### Zadanie 4.

Napisz program, który utworzy dwie zmienne: `a1` i `a2`, po czym wykona następujące czynności:

* Przypisze zmiennej `a1` wartość 10, zmiennej `a2` wartość 15,
* Utworzy zmienną `sum_value`, której nada wartość sumy zmiennych `a1` i `a2`,
* Utworzy zmienną `quotus`, której nada wartość ilorazu zmiennych `a2` i `a1`,
* Utworzy zmienną `int_part`, której nada wartość części całkowitej zmiennej `quotus`,
* Wyświetli w terminalu wartości wszystkich zmiennych.
