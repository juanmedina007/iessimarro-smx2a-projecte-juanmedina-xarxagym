# Document de Repte: XarxaGym

## 1. Dades generals del projecte
* **Títol del projecte:** XarxaGym - Infraestructura de xarxa i serveis per a centre esportiu
* **Cicle formatiu:** CFGM Sistemes Microinformàtics i Xarxes (2n SMX - Grup A)
* **Autor:** Juan Medina Sanchis
* **Curs acadèmic:** 2026-2027

## 2. Descripció del repte
Dissenyar, implementar i documentar la infraestructura informàtica completa per a un gimnàs de nova obertura (XarxaGym), garantint la connectivitat interna, l'accés segur a Internet, la gestió centralitzada d'usuaris i l'allotjament d'un portal web informatiu per als socis.

## 3. Objectius específics
1. Dissenyar l'esquema d'adreçament IPv4 segmentat per departaments (administració, recepció, sala i convidats).
2. Implementar i configurar un servidor DHCP per a l'assignació dinàmica d'adreces IP als equips clients.
3. Desplegar un servidor DNS intern per a la resolució de noms dels serveis locals del gimnàs.
4. Configurar un servidor web Apache/Nginx per allotjar la pàgina web corporativa de XarxaGym.
5. Aplicar polítiques de seguretat bàsiques mitjançant tallafocs i còpies de seguretat periòdiques.

## 4. Mòduls professionals i Resultats d'Aprenentatge (RA) implicats
* **MP04 - Sistemes Operatius en Xarxa:**
  * *RA1 / RA2:* Instal·lació, configuració i administració de serveis de directori, usuaris i recursos compartits.
* **MP06 - Seguretat Informàtica:**
  * *RA2 / RA3:* Aplicació de mesures de seguretat activa i passiva, tallafocs i polítiques de còpies de seguretat.
* **MP07 - Serveis en Xarxa:**
  * *RA1 / RA2 / RA3:* Configuració i verificació de serveis DHCP, DNS i HTTP en entorns de xarxa local.
* **MP08 - Aplicacions Web:**
  * *RA1 / RA2:* Desplegament i manteniment del portal web de XarxaGym.

## 5. Planificació i rols
* **Rol A (alumneA):** Coordinació tècnica, adreçament i servidor DHCP.
* **Rol B (alumneB):** Serveis de noms (DNS) i seguretat (tallafocs).
* **Rol C (alumneC):** Desplegament web i documentació tècnica.

## 6. Recursos i entorn de proves
* Virtualització mitjançant VirtualBox / Proxmox per a la simulació de servidors Linux i clients.
* Eines d'anàlisi i verificació de xarxa (Wireshark, ping, dig, nmap).
* Control de versions i gestió de tasques mitjançant GitHub i GitHub Projects.
