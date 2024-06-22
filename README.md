
# Search Bar

Wyszukiwarka przepisów działająca na React i na API Edamam recipe api.


![Uploading Zrzut ekranu 2024-06-22 o 15.23.41.png…]()

## Framework React
https://react.dev/ 

Główne cechy:

Komponentowa struktura: React opiera się na komponentach, które są samodzielnie działającymi częściami interfejsu użytkownika.

JSX (JavaScript XML): Rozszerzenie składni JavaScript, które pozwala na mieszanie kodu JavaScript i HTML w celu tworzenia interfejsu.

Virtual DOM: Efektywniejsze zarządzanie zmianami w interfejsie poprzez wirtualny model DOM.

Reużywalność komponentów: Modularne podejście ułatwiające ponowne użycie komponentów w różnych częściach aplikacji.

Duża społeczność i ekosystem: Rozległa społeczność i wsparcie narzędziowe, co ułatwia naukę i rozwój aplikacji.
## Generatory komponentów (modeli, kontrolerów, api, ...)
Create React App (CRA) dostarcza strukturę projektu i szablony plików, ale nie zawiera wbudowanych generatorów komponentów. 

Ręcznie zostaly stworzone komponenty.

API - wykorzystano Edamam Recipe API
https://developer.edamam.com/edamam-docs-recipe-api


## Routery kierujące ruchem HTTP

Do obsługi routingu w aplikacji użyto React Router. 
## Szablony HTML

Szablony HTML w projekcie są tworzone za pomocą JSX (JavaScript XML), który jest rozszerzeniem JavaScript umożliwiającym deklaratywne tworzenie interfejsu użytkownika w React. JSX pozwala na mieszanie kodu JavaScript i HTML
## Konektory baz danych
Aplikacja nie korzysta bezpośrednio z konektorów do baz danych, ponieważ jej głównym celem jest komunikacja z zewnętrznym API (Edamam API) 
## Współpraca z REST API
Axios - Komunikacja z REST API

Axios jest biblioteką HTTP dla przeglądarek i Node.js, która umożliwia wykonywanie zapytań HTTP do zewnętrznych serwerów, w tym do REST API. Jest powszechnie stosowany w aplikacjach React do pobierania danych z API i wysyłania żądań HTTP.

https://axios-http.com/docs/intro
