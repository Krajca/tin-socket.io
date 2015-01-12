# Zadanie 1.

Korzystając z zawartego w repozytorium „szkieletu” stwórz prosty komunikator internetowy.
Wszystkie zależności projektu zostały zdefiniowane w plikach konfiguracyjnych `package.json`
oraz `bower.json`.

  - Do zbudowania i obsługi interfejsu użytkownika wykorzystaj bibliotekę `jQuery`,
    pozbywając się jednocześnie zawartych w przykładzie odwołań do standardowego DOM API.
  - Styl opisujący wygląd interfejsu stwórz z pomocą języka `{less}`. Szkielet pliku
    źródłowego znajduje się w podkatalogu `public/css`.
  - Podczas łączenia się z serwerem komunikatora użytkownik powinien móc wybrać sobie
    nazwę/identyfikator, który musi być *unikatowy* w ramach zbioru wszystkich *aktywnych*
    w danym momencie użytkowników.
  - Wymiana wiadomości pomiędzy użytkownikami powinna korzystać z biblioteki `Socket.io`.
  - W czasie swojego działania, serwer powinien gromadzić całą historię wiadomości.
  - Interfejs komunikatora powinien udostępniać historię wiadomości (każda wiadomość powinna
    być opatrzona informacją o autorze oraz czasie utworzenia).
  - Po podłączeniu się do serwera, użytkownikowi wyświetlany jest komunikat powitalny,
    a pozostali użytkownicy otrzymują informację o jego dołączeniu. 

## Jak uruchomić przykład

Będą w katalogu głównym projektu, należy wykonać poniższe instrukcje:

  - `npm install`
  - `bower install`
  - `node app.js`
  
# Zadanie 2.

Do rozwiązania Zadania 1. dodaj obsługę „pokojów”, czyli nazwanych podgrup użytkowników.
W ich implementacji wykorzystaj mechanizm „przestrzeni nazw” (ang. name spaces) `Socket.io`.

## Materiały i odsyłacze

  - [Repozytorium kodu i dokumentacja API Socket.io](https://github.com/Automattic/socket.io)
  - [Strona główna projektu Socket.io](http://socket.io/)