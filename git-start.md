# Strefa download
1. [Git]()
2. [SourceTree](https://www.sourcetreeapp.com/)
3. [Książka](https://chomikuj.pl/kefirm/Ksi*c4*85*c5*bcki/Informatyka/PHP/Helion+-+Git.+Rozproszony+system+kontroli+wersji,3946879722.pdf)

# Wstępna konfiguracja
https://git-scm.com/book/pl/v1/Dostosowywanie-Gita-Konfiguracja-Gita
(wystarczy ustawić dane i notatnik do edycji)

# Start
1. [Praca z SourceTree](https://confluence.atlassian.com/get-started-with-sourcetree)
2. Generowanie klucza ssh
    1. otwieramy git-bash
    2. [generowanie ssh](https://git-scm.com/book/pl/v1/Git-na-serwerze-Generacja-pary-kluczy-SSH)
    3. [dodawanie klucza ssh do githuba](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)
    
# Tworzenie własnego brancha i wysyłanie zmian
(Wymagana konfiguracja SourceTree)
1. pobieramy repo przy pomocy sourcetree `git@github.com:grupa35/bank.git`
2. robimy nową gałąź z nazwą swojego zespołu przyciskiem branch
3. robimy push przyciskiem push
(wszystkie opcje zostawiamy domyślne)

jeżeli wszystko jest ok powinna pojawić się na githubie


# Pull request
https://help.github.com/articles/about-pull-requests/
https://help.github.com/articles/approving-a-pull-request-with-required-reviews/


   
# Dodanie naszego repo do eclipsa
1. [import projektu do eclipsa](http://help.eclipse.org/kepler/index.jsp?topic=%2Forg.eclipse.platform.doc.user%2Ftasks%2Ftasks-importproject.htm)

# Dodanie naszego repo do intellij
1. na ekranie startowymi import
2. wybieramy folder z projektem
3. opcja `creating project from existing sources`
4. next, next aż do wyboru sdk
5. jeżeli nie mamy wybranego sdk trzeba podać folder instalcji, domyślnie `program files/java/sdkXX`
    * jeżeli nie mamy ściągamy z [oracle.com](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) najnowszą wersję
    * opcjonalnie konfigurujemy ścieżki środowiskowe https://docs.oracle.com/javase/tutorial/essential/environment/paths.html
6. finish i mamy projekt w intellij

# Najważniejsze polecenia do konsoli
https://blog.piotrnalepa.pl/2013/05/19/git-podreczny-zestaw-niezbednych-komend-dla-kazdego-webdevelopera-i-nie-tylko/
