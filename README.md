# warsawjs-workshop-prework-static-page

Aplikacja stworzona na potrzeby `WarsawJS Workshop #1` (Prework).

<img src="https://warsawjs.com/static/images/logos/logo-warsawjs.svg" width="400" alt=""/>

## Demo :tada:

Dostępne jest tutaj: <https://piecioshka.github.io/warsawjs-workshop-prework-static-page/public/>

## Krok po kroku 👣

1. Stwórz katalog `warsawjs-workshop-prework-static-page`.
2. Wewnątrz katalogu stwórz pliki `index.html` oraz `main.css`.
3. W pliku `index.html` (w jego 1 linijce) dodaj znacznik `link`, który
    będzie kierował do pliku z `main.css`, wg. wzoru:

    ```html
    <link rel="stylesheet" href="NAZWA_PLIKU.css"/>
    ```

4. W pliku `index.html` (w 2 linijce) dodaj znacznik `h1`, w którym
    wpisać tekst: "Witaj Warszawo", wg. wzoru:

    ```html
    <h1>DOWOLNY TEKST DO WPISANIA</h1>
    ```

5. W pliku `main.css` pokoloruj tekst na czerwono oraz zmień domyślny kolor
    strony na żółty, wg wzoru:

    ```css
    body {
       background-color: KOLOR_W_JEZYKU_ANGIELSKIM; /* np. blue */
       color: KOLOR_W_JEZYKU_ANGIELSKIM; /* np. blue */
    }
    ```

6. Otwórz plik `index.html` w dowolnej przeglądarce:

    * Metodą `drag & drop`
    * albo klikając dwukrotnie na `index.html`

    ![](./images/screenshot-1.png)

7. W pliku `index.html` na samym dole dodaj znacznik `script` wg. wzoru:

    ```html
    <script>
    </script>
    ```

8. Pomiędzy otwarciem i zamknięciem znacznika `script` napisz kod w JavaScript,
    który podmieni tekst na dowolny po 4 sekundach:

    ```javascript
    setTimeout(function () {
        var $h1 = document.querySelector('h1');
        $h1.textContent = 'Dzień dobry';
    }, 4000);
    ```

9. Odśwież stronę i poczekać kilka sekund, aż pojawi się nowy napis!

    ![](./images/screenshot-2.png)

## Zadanie dodatkowe

1. Wejdź na stronę <https://fonts.google.com/>
2. Wybierz czcionkę, która Ci się podoba klikając `[+]`
3. W dolnej części ekranu pojawi się pasek, w który należy kliknąć.
4. W nowym okienku pojawi się tekst podzielony na 3 sekcje:

    * `Your Selection`
    * `Embed Font`
    * `Specify in CSS`

5. W sekcji `Embed Font` będzie linijka HTMLa, którą trzeba skopiować
    i wkleić do pliku `index.html` na samą górę, np.

    ```html
    <link href="https://fonts.googleapis.com/css?family=Indie+Flower" rel="stylesheet"/>
    ```

6. W sekcji `Specify in CSS` będzie krój czcionki, którą trzeba skopiować
    i wkleić do pliku `main.css` pod regułą koloru tekstu, np.

    ```css
    font-family: 'Indie Flower', cursive;
    ```

7. Wystarczy teraz odświeżyć stronę otworzoną w przeglądarce, aby zobaczyć
    tekst napisany wybraną czcionką.

Warto użyć skrótu klawiaturowego: `CTRL + R` albo `CTRL + F5`

![](./images/screenshot-3.png)

## License

[The MIT License](http://piecioshka.mit-license.org) @ 2016
