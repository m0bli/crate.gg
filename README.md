# crate.gg

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 22.2.7.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.


# opis
Ogólny wygląd

Strona ma ciemny motyw w stylu gamingowych serwisów: tło w bardzo ciemnym granacie, delikatnie jaśniejsze karty i pomarańczowy akcent, którego używają przyciski i logo. Kolory rzadkości skinów są takie jak w CS2, czyli niebieski, fioletowy, różowy, czerwony i złoty, więc od razu widać, czy trafiło się coś dobrego. Całość jest czytelna i prosta, bez zbędnego bałaganu.

Górny pasek (na każdej podstronie)

Po lewej jest logo, na środku menu (Skrzynki, Ekwipunek, Upgrader, Contract, Statystyki), a po prawej Twoje saldo wirtualnych monet i przycisk do odbierania dziennej nagrody. Dzięki temu zawsze widzisz, ile masz monet, i możesz szybko przejść do dowolnej części strony.

Strona główna

Na samej górze jest duży napis zachęcający do otwierania skrzynek za darmo i informacja, że nie ma tu prawdziwych pieniędzy ani hazardu. Pod nim jest przewijany pasek z ostatnimi dropami, gdzie każdy skin ma kolorowy pasek oznaczający rzadkość. Niżej znajduje się siatka skrzynek. Każda ma swoją nazwę, cenę w monetach i przycisk "Otwórz".

Otwieranie skrzynki

Na środku ekranu jest pozioma karuzela z przesuwającymi się skinami, a pośrodku pomarańczowa linia pokazująca, na którym skinie zatrzymała się karuzela. Pod nią są trzy przyciski: zwykłe otwarcie, szybkie otwarcie bez animacji i otwarcie kilku skrzynek naraz. Na dole jest lista wszystkiego, co może wypaść z danej skrzynki, żeby wiedzieć, na co liczyć.

Upgrader

Ekran jest podzielony na trzy części. Po lewej są Twoje skiny, które możesz wrzucić do ulepszenia, a po prawej lista skinów, które chcesz zdobyć. Na środku jest duże koło z procentową szansą na sukces, a pod nim przycisk "Upgrade". Im droższy cel, tym mniejsza szansa i tym większe emocje.

Ekwipunek (w planach)

Siatka wszystkich Twoich skinów z filtrami po rzadkości, wyszukiwarką i sortowaniem. Po kliknięciu skina zobaczysz szczegóły (stan, StatTrak™, wartość) i możesz go sprzedać za monety. U góry będzie podsumowanie, ile masz przedmiotów i jaka jest ich łączna wartość.

Contract (w planach)

Tu wybierasz 10 skinów tej samej rzadkości, wrzucasz je do kontraktu i dostajesz 1 skin lepszej rzadkości.

Wersja na telefon

Menu składa się do małego przycisku, a skrzynki i skiny układają się w jednej kolumnie, więc z aplikacji można wygodnie korzystać także na telefonie.

Mogę też napisać to krócej, w wersji po angielsku albo dorobić ekrany ekwipunku i Contractu do podglądu strony.
