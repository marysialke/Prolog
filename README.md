# Wszystkie 5 zadań z prologa oraz wizualne drzewo genealogiczne do pomocy :)

piątek grupa 11.20(11.30) - **Maria Serwin**

Tutaj wytłumaczenia po mojemu co robiłam: (to samo w mailu)


## Zad. 1 Drzewo genealogiczne

Zdefiniowałam każdego członka rodziny i relacje. Reguły przodek, brat, siostra, kuzyn nie było problemu zrobić, jedynie co to nie robiłam już oddzielnie babcia/dziadek bo byli jako przodek. Zrobiłam jak na ćwiczeniach robiliśmy. Jako iż chciałam sobie ułatwić zadanie to użyłam moich fikcyjnych rodzin, by mi prościej było określić relację między członkami rodziny; jakby był problem w rozróżnieniu kto jest kim - załączyłam tam rysunek drzewa genealogicznego, który zrobiłam z połowy moich rysunków jakie mam do dnia dzisiejszego dla lepszej wizualizacji tego chaosu.


## Zad. 2 Loty

Zdefiniowałam lotniska i połączenia po dwa razy, ale każdy z inną ceną, by szukało tańszego lotu do późniejszej reguły. Reguła bezpośredniego lotu szuka czy on w ogóle istnieje, cena pokazuje wszystkie kwoty lotu, a potem zdefiniowałam, czy ogólnie są połączenia między jednym a drugim lotniskiem oraz jego najkrótszą formę - czyli również najtańszą w tym wypadku. Do znalezienia najkrótszej drogi użyłam findall. Jak nie znajdzie połączenia czyli za cenę równą 0 czyli [], to mówi, że lotu nie ma. Jak znajdzie to używa reguły min_list czyli szuka wartości minimalnej między dostępnymi lotami i też wyświetla odpowiedni komunikat.


## Zad.3 Magazyn

Na sam początek dałam regułę dynamic do produktów, by późniejsze reguły ‘przenoszenia’ mogły działać. Potem dałam jaki produkt jest gdzie w jakim magazynie. Potem reguła do sprawdzania czy są rzeczy na stanie i tam dałam że Ilość jest większa niż 0, ale to zero też wyłapuje bez znaku równości. Nie wiem czy to w prologu jest czy ogólnie nie trzeba =, ale działa to działa. Nie dotykam. Potem dałam przenoszenie, czyli czyta ile ma tych rzeczy, usuwa tyle i potem tyle dodaje w inne miejsce - czyli nasz wybrany magazyn. W uzupełnianiu po prostu dodaje do przeczytanej ‘liczby N’ tych produktów i je sumuje na koniec. Oczywiście wszędzie format, by były ładne zdania.


## Zad. 4 Kurier

Dałam definicje miast i ich połączeń. Podałam czasy przejazdu, już pojedynczo każda trasa, bo prolog już płakał, że za dużo zmiennych. Potem dałam, by mi liczyło łącznie ilość czasu (w minutach), by ta wyszukana droga miała, jako zmienną T (tam gdzie trasa ma swoje alternatywy przez inne miasta - to dodaje do siebie minuty, a przynajmniej powinno dodawać). Najkrótsza trasa sprawdza mi czy istnieje droga bezpośrednia i ją zwraca, jak nie, czyli są ‘przesiadki miastowe’ to sprawdza czy droga w ogóle jest możliwa i dałam komendę, by nie zapętlało, czyli nie cofało się do poprzedniego miasta z którego startowaliśmy. Wywołuje najkrótszą trasę i łączny czas. Tu bez funkcji format, bo wyskakiwały błędy i uznałam, że jak nie trzeba tu już to nie daję. A i przy najkrótszej trasie pokazuje mi czasem najpierw większą kwotę, a potem jak kliknę NEXT to mniejszą, ale nie wiem co jest nie tak, więc już nie chciałam psuć bardziej tego. Ważne, że ładnie i składniowo pokazuje co trzeba.


## Zad. 5 Książki

Dałam mangi, a nie książki, bo to moje hobby, a ich tytuły mam pod ręką. Na początku komenda do zmiany ocen, na później. Zdefiniowane tytuły razem z autorem i gatunkiem (proszę nie sprawdzać dla lepszego zdrowia). Potem zdefiniowane oceny z oceną oczywiście maksymalną. Potem zdefiniowałam preferowane gatunki. Dalej pojawił się problem, wciąż nie wiem jak to ostatecznie mi zadziałało, bo użyłam innych opcji, by to znaleźć niż właśnie bagof itd, ale tak jak napisałam w pliku, znam komendę list to użyłam i działa. Na koniec reguła assertz do dodawania ocen i retract do jego usuwania.


Tam ogólnie jak już chodzi o zapytania, to w większości przypadkach trzeba dać inne niż jakie pan dał w przykładzie, bo dawałam szersze opcje, bo nie umiałam tak zwięźle. A w książkach jakoś tak poszło, że dałam tytuł i pokazuje preferowany gatunek, więc zrobiłam na odwrót niż jak powinno być (sama nie wiem jak, ale zostawiam już tak). Mam nadzieję, że to oceny nie zmieni lub nie obniży.
