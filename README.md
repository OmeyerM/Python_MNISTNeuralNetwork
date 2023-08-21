# Program Rozpoznawania Ręcznie Pisanych Cyfr

Program rozpoznawania ręcznie pisanych cyfr umożliwia użytkownikowi ręczne rysowanie cyfry na interfejsie, a następnie wykorzystuje wytrenowany model do rozpoznania wprowadzonej cyfry.

## Wymagania

Aby korzystać z programu, potrzebujesz:

- Dowolnego programu obsługującego skrypty .ipynb, np. Jupyter Notebook, Visual Studio Code itp., do uruchomienia interfejsu.
- Zainstalowanych bibliotek:
  - `pickle` - do wczytania zapisanego modelu
  - `matplotlib` - do wyświetlenia wykresów
  - `numpy` - do operacji na danych
  - `keras` - do pobrania i transformacji danych
  - `PyQt5` - do obsługi interfejsu.

## Pobieranie plików

1. Pobierz plik `MNIST.ipynb` ze źródłowego repozytorium i uruchom go w programie obsługującym skrypty .ipynb, np. Jupyter Notebook. Ten plik zawiera kod do trenowania modelu rozpoznawania cyfr MNIST, zapisania tego modelu do pliku `neural_network.pkl`, a także wyświetlenia interfejsu.
2. Pobierz plik `neural_network.pkl`, który zawiera wytrenowany model sieci neuronowej. Upewnij się, że plik ten znajduje się w tym samym folderze co program rozpoznawania cyfr.

## Uruchamianie programu

1. Uruchom program obsługujący skrypty .ipynb, np. Jupyter Notebook.
2. Otwórz plik `MNIST.ipynb` i wykonaj go w całości, aby uruchomić interfejs rozpoznawania ręcznie pisanych cyfr.

## Korzystanie z interfejsu

1. Po uruchomieniu programu zobaczysz interfejs, który pozwala ręcznie rysować cyfry.
2. Użyj myszki, aby narysować cyfrę w obszarze do rysowania.
3. Po narysowaniu cyfry kliknij przycisk "Rozpoznaj", aby uruchomić proces rozpoznawania.
4. Model sieci neuronowej dokona predykcji i wyświetli wynik.
5. Możesz użyć przycisku "Czyść" i kontynuować rysowanie kolejnych cyfr.
6. Dodatkową opcją jest możliwość wylosowania cyfry ze zbioru treningowego - przycisk "Losuj".
7. Również można poznać istotność danych pikseli przy przewidywaniu danej cyfry - przycisk "Istotność".
