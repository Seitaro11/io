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

Aplikacja powinna posiadać dwa niezależne od siebie moduły - pracownika i administratora. Administrator posiada możliwość przesyłania plików graficznych i protokołów do wybranych pracowników, zaś pracownik może przesyłać z powrotem pliki .xml zawierające naniesione markery.
