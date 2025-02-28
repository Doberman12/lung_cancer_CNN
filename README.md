# Klasyfikacja obrazów płuc za pomocą CNN

## Opis

Ten projekt wykorzystuje konwolucyjne sieci neuronowe (CNN) do klasyfikacji obrazów histopatologicznych płuc. Celem jest automatyczne rozpoznawanie trzech kategorii: gruczolakoraka, zdrowych płuc i raka kolczystokomórkowego.

## Zbiór danych

Projekt korzysta z publicznie dostępnego zbioru danych "Lung Cancer Histopathological Images" z Kaggle. Zbiór zawiera obrazy histopatologiczne płuc, podzielone na trzy kategorie.

## Model

Zbudowano dwa modele CNN:

1. **Model autorski:** Zaprojektowany od podstaw model CNN z kilkoma warstwami konwolucyjnymi, max pooling i gęstymi.
2. **Model pretrenowany (VGG16):** Wykorzystano pretrenowany model VGG16 z wagami ImageNet, dodając do niego własne warstwy klasyfikacyjne.

## Wyniki

Oba modele osiągnęły wysoką dokładność na zbiorze walidacyjnym:

* Model autorski: **97.20%** (ostatnia epoka), **98.16%** (średnia z ostatnich 5 epok), **99.07%** (najwyższa wartość)
* Model VGG16: **97.70%** (ostatnia epoka), **97.71%** (średnia z ostatnich 5 epok), **97.77%** (najwyższa wartość)

## Instrukcje

Aby uruchomić projekt:

1. Pobierz zbiór danych "Lung Cancer Histopathological Images" z Kaggle.
2. Zaimportuj notebook do Google Colab.
3. Zainstaluj wymagane biblioteki (TensorFlow, Keras, scikit-learn, seaborn).
4. Uruchom notebook.

## Wnioski

Projekt pokazuje, że CNN mogą być skutecznie wykorzystywane do klasyfikacji obrazów histopatologicznych płuc. Oba modele osiągnęły wysoką dokładność, co sugeruje ich potencjał w zastosowaniach medycznych.
