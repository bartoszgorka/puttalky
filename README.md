# PUTTalky

Chatbot służący do zamawiania pizzy. Wykorzystanie Drools oraz OWL dla zapewniania dialogu z użytkownikiem.

## Przykłady użycia

_[B] oznacza wypowiedź chatbota, [U] użytkownika_

### Własny dodatek

> [B] Jaki dodatek powinna zawierać Twoja pizza:  
> [U] kurczak, sharma  
> [B] Podaj rodzaj ciasta:  
> [U] cienkie  
> [B] Przygotujemy specjalną pizzę:  
> [B]   Dodatki: 	kurczak, sharma  
> [B]   Ciasto: 	cienkie

### Obsługa bez dodatku

> [B] Wpisz nazwę lub typ pizzy (spacja aby pominąć) 
> [U]  (space)
> [B] Jaki dodatek powinna zawierać Twoja pizza:
> [U] sos, bez mięsne, sharma
> [B] Podaj rodzaj ciasta:
> [U] cienkie
> [B] Przygotujemy specjalną pizzę:
> [B]   Dodatki: 	Sos, sharma  
> [B]   Bez: 		DodatekMięsny

## Lista zmian
* [X] Zamówienie pizzy spoza listy, własny dodatek (także własne ciasto możliwe)
* [X] Zamówienie pizzy o konkretnej nazwie lub typie
* [X] Więcej niż jeden dodatek w pizzy
* [X] Pizza bez mięsa
* [X] Przykłady użycia

## License
The content of this project itself is licensed under the [Creative Commons Attribution 3.0 license](http://creativecommons.org/licenses/by/3.0/us/deed.en_US), and the underlying source code used to format and display that content is licensed under the [MIT license](http://opensource.org/licenses/mit-license.php).
