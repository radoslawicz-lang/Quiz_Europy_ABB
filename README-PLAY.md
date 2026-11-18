# Google Play AAB, Quiz Europy 1.3.3

Projekt nadal buduje APK testowe, ale ma też workflow `.github/workflows/build-aab.yml` tworzący podpisany pakiet AAB do Play Console.

## Wymagane sekrety GitHub
Dodaj KEYSTORE_BASE64, KEYSTORE_PASSWORD, KEY_ALIAS oraz KEY_PASSWORD zgodnie z osobnym plikiem `DANE_DO_GITHUB_SECRETS.txt`.

## Budowanie
Actions > Zbuduj AAB do Google Play > Run workflow.
Pobierz artefakt `Quiz-Europy-AAB-Google-Play-v1.3.3`.

## Ważne
- applicationId: pl.quiz.europa
- versionCode: 8
- versionName: 1.3.3
- targetSdk / compileSdk: 36
- minSdk: 26
- plik AAB jest podpisany kluczem upload; zachowaj klucz do kolejnych aktualizacji.
