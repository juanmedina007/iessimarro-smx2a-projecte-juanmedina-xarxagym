# Cronograma del projecte · XarxaGym

## 1. Dades generals i fites de referència
- **Projecte:** XarxaGym - Infraestructura de xarxa i serveis per a centre esportiu
- **Fita de planificació (M0 Planificació):** Inici 09/11/2026 · Data límit 22/12/2026
- **Fita de tancament (M3 Tancament i defensa):** Inici 15/02/2027 · Data límit 26/02/2027
- **Incidència de fase:** #14

## 2. Planificació prevista (Setmanes S1 - S5)

| Setmana | Periode previst | Activitat / Tasca clau | Rol responsable | Estat previst |
|---|---|---|---|---|
| **S1** | 09/11/2026 - 15/11/2026 | **A1:** Disseny IPv4, segmentació VLAN i servidor DHCP | Rol A | Planificada |
| **S2** | 16/11/2026 - 22/11/2026 | **A2:** Servidor DNS intern i regles de tallafocs | Rol B | Planificada |
| **S3** | 23/11/2026 - 29/11/2026 | **A3:** Desplegament del portal web corporatiu de XarxaGym | Rol C | Planificada |
| **S4** | 30/11/2026 - 06/12/2026 | **A4:** Còpies de seguretat automatitzades i verificació integral | Rol A | Planificada |
| **S5** | 07/12/2026 - 22/12/2026 | Revisió global d'evidències, ajustos finals i tancament de M0 | Rol A / Equip | Planificada |

## 3. Dependències entre activitats
- **A1 -> A2:** Cal tenir definides les subxarxes IPv4 i l'adreçament base de la xarxa per configurar correctament les zones DNS i les regles del tallafocs.
- **A1 i A2 -> A3:** El servidor web de XarxaGym necessita connectivitat IP operativa i resolució de noms interna per ser accessible des dels equips del centre.
- **A1, A2 i A3 -> A4:** Les còpies de seguretat periòdiques i les proves de connectivitat/restauració s'apliquen sobre la xarxa, el DNS, el tallafocs i el portal web ja configurats.

## 4. Tauler Kanban i vista Roadmap (GitHub Projects)
- **Tauler de treball:** GitHub Projects vinculat al repositori iessimarro-smx2a-projecte-juanmedina-xarxagym amb les 4 columnes (*Backlog / Pendent*, *En curs*, *En revisió*, *Fet*) i dates d'inici/fi.
- **Vista Roadmap:** Configurada per fer el seguiment temporal de les incidències i fites del projecte.