# Metodologia de treball i seguiment · XarxaGym

## 1. Organització i rols de l'equip
El treball del projecte **XarxaGym** s'estructura sota una metodologia àgil lleugera basada en Git, GitHub Issues i GitHub Projects (tauler Kanban i vista Roadmap), amb assignació clara de responsabilitats:
- **Rol A (Coordinació tècnica, xarxa i DHCP):** Planificació general, disseny IPv4/VLAN, servidor DHCP, còpies de seguretat i seguiment del repositori.
- **Rol B (Serveis de noms i seguretat):** Configuració del servidor DNS intern, polítiques de tallafocs, verificació de ports i auditories bàsiques.
- **Rol C (Desplegament web i documentació):** Posada en marxa del portal web corporatiu de XarxaGym, proves d'accés i suport documental.

## 2. Convenció de commits i referències a incidències
- Tots els canvis es pugen a la branca principal mitjançant **Conventional Commits** en minúscules i sense punt final:
  - docs (<àmbit>): <descripció breu>
  - eat (<àmbit>): <descripció breu>
  - ix (<àmbit>): <descripció breu>
  - chore (<àmbit>): <descripció breu>
- Cada commit vinculat a una tasca o fase inclou Refs #<número> al cos del missatge per mantenir la traçabilitat completa sense tancar incidències de forma automàtica abans de la validació.

## 3. Flux al tauler Kanban i gestió d'incidències
El tauler Kanban compta amb quatre columnes per reflectir l'estat real de cada incidència:
1. **Todo:** Tasques o fases pendents d'iniciar.
2. **In Progress:** Tasca o fase activa en desenvolupament en el moment actual.
3. **In Review:** Entrega o fase pujada i pendent de revisió/validació per part del professorat.
4. **Done:** Tasca o fase validada i tancada formalment.

## 4. Revisió, evidències i diari del grup
- Cada entrega de fase es marca amb una etiqueta anotada (p4-fase1, p4-fase2, p4-fase3, p4-fase4, p4-fase5, p4-fase6) i s'acompanya d'un comentari a la incidència corresponent.
- Les captures de pantalla, sortides de comandaments i proves de verificació s'organitzen localment per a la seva revisió i incorporació a la memòria final.
- El seguiment setmanal de decisions, incidències i avenços queda registrat en el diari de treball del grup i a les fitxes d'activitat (documents/fitxes/).