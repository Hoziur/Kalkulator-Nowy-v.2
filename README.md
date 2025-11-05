# Kalkulator Wyceny Kuchni – Windows (.exe)

**Jak użyć (bez instalowania czegokolwiek lokalnie):**
1. Wgraj zawartość tego folderu do nowego repo na GitHub (przez **Upload files**).
2. Wejdź w zakładkę **Actions** i uruchom **Windows EXE build** (Run workflow).
3. Po zakończeniu pobierz plik z **Artifacts** → `Kalkulator-Windows-Installer` (ZIP) → w środku jest `Kalkulator-Wyceny-Kuchni-Setup-1.0.0.exe`.

**Lokalnie (opcjonalnie):**
```bash
npm install
npm run dev      # okno Electron w dev
npm run dist     # generuje instalator .exe (NSIS)
```