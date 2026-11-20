# FilesReporter

**PL** | [EN](#english)

Darmowy program dla administratorów serwerów plików: pokazuje, **co zajmuje miejsce**, **czy ktoś jeszcze z tego korzysta**
i **które pliki można przenieść na tańszy nośnik**. Skanuje dyski, udziały sieciowe i wybrane foldery na jednym lub kilku
komputerach (serwery, węzły klastra), a wyniki zapisuje do PDF, Excela i CSV. Program tylko czyta – niczego na serwerach nie zmienia.

**[⬇ Pobierz najnowszą wersję](https://github.com/mayaa79/FilesReporter/releases/latest)** (`FilesReporter-Setup-<wersja>.exe`)

## Funkcje

- **Zajętość miejsca** – lista dużych plików (≥ 1 GB, ≥ 5 GB albo własny próg) z właścicielem pliku, grupowaniem po udziale,
  dysku lub komputerze, filtrami pod każdą kolumną i eksportem do Excela, PDF i CSV.
- **Wizualizacja** – diagramy elementów, typów i wieku plików oraz właścicieli; PDF dla dyrekcji.
- **Raport do archiwizacji** – duże pliki niezmieniane od 3, 6, 12 miesięcy lub własnego okresu; PDF szczegółowy albo ogólny
  (jedna strona), Excel (3 arkusze) i CSV.
- **Aktywność plików** – czy udział lub folder jest używany: werdykt Aktywny / Słabo aktywny / Nieaktywny, raport zbiorczy i szczegółowy.
- **Zapis i porównanie skanów** – wynik do pliku `.frscan`, otwarcie bez ponownego skanowania i porównanie dwóch skanów.
- **Linia poleceń** – skany i raporty bez okna (Harmonogram zadań), z opcjonalną wysyłką poczty. Pomoc: `FilesReporter.exe /help`.
- Skan wielu komputerów naraz, wybór komputerów z domeny, interfejs po polsku i angielsku, motyw ciemny i jasny.

## Wymagania

- Windows 7 SP1 / Windows Server 2008 R2 SP1 lub nowszy, 64-bit, **.NET Framework 4.8**
  (Windows 10 od wersji 1903 i Windows 11 mają go w systemie; instalator sprawdzi i podpowie).
- Konto z prawami administratora na skanowanym komputerze; przy skanie zdalnym dostęp do WMI i udziałów administracyjnych.
- PDF na Windows Server 2008 R2: Visual C++ Redistributable 2015–2022 (x64) i aktualizacja KB2999226. Excel i CSV działają bez nich.

## Autor

Marcin Majewski – [LinkedIn](https://www.linkedin.com/in/majewski-it). Program jest darmowy (freeware); licencja w instalatorze.

---

## English

**FilesReporter** is a free tool for file server administrators. It shows **what takes up space**, **whether anyone still uses it**
and **which files can be moved to cheaper storage**. It scans drives, network shares and chosen folders on one or several
computers (servers, cluster nodes) and saves the results to PDF, Excel and CSV. It is read-only – it changes nothing on your servers.

**[⬇ Download the latest version](https://github.com/mayaa79/FilesReporter/releases/latest)** (`FilesReporter-Setup-<version>.exe`)

### Features

- **Disk usage** – list of large files (≥ 1 GB, ≥ 5 GB or a custom threshold) with the file owner, grouping by share, drive or
  computer, per-column filters and export to Excel, PDF and CSV.
- **Visualization** – charts of items, file types, file age and owners; a PDF for management.
- **Archive report** – large files unchanged for 3, 6, 12 months or a custom period; detailed or summary (one page) PDF,
  Excel (3 sheets) and CSV.
- **File activity** – is a share or folder still in use: verdict Active / Weakly active / Inactive, summary and detailed reports.
- **Saving and comparing scans** – save a result to a `.frscan` file, reopen it without rescanning and compare two scans.
- **Command line** – scans and reports without a window (Task Scheduler), optional e-mail delivery. Help: `FilesReporter.exe /help`.
- Scans several computers at once, picks computers from the domain, Polish and English interface, dark and light theme.

### Requirements

- Windows 7 SP1 / Windows Server 2008 R2 SP1 or newer, 64-bit, **.NET Framework 4.8**
  (built into Windows 10 1903+ and Windows 11; the installer checks and tells you where to get it).
- An administrator account on the scanned computer; for remote scans, access to WMI and administrative shares.
- PDF on Windows Server 2008 R2: Visual C++ Redistributable 2015–2022 (x64) and update KB2999226. Excel and CSV work without them.

### Author

Marcin Majewski – [LinkedIn](https://www.linkedin.com/in/majewski-it). Free software (freeware); the license is shown in the installer.
