Rozwiazanie zadania allegro_software_developer_intern-Poznan

Dzień dobry,
Do stworzenia usługi użyłem języka Python, micro frameworka Flask oraz biblioteki Pillow.
Rozwiązanie spełnia wszystkie wymagania specyfikacji podanej w zadaniu, wraz z walidacją requesta.
Dodatkowo zawiera ono opcjonalny argument 'kolor', który pozwala przekazać kolor tła w formacie RGB dla mozaiek łączących 3, 5 lub 7 zdjęć.
By ułatwić testowanie usługi dołączyłem również prostą stronę demo.
Mam nadzieje, że dzięki tej implementacji uda mi się dotrzeć do kolejnego etapu rekrutacji :)

Pozdrawiam,
Marcin Piskorz


Jak używać usługę:
1. Upewnić się, że Python oraz package manager PIP są zainstalowane na komputerze.

2. Otworzyć główny folder w terminalu.

3. Zainstalować wymagane biblioteki python przy użyciu komendy: 
	pip install -r requirements.txt
	
4. Uruchomić usługę przy użyciu komendy: 
	python server.py
	
5. Otworzyć strone HTML znajdującą się w folderze 'demo' i wygenerować mozaikę.
