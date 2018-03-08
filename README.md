# PUTTalky

Chatbot służący do zamawiania pizzy. Wykorzystanie Drools oraz OWL dla zapewniania dialogu z użytkownikiem.

## Przykłady użycia

_[B] oznacza wypowiedź chatbota, [U] użytkownika_

### Wybór pizzy

> [B] Wpisz nazwę lub typ pizzy (spacja aby pominąć)  
> [U] vesuvio  
> [B] Wskazano pizzę: Vesuvio

### Wybór typu pizzy

> [B] Wpisz nazwę lub typ pizzy (spacja aby pominąć)  
> [U] z mięsem  
> [B] Wskazano pizzę: Pepperoni    
> [B] Wskazano pizzę: Vesuvio  

### Wybór dodatku z menu

> [B] Wpisz nazwę lub typ pizzy (spacja aby pominąć)  
> [U]  (space)  
> [B] Jaki dodatek powinna zawierać Twoja pizza:  
> [U] ser  
> [B] Podaj rodzaj ciasta:  
> [U] cienkie   
> [B] Polecam pizzę: 	Margherita  
> [B] Polecam pizzę: 	Vesuvio  
> [B] Polecam pizzę: 	Pepperoni

### Pizza bez dodatku

> [B] Wpisz nazwę lub typ pizzy (spacja aby pominąć)  
> [U]  (space)  
> [B] Jaki dodatek powinna zawierać Twoja pizza:  
> [U] ser, bez mięsa  
> [B] Podaj rodzaj ciasta:  
> [U] grube  
> [B] Przygotujemy specjalną pizzę:  
> [B] Dodatki: 	bez mięso, ser  
> [B] Ciasto: 	grube

### Własny dodatek

> [B] Wpisz nazwę lub typ pizzy (spacja aby pominąć)  
> [U]  (space)  
> [B] Jaki dodatek powinna zawierać Twoja pizza:  
> [U] kurczak  
> [B] Podaj rodzaj ciasta:  
> [U] cienkie  
> [B] Przygotujemy specjalną pizzę:  
> [B]   Dodatki: 	kurczak  
> [B]   Ciasto: 	 	cienkie

### Nietrafiona nazwa pizzy

> [B] Wpisz nazwę lub typ pizzy (spacja aby pominąć)  
> [U] farmerska  
> [B] Jaki dodatek powinna zawierać Twoja pizza:  
> [U] kurczak, pieczarki  
> [B] Podaj rodzaj ciasta:  
> [U] grube   
> [B] Przygotujemy specjalną pizzę:  
> [B]   Dodatki: 	kurczak, pieczarka   
> [B]   Ciasto: 	 	grube

## Lista zmian
* [X] Zamówienie pizzy spoza listy, własny dodatek (także własne ciasto możliwe)
* [X] Zamówienie pizzy o konkretnej nazwie lub typie
* [X] Więcej niż jeden dodatek w pizzy
* [X] Pizza bez * (np. mięsa)
* [X] Przykłady użycia

## License
The content of this project itself is licensed under the [Creative Commons Attribution 3.0 license](http://creativecommons.org/licenses/by/3.0/us/deed.en_US), and the underlying source code used to format and display that content is licensed under the [MIT license](http://opensource.org/licenses/mit-license.php).
