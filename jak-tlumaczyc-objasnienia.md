# Jak tłumaczyć Objaśnienia

## Zachowaj znakowanie

### O strukturze dokumentu
Każdy dokument z serii Objaśnienia jest dokumentem zapisanym w formacie HTML. 
Finalnie wszystkie dokumenty będą automatycznie uzupełnione:

- o brzmienie objaśnianej wytycznej lub kryterium sukcesu. Nie dopisuj ich do dokumentów;
- o techniki wystarczające i pomocnicze, jeśli nazwa techniki nie została ptrzytoczona (jest tylko "puste" łącze do techniki.

Tekst, który trzeba przetłumaczyć, znajduje się zawsze o obszarze `main` i został oznaczony komentarzami:
- po znaczniku `main` komentarzem brzmiącym: *TU ROZPOCZNIJ TŁUMACZENIE*;
- przed znacznikiem zamykającym `main` komentarzem brzmiącym: *PONIŻEJ NIC NIE ZMIENIAJ*.

### Zwracaj uwagę na znaczniki

Podczas tłumaczenia zwracaj uwagę na znaczniki:

- nie usuwaj żadnych znaczników formatujących nagłówki (znaczniki `hn`), akapity (znaczniki `p`), listy i elementy list (znaczniki `ul`, `ol`, `dl`, `li`, `dt` i `dd`, obrazki (znaczniki `img` i ich atrybuty, zobacz uwagę o tekstach alternatywnych poniżej);
- gdy napotkasz znaczniki `em` i `strong`, oznacz nimi w tłumaczonym tekście odpowiedniki słów i fragmentów wyróżnionych w oryginale;   
- **bardzo ważne**: słowa lub frazy objęte znacznikami otwierającym `<a>` (bez żadnych atrybutów) i zamykającym `</a>` to terminy słownikowe. Brak atrybutów to nie błąd - do znacznika otwierającego zostanie później dodane automatycznie łącze do terminu w słowniku. Zachowaj te znaczniki w odpowiednim miejscu tłumaczonego tekstu.

### Teksty alternatywne

W niektórych objaśnieniach znajdują się ilustracje (objęte znacznikiem `img`). Koniecznie przetłumacz teksty alternatywne obrazków umieszczone w atrybucie `alt`. Nie zmieniaj niczego w treści atrybutu `src`. Nie zmieniaj też wartości atrybutów `width` i `height`, jeśli są podane.

### Łącza do treści anglojęzycznych i treść łączy anglojęzycznych

- Dodaj w każdym łaczu jako paramtery znacznika otwierającego `<a...>` atrybuty `lang` i `hreflang`, np. `<a lang="en" hreflang="en" href=...>` 
- Możesz w nawiasie umieścić tłumaczenie na język polski tytuły zasobów, do których prowadzą łącza.   

## Wskazówki dotyczące tłumaczenia
1. Śmiało **wspomagaj się translatorami internetowymi**. To nie ujma. Zawodowi tłumacze również wspomagają się narzędziami automatycznymi. Dobrą praktyką jest korzystanie co najmniej z dwóch translatorów, np. [Tłłumacz Deepl](https://www.deepl.com/translator) oraz [Google Tłumacz](https://translate.google.com/). Do dyspozycji masz także Bind (w przeglądarce Edge).
1. **Oddaj wiernie sens tekstu źródłowego**. „Tłumacz nie jest zobowiązany do tłumaczenia dosłownego, lecz ma za zadanie oddać wiernie sens tekstu źródłowego zgodnie z naturą i specyfiką obu języków”, „Wierność to zgodność z oryginałem pod względem przekazywanych treści, intencji i specyfiki języka”.
1. **Nie twórz nowej treści**. Nie dodawaj treści i znaczeń, których nie ma w oryginale. Nie odejmuj niczego, co jest w oryginale.
1. **Nie zmniejszaj i nie wzmacniaj** znaczenia żadnej treści.
1. **Masz wątpliwości?** - umieść alternatywną wersję tłumaczenia fragmentu, który sprawia Ci trudność w tłumaczeniu. 
1. **Nie musi być idealnie** - wystarczy, że będzie dobrze, zrozumiale, zgodnie z polskimi zwyczajami językowymi 

 

