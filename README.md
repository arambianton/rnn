# Рекуррентные нейронные сети

Классификация тональности отзывов и языковое моделирование.

**Данные:** Large Movie Review Dataset (IMDB), бинарная классификация. Словарь 5 000 токенов (WordLevel, NLTK stopwords).

**Часть 1 — классификация:** LSTM-сеть. Реализованы и сравниваются пять техник Dropout для рекуррентных сетей: Variational, Gal-Ghahramani, Weight Dropout (DropConnect), Zoneout, Semeniuta.

**Часть 2 — языковая модель:** авторегрессионный LSTM-декодер с teacher forcing, beam search на инференсе.

**Стек:** `torch`, `tokenizers`, `nltk`
