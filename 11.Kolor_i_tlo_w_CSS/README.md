<img alt="logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# CSS &ndash; kolor i tło

Style CSS pisz w pliku style.css. Sprawdź czy plik style.css jest dodany do pliku index.html

1. Stwórz element **div** o klasie "opacityTest", a w nim dwa paragrafy wypełnione tekstem. Pierwszemu elementowi **p** nadaj klasę ```first```, a drugiemu ```second```. Ustaw dowolne tło dla pierwszego elementu **p** i nadaj mu przezroczystość 0.4 za pomocą RGBa (pamiętaj o przesłonięciu koloru RGBa wcześniej -  jeśli nie pamiętasz, wróć do prezentacji, do slajdu "Przezroczystość tła").

2. Następnie dla drugiego elementu **p** również ustaw dowolne tło oraz ustaw mu przezroczystośc za pomocą opacity. Porównaj efekty. Opisz spostrzeżenia w komentarzu. Jak zmienia się div, a jak elementy w nim zawarte?

3. Za pomocą generatora [gradient-generator](http://www.cssmatic.com/gradient-generator) stwórz gradient dla elementu **div** o klasie ```gradient```.
Postaraj się aby kolory były zbliżone do poniższych:

	![Przykładowy gradient](images/gradient.jpg)

4. Wykonaj następujące polecenia:
   * pobierz dowolny obrazek &ndash; np. z tej strony [sitebuilderreport](http://www.sitebuilderreport.com/stock-up) i zapisz go w podfolderze **images** (w głównym folderze projektu),
   * stwórz element **div** o klasie **image** i ustaw dla niego tło w postaci powyższego obrazka.

5. Następnie ustaw elementowi **div** z poprzedniego zadania szerokość na 100% oraz wysokość na 200px oraz zablokuj powielanie obrazka.

6. Ustaw obrazek z poprzedniego polecenia na środku elementu **div** (skorzystaj z **background-position**).

## Uwaga
Gradient powinien mieć prefiksy dla starszych wersji przeglądarek. Wystarczy skorzystać z generatora i skopiować kod.

Przyjrzyj się linkowi. Dwie kropki oznaczają wyjście poziom wyżej (do głównego folderu):

  'background-image: url(../images/mydog1.jpg);'


## Potrzebujesz pomocy lub inspiracji?

* [dokumentacja, gradient](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient)
* [dokumentacja, background-image](https://developer.mozilla.org/pl/docs/Web/CSS/background-image)
* [tutorial video Codecourse, background-image](https://www.youtube.com/watch?v=cUF-q50DPPM)
* [generator gradientu](http://www.cssmatic.com/gradient-generator)
* [sitebuilderreport, stock photos](http://www.sitebuilderreport.com/stock-up)
* HTML i CSS &ndash; pre-work
