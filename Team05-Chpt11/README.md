# DA382A Projektarbete i NetLogo
 
Hej allihopa!

Lite grejer för att detta ska fungera hyfsat smärtfritt.

Det viktigaste är kommunikation, förstår man inte, är man osäker på något, så säger man till. Tills dess att man får ett klart besked.
### Viktiga tre regler
- Vi rör inte main-branchen!
- Vi rör absolut inte main-branchen när vi programmerar funktioner.
- Vi rör inte main-branchen enskilt, utan tillsammans när vi fått en viss del att fungera.

Min (Davids) tanke är att vi skapar egna brancher (per grupp) för att utveckla vår tilldelade funktionalitet, och endast gör en merge med main när det fungerar fläckfritt.
När man känner att den specifika funktionen/uppgiften är klar så hämtar jämför man med senaste main versionen och bugfixar om det behövs. Man kan sedan be Gion att slå ihop brancherna.


Man kan också tänka sig att en fork från en grupps branch kan vara lämplig för att smidigare jobba som innan med enskilda gruppen. (Detta blir det inte, det blir troligtvis parprogrammering eller sub-branches.

```
exempel-struktur

main-branch
        |_ taskXX_branch
        |               |_ gruppmedlem1-branch
        |               |_ gruppmedlem2-branch
        |_ taskXY-branch
                        |_ gruppmedlem1-branch
```


## En förklaring av branches på mitt förslag
1. Main Branch: Stable, integrering hit sker endast när något fungerar fullständigt och förslagsvis i någon slags ordning där till exempel tidshantering är viktigt att få på plats innan vi går ut och äter på restaurang på kvällen.
2. Task Branch: För varje uppgift vi får bör en branch skapas ämnad för just den funktionen.
Example: *task-11A(-environment-setup)*, *task-XXb(-agent-communication)*
3. Indivduella Branches: Varje gruppmedlem har sedan en egen branch för sin bekärda del av kodningen (alternativt (lättare) parprogrammering).
Example: *john-environment-trees*, *lisa-environment-water*

4. Backup Branch: DENNA RÖR VI EJ!


Vi jobbar sedan uppåt igen. En enskild task färdig -> hämta main. När allt är fungerande i task-branch med den hämtade main -> merge till main.


Finns för frågor och tack på förhand innan röran börjar, 
David P.

