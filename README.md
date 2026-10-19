# prm-licencje

Lista aktywnych kodów testowych (TEST) do PRM PAX OPERATIONS (Excel 1.4.1+).

* `aktywne_kody_testowe.txt` — jedno ID kodu w linii, `#` zaczyna komentarz.
* **Pierwszej linii (`# PRM PAX OPERATIONS ...`) nie usuwaj** — po niej Excel poznaje, że to prawdziwa lista.
* Wyłączenie kodu: usuń jego linię albo dopisz `#` na początku. Excel przestaje działać przy następnym
  sprawdzeniu (otwarcie pliku albo co 15 min; GitHub buforuje plik do ok. 5 min).
* Nowy kod: panel właściciela → firma → Licencje → typ TEST (pokazuje gotową linię) albo
  `python tools/license_tool.py issue --install '*' --site TEST --expiry NONE --type TEST --profile TEST`.

Repozytorium musi być **publiczne** — Excel czyta plik bez logowania. Są tu tylko identyfikatory (skróty SHA-256
kodów), żadnych danych ani sekretów.

© Marcel DŁUGOŁĘCKI & Eliza MACIEJCZYK — wszelkie prawa zastrzeżone.
