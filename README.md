[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tKFkieDb)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23143834)
﻿# DAFE1000-oblig-template

<Replace with full name and OsloMet email address>


For å finne maksimalpunktet/toppunktet for funksjonen: f(x) = e**(-x/4) * tan**-1(x), må vi derivere den og finne ut hva x er nå derivasjonen er null. Dette er på grunn av at når derivasjonen er lik null er det ikke endring i grafen, som betyr det er toppunktet. 

Vi kan også først derivere funksjonen. Så samler vi e**(-x/4) og setter det lik 0. Siden e**(-x/4) ikke kan være null kan vi krysse den ut. Så ganger vi alt med 4, så får vi tan**-1(x) - 4/(x**2 + 1): [Papir](Bilder/Papir_utregning.png) , det skal stå minus istedenfor pluss i papiret.

For å finne derivasjonen i python kan vi bruke definisjonen av derivasjon: (f(x + h) - f(x)) / h.

Da bruker vi newtons metode for å tilnærme oss til nullpunktet til derivasjonen f'(x), med formelen x_n = x_n-1 - f'(x)/f''(x).

Vi får da x verdien 1.6907 som er lik geogebra sin utregning: [Geogebra](Bilder/f'(x)=0.png)
Setter vi det inn i f(x) får vi at toppunktet er 0,6793. Setter disse verdiene i matplotlib og plotter verdiene.



