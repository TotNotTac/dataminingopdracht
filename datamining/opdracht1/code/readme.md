# Opdracht 1

## Setup

1. Maak een Github account
2. Okay nu moeten we een ssh key toevoegen aan je Github account (zo kan Github zien dat jouw laptop bij jouw account hoort)
   A. Open je terminal en type het volgende commando: `ssh-keygen`
   B. Laat de textinvoer leeg en klik op enter, doe hetzelfde als het om een wachtwoord vraagt.
   C. Type het volgende commando en kopieer de output: `cat .ssh/id_rsa.pub`
   D. Ga naar de volgende URL: `https://github.com/settings/keys`
   E. Klik op `new SSH key`
   D. Geef je key een leuke titel en plak wat je zojuist gekopieerd hebt in het `key` veld.
   F. Klik `Add SSH key`
3. Vind een leuke folder waar je je project op wilt slaan. (mijne staat onder ~/Documents/school/minor)
4. Open een terminal in deze folder en type het volgende commando: `git@github.com:TotNotTac/datascience_blok2.git`, laat de terminal open staan
5. Installeer Visual Studio Code
   https://code.visualstudio.com/download
6. type `code .` in de terminal die je nog open had staan
7. Nu zit je in visual studio code. Hier kan je efficient code aanpassen, data bekijken en meer.
   In de linker zijbalk staat een icoontje met 4 blokjes, klik hier op. Hier kan je nieuwe extensies zoeken en installeren.

   Download en installeer de volgende benodigde extensies:

   - Python
   - Jupyter

   De volgende extensies zijn niet perse nodig maar wel aan te raden voor een fijnere ervaring:

   - Git Graph
   - Rainbow CSV

8. Open `testSetup.ipynb` en kijk of alles werkt
