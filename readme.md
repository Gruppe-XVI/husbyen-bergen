# Kom i gang
Finn en mappe (som regel den du har kodeprosjekt i) min heter bare `code` og ligger i hjemmappen min. Åpn en konsoll/terminal i mappen med høyreklikk og trykk på "åpn terminal/konsoll her" knappen. I vinduet som åpner taster du inn dette 
```zsh
git clone https://github.com/Gruppe-XVI/husbyen-bergen.git
```
Dette vil laste ned prosjektet i en ny mappe som vil hete `husbyen-bergen`. Åpn denne i teksteditoren din så er du basically komt i gang.

### Git Info 
- `git pull` før du begynner å jobbe
- `git add *` for å legge til endringene dine til commit
- `git commit -m "[prefix]: [melding]"` for å lage commit og lage en melding
- `git push` for å sende endringene til github og dele med alle alltid push ferdige endringer når du er ferdig med arbeid.
***!!Viktig** Hvis du jobber i samme fil som noen andre så må dere passe på at det skjer merge conflikt som er ikke veldig gøy å ordne opp i hvis det oppstår kontakt meg (@kSksip)*

## Hvordan å gjøre commits
En kort guide på hvordan vi kan strukturere commit meldinger for å forstå hva det er andre gjør på prosjektet. Inspirert av [Conventional Commits](https://www.conventionalcommits.org/en/).

### Hva er en god commit?
- en god commit har som regel en melding som forklarer godt hva som er blitt endret.
- `endret noe` er en dårlig commit melding. Den forteller deg ingenting om hva som er blitt endret eller oppdatert. Hvis du har lagt til et nytt element på en side så kan meldingen f.eks. være `feat: la til venneliste på dashboard`
- commit én og én feature, ikke commit flere features/endringer i én commit. Hvis du fikser en bug eller endrer stilen i allerede eksisterende kode commit det for seg selv. 

### Prefix(er)
- **fix:** Used when the commit fixes a bug.
- **feat:** Used when the commit introduces a new feature.  
- **style:** Used when the commit changes the visual appearance of the app.
- **refactor:** Used when the commit refactor code.
- **docs:** Used when the commit edits markdown files or general documentation
