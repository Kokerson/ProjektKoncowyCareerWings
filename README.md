# Aplikacja do Analizy Rynku AI

Aplikacja webowa przetwarzająca dane CSV i generująca kompleksowe raporty rynkowe z wykresem. Posiada moduł czatu z asystentem finansowym. Zabezpieczona (Talisman, limiter, bcrypt).

## Uruchomienie lokalne
1. `git clone <twoje-repo>`
2. `python -m venv venv`
3. Aktywuj venv i wpisz: `pip install -r requirements.txt`
4. Utwórz plik `.env` z `ANTHROPIC_API_KEY` oraz `SECRET_KEY`.
5. Uruchom: `python app.py`