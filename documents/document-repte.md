# Document del Repte (Versió 3) · XarxaGym

## 1. Dades generals del projecte
- **Títol del projecte:** XarxaGym - Infraestructura de xarxa i serveis per a centre esportiu
- **Cicle formatiu:** CFGM Sistemes Microinformàtics i Xarxes (2n SMX - Grup A)
- **Autor:** Juan Medina Sanchis
- **Curs acadèmic:** 2026-2027

## 2. Descripció del repte
Dissenyar, implementar i documentar la infraestructura informàtica completa per a un gimnàs de nova obertura (XarxaGym), garantint la connectivitat interna segmentada, l'accés segur a Internet, la gestió centralitzada d'usuaris i l'allotjament d'un portal web informatiu per als socis.

## 3. Objectius específics
1. Dissenyar l'esquema d'adreçament IPv4 segmentat per departaments (administració, recepció, sala i convidats).
2. Implementar i configurar un servidor DHCP per a l'assignació dinàmica d'adreces IP als equips clients.
3. Desplegar un servidor DNS intern per a la resolució de noms dels serveis locals del gimnàs.
4. Configurar un servidor web Apache/Nginx per allotjar la pàgina web corporativa de XarxaGym.
5. Aplicar polítiques de seguretat bàsiques mitjançant tallafocs i còpies de seguretat periòdiques.

## 4. Mòduls professionals i Resultats d'Aprenentatge (RA) implicats
- **MP04 - Sistemes Operatius en Xarxa:**
  - *RA1 / RA2:* Instal·lació, configuració i administració de serveis de directori, usuaris i recursos compartits.
- **MP06 - Seguretat Informàtica:**
  - *RA2 / RA3:* Aplicació de mesures de seguretat activa i passiva, tallafocs i polítiques de còpies de seguretat.
- **MP07 - Serveis en Xarxa:**
  - *RA1 / RA2 / RA3:* Configuració i verificació de serveis DHCP, DNS i HTTP en entorns de xarxa local.
- **MP08 - Aplicacions Web:**
  - *RA1 / RA2:* Desplegament i manteniment del portal web de XarxaGym.
- **Projecte Intermodular:**
  - *RA1 / RA2:* Caracterització de l'organització i de l'empresa del sector, i anàlisi de viabilitat tècnica i econòmica.

## 5. Planificació i rols
- **Rol A (alumneA):** Coordinació tècnica, adreçament i servidor DHCP.
- **Rol B (alumneB):** Serveis de noms (DNS) i seguretat (tallafocs).
- **Rol C (alumneC):** Desplegament web i documentació tècnica.

## 6. Recursos i entorn de proves
- Virtualització mitjançant VirtualBox / Proxmox per a la simulació de servidors Linux i clients.
- Eines d'anàlisi i verificació de xarxa (Wireshark, ping, dig, nmap).
- Control de versions i gestió de tasques mitjançant GitHub i GitHub Projects.

## Criteris d'avaluació per RA

| Mòdul | RA | Criteri d'avaluació comprovable | Incidència que l'evidenciarà |
|---|---|---|---|
| MP04 · Sistemes Operatius en Xarxa | RA1 | El servidor Linux base s'instal·la sense errors, amb adreçament IP estàtic configurat i connectivitat verificada. | #13 |
| MP04 · Sistemes Operatius en Xarxa | RA2 | Els grups d'usuaris (administració, recepció, monitors) i els recursos compartits tenen permisos diferenciats i provats. | #13 |
| MP06 · Seguretat Informàtica | RA2 | El tallafocs aplica regles restrictives per defecte i permet únicament els ports necessaris (DNS, DHCP, HTTP/HTTPS, SSH). | #13 |
| MP06 · Seguretat Informàtica | RA3 | S'executa una tasca automatitzada de còpia de seguretat periòdica dels fitxers de configuració i del web corporatiu. | #16 |
| MP07 · Serveis en Xarxa | RA1 | El servidor DHCP assigna automàticament adreces IP dins del rang de cada subxarxa i registra el lloguer (*lease*) correctament. | #13 |
| MP07 · Serveis en Xarxa | RA2 | El servidor DNS intern resol tant registres directes (A/CNAME) com inversos (PTR) dels serveis interns de XarxaGym. | #13 |
| MP07 · Serveis en Xarxa | RA3 | El servei HTTP respon correctament des dels clients interns mitjançant el nom de domini intern configurat. | #13 |
| MP08 · Aplicacions Web | RA1 | El servidor web Apache/Nginx serveix el portal informatiu de XarxaGym amb estructura HTML/CSS operativa i sense errors 404/500. | #13 |
| MP08 · Aplicacions Web | RA2 | El portal web inclou els apartats d'horaris, tarifes i contacte del gimnàs, i queda documentat el procediment de desplegament. | #16 |
| Projecte Intermodular | RA1 | El plantejament inicial caracteritza l'organització destinatària, el sector i els perfils professionals de SMX implicats. | #12 |
| Projecte Intermodular | RA2 | El pressupost desglossa partides, mà d'obra, IVA i comparativa d'opcions justificant la viabilitat del projecte. | #1 |