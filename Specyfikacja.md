# Projekt z Inżynierii Oprogramowania

## Treść zadania projektowego

Tematem projektu jest stworzenie aplikacji PhotoMark pozwalającej nanieść marker na pliki graficzne przy pomocy przyjaznego i intuicyjnego interfejsu użytkownika. Aplikacja powinna składać się z dwóch zależnych od siebie modułów: administratora zlecającego pracę oraz pracownika, tą pracę wykonującego.

## Słownik projektu

##### Marker

Marker stanowi opis punktu zaznaczonego na obrazie przez pracownika. Składa się z pary współrzędnych i etykiety. Dodanie etykiety jest opcjonalnie - w przypadku, gdy zaistnieje taka potrzeba, administrator powinien zaznaczyć to w protokole.

##### Pakiet obrazów

Zestaw plików graficznych przeznaczonych do opisania markerami według załączonego protokołu.

##### Protokół

Zestaw instrukcji dotyczących sposobu umieszczania markerów na obrazie. Jest dołączany do pakietu obrazów wysyłanych przez administratora.

## Wymagania funkcjonalne

### Podział modularny

Aplikacja podzielona jest na dwa związane ze sobą moduły - administratora i pracownika. Rola użytkowników w tych modułach jest następujące:

##### Administrator

Administrator tworzy zadania będące pakietami obrazów, które mogą być:

* opublikowane w systemie, kazdy pracownik przypisany w do autora zadania może podjąć się pracy nad pakietem, wtedy zadanie w systemie nie jest już widoczne dla reszty pracowników.
* przypisane do konkretnego pracownika należącego do administratora.

Administrator może przypisać do siebie użytkownika o ile ten nie należy do żadnego administratora. W innym wypadku może wyrazić prośbę o transfer pracownika do jego właściciela.

##### Użytkownik

Użytkownik korzystając z narzędzi dostępnych w swoim module wykonuje zlecone zadania przez administratorów, ewentualnie rezerwuje sobie zadanie stworzone na forum systemu.
