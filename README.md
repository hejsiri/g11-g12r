# Symulator taryf energii: G12r vs G11

Prosta aplikacja webowa do porównania szacunkowego miesięcznych kosztów energii dla taryf **G12r** i **G11**.

## Co robi projekt

- porównuje koszt miesięczny dla G12r i G11,
- pozwala ustawić miesięczne zużycie energii (kWh),
- pozwala ustawić udział zużycia w tanich godzinach G12r,
- pokazuje rozbicie opłat w tabelach dla obu taryf,
- pokazuje, która taryfa jest tańsza i o ile,
- zlicza odwiedziny strony (`licznik.php` + `licznik.txt`).

## Struktura plików

- `index.html` - interfejs aplikacji, logika obliczeń i prezentacja wyników,
- `licznik.php` - prosty licznik odwiedzin z blokadą pliku,
- `licznik.txt` - aktualna liczba odwiedzin,
- `README.md` - opis projektu.

## Uruchomienie lokalne

### Opcja 1 (pełna, z licznikiem odwiedzin) - serwer PHP

1. Otwórz terminal w katalogu projektu.
2. Uruchom:

```bash
php -S localhost:8000
```

3. Wejdź w przeglądarce na:

```text
http://localhost:8000
```

### Opcja 2 (sam `index.html`)

Możesz otworzyć `index.html` bezpośrednio w przeglądarce, ale licznik odwiedzin nie będzie działał poprawnie bez PHP.

## Publikacja na GitHub

1. W VS Code otwórz zakładkę **Source Control**.
2. Dodaj pliki do commita.
3. Wpisz wiadomość commita, np. `add README`.
4. Kliknij **Commit**.
5. Kliknij **Publish to GitHub** lub **Push** (jeśli repo już jest podpięte).

## Uwagi

Wyniki mają charakter orientacyjny i zależą od przyjętych stawek w kodzie (`index.html`).
