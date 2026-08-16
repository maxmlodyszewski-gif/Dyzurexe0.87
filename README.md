# DYŻUR.exe PWA - Instrukcja publikacji na GitHub Pages

Oto gotowy pakiet plików Twojej gry przygotowany do działania jako aplikacja (PWA) na iOS, Androidzie i komputerach!

## Krok 1: Wgranie plików na GitHub
1. Zaloguj się na swoje konto na [GitHubie](https://github.com/).
2. Stwórz nowe repozytorium (przycisk **"New"**), nazwij je np. `dyzur-exe`. Zaznacz, że ma być **Public**.
3. Kliknij **"uploading an existing file"** na stronie głównego widoku nowo utworzonego repozytorium.
4. Przeciągnij i upuść **wszystkie pliki** z tego folderu (nie wgrywaj folderu w folderze, pliki m.in. `index.html` muszą być luzem).
5. Kliknij zielony przycisk **"Commit changes"**.

## Krok 2: Uruchomienie GitHub Pages
1. W swoim repozytorium na GitHubie wejdź w zakładkę **"Settings"** (Ustawienia).
2. W menu po lewej stronie wybierz **"Pages"**.
3. W sekcji **"Build and deployment"** pod opcją **"Source"** wybierz `Deploy from a branch`.
4. Pod spodem, pod nagłówkiem **"Branch"** wybierz `main` z rozwijanej listy i kliknij przycisk **"Save"**.
5. Poczekaj kilka minut! GitHub właśnie publikuje Twoją grę.
6. Na samej górze sekcji "Pages" pojawi się po chwili informacja z linkiem do gry, np. `https://twoj-nick.github.io/dyzur-exe/`. 
7. Wyślij ten link graczom! (Szczególnie użytkownikom iOS).

## Instalacja na iPhone (iOS)
Gracze na iPhonie muszą wykonać poniższe kroki by gra działała jak pełnoprawna aplikacja i zapisywała stan gry:
1. Otwórz wygenerowany przez GitHuba link w przeglądarce **Safari**.
2. Na dolnym pasku przeglądarki Safari kliknij ikonkę udostępniania (kwadrat ze strzałką do góry).
3. Wybierz opcję **"Do ekranu początkowego" (Add to Home Screen)**.
4. Kliknij "Dodaj" w prawym górnym rogu.

Gra pojawi się na pulpicie smartfona. Po jej otwarciu z poziomu ikonki odpali się ona na pełnym ekranie w dedykowanym widoku bez pasków Safari i będzie działać nawet offline!
