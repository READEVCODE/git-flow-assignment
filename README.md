﻿# git-flow-assignment
# release/v1.0

We zijn begonnen met het aanmaken van de repo in github, dit heb ik gedaan door de UI te volgen van Github zelf. Na het aanmaken van de repo heb ik deze gecloned naar mijn laptop met de command git clone (URL).

Na het clonen van de repo heb ik via een command (echo "# git-flow-assignment" >> README.md) uitevoerd om het README bestand aan te maken en deze aan te vullen met de tekst "# git-flow-assignment". vervolgens heb ik dit geadd met git add en gecommit naar de main met git commit -m '..'

Na het aanmaken avn de repo ben ik begonnen met het aanmaken van de feature branch genaamd feature/add-welcome-message en hier heb ik een welcome.txt file in aangemaakt met de command (echo "Dit gaat zeker lukken met de tijd" >> welcome.txt) vervolgends geadd, gepusht en gecommit. Na het het pushen heb ik in een Github zelf een PR aangemaakt en deze is geapproved door Shaner.

Na het het aanmaken van de feauture branch ben ik het README bestand een wijziging gaan doorvoeren door er een versie aan toe te voegen. Deze wijizging heb ik vervolgend gecommit en gepusht en heb ik een PR aangemaakt voorzowel de main als de develop. Tijdens het uitvoeren van de PR kwamen we er achter dat het beter was als we het in de volgorde van eerst naar develop en dan naar main te sturen. Maar dit was een beetje onduidelijk in de opdracht en hebben dit later gecorrigeerd in de volgende opdracht.

Vervolgens heb ik een nieuwe branch aangemaakt genaamd `hotfix/fix-typo` waar ik een 'typo (tekens toegevoegd :))' ging corrigeren in mijn code, dit heb ik gedaan in de de welcome.txt bestand. deze wijziging is geadd, gecommit en gepusht 

Tot slot heb ik geoefend met Tags door de branches release en hotfix te taggen met een versie door de command git tag v1.0.1, dit zag ik vervolgens weer terug in github met de command git push origin --tags
