KROK 1.Rozpocznij prace z:
	- u góry VSC wpisz: ">git:clone ---adres url repo---"

	# 2. Przejdź na główną gałąź
	git switch main

	# 3. Pobierz wszystkie zmiany, które Ty (lub koledzy) 	zmergowaliście
	git pull origin main

KROK 2.
	# Stwórz NOWĄ gałąź (np. dla zadania 4) i od razu się na nią przełącz
	git switch -c task-4-json

KROK 3: Wykonaj całe zadanie 


	Pracuj normalnie w VS Code. Twórz pliki, foldery i pisz kod tylko dla tego jednego zadania.

KROK 4: Zapisz zmiany (Commit)

	Gdy zadanie jest gotowe:
	# 1. Dodaj wszystkie swoje nowe/zmienione pliki
	git add .

	# 2. Zapisz zmiany z czytelnym opisem
	git commit -m "Ukończono Zadanie 4: Dodanie pliku JSON"

KROK 5: Wyślij swoją gałąź na GitHub
	Wyślij na serwer tylko swoją nową gałąź (NIE main!).

	# -u ustawi śledzenie, więc następnym razem wystarczy 'git push'
	git push -u origin task-4-json

KROK 6: Zrób Pull Request i Merge na stronie GitHub

	Wejdź na stronę swojego repozytorium na GitHubie.

	Powinien pojawić się żółty pasek z Twoją gałęzią – kliknij "Compare & pull request".

	Kliknij "Create pull request".

	Kliknij zielony przycisk "Merge pull request" i potwierdź.

8f2fc21de1ffd4fcfd2a5e5bbe329614c230192d
a. Copy-paste a link to the GitHub repository in Moodle.
b. Copy-paste the last commit id of the repository (this number is made up
of 40 characters, e.g. 3cd5240148b2e1d007ea0828c15612488a4dc18d;
you can find this number on GitHub by viewing the commit list)
c. Upload a copy of the repository in .zip format. You can download your
repository as .zip directly from GitHub, for example (see the green Code
button).
