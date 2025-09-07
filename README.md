# GameControl

Plugin stworzony z myślą o serwerach FFA.  
Pozwala w prosty sposób tworzyć i edytować kity przez GUI oraz rozdawać je graczom.  
Wszystkie kity zapisywane są w pliku `kits.yml`, dzięki czemu pozostają po restarcie i reloadzie serwera.

---

## Funkcje
- Tworzenie nowych kitów w GUI (`/gamecontrol kit stworz <nazwa>`)
- Edycja istniejących kitów (`/gamecontrol kit edytuj <nazwa>`)
- Nadawanie kitów graczowi lub wszystkim online (`/gamecontrol kit nadaj ...`)
- Zapisywanie kitów w pliku `kits.yml`
- Tab-complete dla komend
- Alias `/game` jako skrót do `/gamecontrol`

---

## Komendy

### `/gamecontrol help`
Wyświetla listę wszystkich dostępnych komend.

### `/gamecontrol kit stworz <nazwa>`
Tworzy nowy kit i otwiera GUI, w którym można ułożyć przedmioty.  
Po zamknięciu okna kit zostaje zapisany.

### `/gamecontrol kit edytuj <nazwa>`
Otwiera edytor istniejącego kita.  
Zawartość GUI odpowiada temu, co jest zapisane w pliku, a po zamknięciu zmiany są zapisywane.

### `/gamecontrol kit nadaj <nazwa> <nick>`
Nadaje wybrany kit podanemu graczowi.

### `/gamecontrol kit nadaj <nazwa> wszyscy`
Nadaje wybrany kit wszystkim graczom online.

---

## Pliki
- `kits.yml` – automatycznie tworzony plik, w którym przechowywane są wszystkie kity.

---

## Instalacja
1. Pobierz najnowszą wersję pluginu.
2. Wrzuć plik `.jar` do folderu `plugins` na serwerze Spigot/Paper.
3. Uruchom lub zrestartuj serwer.
4. Stwórz swój pierwszy kit poleceniem `/gamecontrol kit stworz <nazwa>`.

---

## Wymagania
- Serwer **Spigot** lub **Paper** w wersji 1.16 – 1.20+
- Java 17+ (zalecane)

---

**Autor:** Dulerek
