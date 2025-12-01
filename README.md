
# Link do strony demonstracyjnej [https://iviv122.alwaysdata.net/](https://iviv122.alwaysdata.net/)

# Strona testowa nie zawiera wszystkich obrazów, bo nie były dostarczone przez organizatora

# Materiały

* ikony wektorowe [https://lucide.dev/icons/](https://lucide.dev/icons/)
* tłowy obrazek [https://heropatterns.com/](https://heropatterns.com/)


## Nowości
Przycisk starsze posty ładuje je na tej samej stronie.
Stary navbar z cisco oraz poradnikiem itp... znajduje się teraz w side barze.
Nowe skróty przejść na głównej stronie dla nowych uczniów.
Obrazek szkoły na home page.
Aktualizacja nowych social media (skype nieststy już nie istnieje).
## How to update 
```
wp plugin update --all

wp theme update --all
```
# Uwagi co do implementacji strony

* Wszystkie wtyczki są takie same, nic nie było pobrane lub usunięte.
* Strona używa CDN Bootstrap 5.3.3 oraz odpowiedniego jQuery.
* Przycisk „starsze wpisy” korzysta z load-more.js.
* Przycisk „accessibility helper” ma tylko zwiększ/zmniejsz czcionkę, inne funkcje nie są przewidziane i ich wynik jest niewiadomy (dostaliśmy przycisk w takim stanie).
* Brak przycisku „zadzwoń do psychiatry” z tego powodu, że nie działał nam w podanych plikach.
* Przyciski social media są hardkodowane.

## Szczegóły

* Link do Akademia CISCO jest hardkodowany dla sidebaru.
* Strona używa paska wyszukiwania, który bazuje na get_search_form().
* Motyw korzysta z obrazów przechowywanych w folderze images znajdującym się w folderze motywu.
* Logo jest hardkodowane iż za problemów z wysyłaniem zdjęć na WordPress.
* Obrazek szkoły na stronie głównej jest zhardkodowany.
* Przyciski „Gdzie nas szukać”, „Kontakt”, „FAQ” na głównej stronie są hardkodowane, znajdują się w index.php motywu i są dostępne do usunięcia.
* Przyciski „Kontakt” i „FAQ” mają hardkodowane linki, zakładamy, że osoba zwiedzająca stronę chce mieć szybki dostęp do tej informacji.
* W przycisku „Gdzie nas szukać” nie da się zmienić lokalizacji przez interfejs graficzny, zakładamy, że technikum nie zmieni swego położenia.



