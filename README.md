# CEL PROJEKTU
Celem projektu jest przetestowanie aplikacji typu to-do-list w ramach warsztatów 'Testowanie manualne aplikacji' - 'Czy IT jest dla mnie'. Testy przeprowadzałem samodzielnie na bazie dostarczonej mi dokumentacji biznesowej. Wszelkie znalezione błędy raportuje w narzędziu Jira. W ramach portfolio przedstawiam trzy przypadki testowe.


# ZAŁOŻENIA APLIKACJI
Aplikacja umożliwia dodawanie list do tablicy. Każdej liście mogę przypisać nazwę. Do każdej listy mogę przypisywać wiele zadań (tasków). W ramach każdego zadania mogę skonfigurować tytuł, opis, dodatkowe etykiety.

![image](https://github.com/PatrykStencel/Projekt/blob/main/img/1.png)

# JAK PRZYGOTOWUJE PRZYPADKI TESTOWE

Przypadki testowe rozpatruje w 3 kategoriach:

* funkcjonalne (podstawowa funkcjonalność opisana w dokumentacji) - W ramach testów funkcjonalnych sprawdzam możliwe scenariusze opisane w dokumentacji. Sprawdzam wszystkie możliwe poprawne kombinacje danych wejściowych oraz te które mogą spowodowac błędy.

* użytkowe/wizualne - w ramach testów sprawdzam czy aplikacja jest zgodna z przygotowanymi makietami, jak również czy interfejs użytkownika wygląda estetycznie i czy jest użyteczny

* techniczne - w ramach testów technicznych jeżeli to możliwe staram się modyfikować kod HTML.

## TESTOWANY FRAGMENT APLIKACJI 'Add checkbox list to a task' 

![image](https://github.com/PatrykStencel/Projekt/blob/main/img/1dok.png)
![image](https://github.com/PatrykStencel/Projekt/blob/main/img/2dok.png)

#### TEST CASE 1 - Przypadek podstawowy: Dodanie 'checkbox list' do zadania - WYNIK POPRAWNY

![image](https://github.com/PatrykStencel/Projekt/blob/main/img/task.png).
