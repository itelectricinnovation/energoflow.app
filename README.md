# Energoflow.app

Energoflow.app to aplikacja do monitorowania i zarządzania przepływem energii (prototyp). Ten README zawiera instrukcje jak uruchomić projekt lokalnie, informacje o funkcjach oraz wskazówki dla kontrybutorów.

## Funkcje
- Monitorowanie zużycia energii w czasie rzeczywistym
- Wizualizacje zużycia i generacji
- Alerty i raporty okresowe
- API do integracji z zewnętrznymi systemami

## Stos technologiczny
- Frontend: (np. React / Vue / Svelte) — dopasuj do aktualnej implementacji
- Backend: (np. Node.js / NestJS / Django) — dopasuj do aktualnej implementacji
- Baza danych: (np. PostgreSQL, SQLite)

> Uwaga: Zaktualizuj powyższe sekcje o dokładne technologie użyte w repozytorium, jeśli są inne.

## Szybki start (development)

1. Sklonuj repozytorium:

```bash
git clone https://github.com/itelectricinnovation/energoflow.app.git
cd energoflow.app
```

2. Zainstaluj zależności (przykład używa npm):

```bash
npm install
```

3. Skonfiguruj zmienne środowiskowe:

- Skopiuj przykładowy plik .env.example do .env i wypełnij wartości

```bash
cp .env.example .env
# edytuj .env zgodnie z potrzebami
```

4. Uruchom aplikację w trybie deweloperskim:

```bash
npm run dev
```

5. Aplikacja powinna być dostępna pod: http://localhost:3000 (lub innym portem, sprawdź konfigurację)

## Testy

Uruchom testy (jeśli dostępne):

```bash
npm test
```

## Wdrażanie

- Zbuduj aplikację: `npm run build`
- Wdrażaj na wybranej platformie (Vercel, Netlify, Heroku, Docker, itp.)

## Contributing

1. Forkuj repozytorium
2. Stwórz branch: `git checkout -b feature/nazwa-funkcji`
3. Zrób commit: `git commit -m "Add: opis zmiany"`
4. Push: `git push origin feature/nazwa-funkcji`
5. Otwórz pull request

Proszę dodać szczegóły implementacyjne i wymagania w issue przed większymi zmianami.

## License

Dodaj plik LICENSE lub zaktualizuj tę sekcję zgodnie z licencją projektu (np. MIT).

## Kontakt

itElectric Innovation — https://github.com/itelectricinnovation

---

Jeśli chcesz, mogę:
- dopasować README do rzeczywistego stosu technologicznego obecnego w repozytorium (podaj proszę, jakie technologie są użyte albo pozwól, że sprawdzę pliki projektu),
- dodać badge (build, coverage, license),
- utworzyć plik LICENSE wraz z treścią (np. MIT).