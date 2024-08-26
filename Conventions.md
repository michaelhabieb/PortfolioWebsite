# Conventies voor Portfolio opdracht.


## Inhoudsopgave
1. [Algemene Conventies](#algemene-conventies)
2. [PHP Code Conventies](#php-code-conventies)
3. [Routing Conventies](#routing-conventies)


## Algemene Conventies

- **Indentatie:** Gebruik 4 spaties voor indentatie. Vermijd tabs.
- **Lijnlengte:** Hou de regels onder ongeveer 120 tekens waar mogelijk.
- **Commentaar:** Schrijf commentaar in het Engels. Gebruik single-line (`//`) commentaar voor korte uitleg en multi-line (`/* ... */`) commentaar voor gedetailleerde uitleg.

## PHP Code Conventies

- **Openingstags:** Gebruik altijd de volledige PHP openingstag `<?php`.
- **Namespaces:** Volg PSR-4 autoloading-standaarden. Gebruik de juiste namespace voor elke klasse.
- **Klasse Namen:** Gebruik `PascalCase` voor klassenamen (bijv. `UserController`).
- **Methodenamen:** Gebruik `camelCase` voor methodenamen (bijv. `getUserProfile`).
- **Variabelen:** Gebruik `camelCase` voor variabelnamen (bijv. `$userName`).

## Routing Conventies

- **Routes:** Gebruik altijd het `web.php` bestand voor de routes.
- **Route Namen:** Gebruik altijd betekenisvolle namen voor je routes met de `name` method. Dit maakt het gemakkelijker om routes te refereren in je views en controllers. Bijvoorbeeld, in plaats van `Route::get('/projects', [ProjectController::class, 'index']);`, gebruik `Route::get('/projects', [ProjectController::class, 'index'])->name('projects.index');`.
- **Resource Controllers:** Maak gebruik van resource controllers voor CRUD-functionaliteiten. Dit zorgt ervoor dat je routes consistent en overzichtelijk blijven. Bijvoorbeeld, gebruik `Route::resource('projects', ProjectController::class);` in plaats van individuele routes voor elk CRUD-verzoek.


##  Styling Conventies

- **Font:** Gebruik altijd  `voorbeeld_text_font`  als font
- **Kleurencode:** Volg altijd het gegeven kleurenpalet
