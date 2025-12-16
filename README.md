# SP4-IDS-Light
⸻

SP4-IDS-Light er et letvægts Intrusion Detection System (IDS) udviklet i Java. Systemet er designet som et simpelt konsolprogram, der analyserer logdata og genererer alerts, som kan bruges til efterfølgende analyse af sikkerhedshændelser.
⸻

Formål

Formålet med SP4-IDS-Light er at:

	opdage mistænkelig adfærd baseret på simple regler
	gemme og vise trusler, så visse hændelser kan analyseres.
	fungere som et fundament, der senere kan udvides med flere regler og logtyper

Funktionelle krav

Systemet opfylder følgende funktionelle krav:

1. Visning af tidligere trusler
   
Systemet kan give en liste over tidligere genererede trusler.
Dette gør det muligt at analysere hændelser efterfølgende og skabe overblik over, hvad der er sket i systemet.

Trusler gemmes under kørsel via en csv-fil og kan vises via konsollen.

2. Simpelt og forståeligt system
   
Systemet er designet til at være let at anvende og forstå:
	•	output præsenteres klart i konsollen
	•	fokus er på grundlæggende IDS-funktionalitet frem for komplekse sikkerhedsmekanismer

4. Konsolbaseret program
   
SP4-IDS-Light kører udelukkende som et konsolprogram:
	•	ingen grafisk brugerflade
	•	egnet til køre, at køre på en arbejdesplads.

5. Opfanger
   
 •	Log in's ude for et bestemt tidsrum
 •  For mange mislykket login forsøg (Bruteforce)
 •  Sletning i fil linjer
 • Bliver ovenstående opfanget bliver brugeren låst


6. Teknologi

 <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="32"/>
   Sprog: Java
   
   Kørselsform: Konsolapplikation

Projektstatus

SP4-IDS-Light er et studieprojekt og skal betragtes som et proof-of-concept snarere end et produktionsklart IDS.
