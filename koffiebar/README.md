# Koffiebar

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 22.2.0.

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





Reflectie (README): waar kijk je eerst als een wijziging niet op het scherm verschijnt (F1.8)?
 
# -> Naar de console


Welke Angular-versie gebruikt je project precies? Wat betekent het dakje?


# het dakje betekent semantic versioning binnen die versie of hoger 
 ng version 

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/
    

Angular CLI       : 22.2.0
Angular           : 22.2.0
Node.js           : 24.21.0
Package Manager   : npm 11.19.0
Operating System  : win32 x64

┌───────────────────────────┬───────────────────┬───────────────────┐
│ Package                   │ Installed Version │ Requested Version │
├───────────────────────────┼───────────────────┼───────────────────┤
│ @angular/build            │ 22.2.0            │ ^22.2.0           │
│ @angular/cli              │ 22.2.0            │ ^22.2.0           │
│ @angular/common           │ 22.2.0            │ ^22.2.0           │
│ @angular/compiler         │ 22.2.0            │ ^22.2.0           │
│ @angular/compiler-cli     │ 22.2.0            │ ^22.2.0           │
│ @angular/core             │ 22.2.0            │ ^22.2.0           │
│ @angular/forms            │ 22.2.0            │ ^22.2.0           │
│ @angular/platform-browser │ 22.2.0            │ ^22.2.0           │
│ @angular/router           │ 22.2.0            │ ^22.2.0           │
│ rxjs                      │ 7.8.2             │ ~7.8.0            │
│ typescript                │ 6.0.3             │ ~6.0.2            │
│ vitest                    │ 5.0.2             │ ^5.0.0            │
└───────────────────────────┴───────────────────┴───────────────────┘


Waarom staat @angular/cli bij devDependencies en niet bij dependencies ?

 # dependencies zijn pakketten die we nodig hebben en de gebruiker niks heeft aan de CLI


Welk commando voert npm start uit?

# het voert de ng serve commando uit 

Welk bestand is het startpunt van de applicatie, en aan wie geeft het de controle?

# src/main.ts het startpunt: hier geeft jouw code de controle aan Angular



Wat staat er in de <body> van src/index.html ? Vergelijk in de browser View Page Source met
de Elements-tab en verklaar het verschil

# Mijn programma "start" niet. Het overhandigt zijn
# rootcomponent en zijn configuratie aan het framework, en Angular neemt het over.


wat is het opvallendste verschil met de package.json van je Express-project uit Web
Programming?

# package.json is vlotter te lezen tegenover vorig jaar 



hoe wist npm wat het moest installeren? Hoe groot is node_modules , en hoe
groot is wat de gebruiker downloadt (de kolom Estimated transfer size)? Welk soort server heb je
nodig om de inhoud van dist/ online te zetten (syllabus 1.2)?


# npm wist wat die moest installen omdat die de pckg.json leest en die exact weet wat die installed

# estimated transfer size = 52.14 kB



noem drie dingen behalve componenten die de CLI kan genereren. Wat deed
--dry-run , en wanneer is dat nuttig

# ng generate [ web-worker , service-worker, resolver ]
# het genereert een naam.ts, naam.cs en een naam.html binnenin de src/app


Schrijf de twee stappen in je eigen woorden op. Waar komt de naam apphoofding vandaan?

# app hoofding toev in app.html het werd rood omdat die import niet in de hoofding.ts geschreven stond opgelost door te auto importe apphoofding is afkomstig van de klasse aangemaakt in .ts file 


Delen de twee knoppen hun aantal? Wat zegt dat over een component en haar
state? Vergelijk met oefening 1 van labo 1: welke regel code die je daar overal moest schrijven, staat
hier nergens?




# render() die is nergens hier te vinden maar het doet hetzelfde als 



