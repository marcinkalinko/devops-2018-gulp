# devops-2018-gulp

## Linki
https://babeljs.io/learn-es2015/ - strona babela z przykładami z ES6

https://babeljs.io/repl/ - playground dla babela

http://es6-features.org/#Lexicalthis - nowości w ES6

## Zadania

1. Upewnij się, ze node oraz gulp są zainstalowane globalnie:
    > node -v

    > gulp -v
2. Jezeli node nie jest, zainstaluj go z tej strony :
    > https://nodejs.org/en/
3. Jezeli gulp nie jest, zainstaluj go tą komendą :
    > npm install gulp-cli -g
4. Przejdz w terminalu do katalogu projektu i uruchom instalację pakietów :
    > npm install
5. Po zainstalowaniu uruchom server i zobacz co się dzieje w plikach
    > gulp serve
6. Obejrzyj plik gulpfile.js
    * Zmienne
    * Zadania
    * Zadanie domyślne
7. Sprawdz działanie serwera
    * Zmień coś w pliku src/index.html
    * Zmień coś w pliku src/js/main.js
    * Zmień coś w pliku src/scss/main.scss
8. Zadania:
    * Dodaj nowy plik index2.html i zmień zadania tak, aby to nowy plik index2.html był kopiowany (domyslnie browsersync i tak będzie czytał index.html, więc index2.html będzie kopiowany ale nie używany)
    * W podobny sposób dodaj i zmień w ustawieniach pliki main2.js i main2.scss
    * Dodaj nowe pliki main2.js i main2.scss do pliku index.html
    * Stwórz nowy folder o nazwie "zrodla" i stwórz tam odpowiadająca tobie strukture plików
    * Stwórz dowolne dwa skrypty działające na plikach z nowego folderu.
    * Ściągnij i użyj gulp-minify - bibliotekę do minifikacji plików Javascript (https://www.npmjs.com/package/gulp-minify)
