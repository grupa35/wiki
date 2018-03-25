# Ustawienia Intellij

Ustawienia = File -> Settings lub Ctrl + Alt + S
***
### Dodatki
`Ustawienia -> Plugins -> Browse Repository`
* save actions
* builder generator

***

### Ustawienia
**Brak wspomnienia o opcji -> Default**
1. Save actions `Ustawienia -> Save Actions`
    * activate save actions on save
    * no action if compile errors
    * organize imports
    * reformat file
    * rearrange fields and methods
    * add missing @OVerride annotations
    * remove unnecessary this
    * remove final from private method
    * remove explicit generic type for diamond
    * remove unused suppress warning annotation
    * remove unnecessary semicolon
2. Code Style `Ustawienia -> Editor -> Code Style -> Java -> Scheme -> Koło zębate -> Import Scheme -> Intellij`
    * [pz-style](pz-style.xml)
3. Git `Ustawienia -> Version Control -> Git`
    * Path to git executable (Zmienić jeżeli instalacja była do niestandardowego folderu)
    * SSH native
    * Allow Force Push -> True, protected -> master
4. Github `Ustawienia -> Version Control -> Github`
    * Podajemy swoje dane
5. Trello `Ustawienia -> Tools -> Tasks`

    `nazwa_grupy = pz-backend lub pz-frontend`
    * Changelist -> nazwa_grupy-{number} {summary}
    * feature branch -> nazwa_grupy-{number}
    * Server -> z listy wybieramy trello
    * Klikamy ‘Where can I get authorization token?’ i kopiujemy z przeglądarki token do pola token
    * Board -> Wybieramy nazwa_grupy
    * List -> All
    * Zakładka -> Commit message -> Add -> nazwa_grupy-{number} {summary}

**Po stworzeniu projektu dodamy kilka ustawień**
***
### Skróty klawiczowe
[Polecam zapoznać się ze skrótami klawiszowymi z tego linku](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)

Najczęściej używane
*  2x Shift -> Szybkie szukanie pliku
* Alt + Enter -> quick fix
* Ctrl + H -> Hierarchia klas
* F4 -> Źródło
* Alt + F7 -> Użycia
* Ctrl + Shift + I -> Szybki podgląd
* Ctrl + Shift + P -> Parametry metody
* Shift + F6 -> Zmiana nazwy wszystkich użyć
* F6 -> Przenieś klasę/plik
* Ctrl + Alt + L -> formatowanie kodu
* Alt + Insert -> Generowanie kodu
* Git
    * Ctrl + K -> Commit
    * Ctrl + Shift + K -> Push
    * Ctrl + T -> Aktualizacja projektu
