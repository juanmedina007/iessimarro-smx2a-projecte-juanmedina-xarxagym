# Fase 1 · Plantejament inicial: XarxaGym - Infraestructura de xarxa i serveis per a centre esportiu

## Necessitat detectada
El nou centre esportiu **XarxaGym** obri les seues instal·lacions sense cap infraestructura informàtica ni de xarxa desplegada. Actualment no disposa d'una xarxa local segmentada que separe el trànsit intern d'administració i recepció del trànsit dels socis i convidats, ni tampoc de serveis interns centralitzats (assignació automàtica d'adreces IP, resolució de noms local, gestió d'usuaris, portal web informatiu o polítiques de seguretat i còpies de seguretat). Resolent aquesta necessitat s'assegura l'operativitat diària del gimnàs, la protecció de les dades de gestió i una connexió estable i segura per a treballadors i clients.

## Idees inicials
| # | Idea | Necessitat que resol (qui i per què) | Mòduls implicats |
|---|---|---|---|
| 1 | **Infraestructura de xarxa segmentada i serveis centrals (XarxaGym)** | Resol la manca de connectivitat estructurada, seguretat i serveis interns (DHCP, DNS, web corporatiu, tallafocs i còpies de seguretat) per a l'equip gestor, recepció i socis del gimnàs. | MP04, MP06, MP07, MP08 |
| 2 | **Sistema de control d'accés biomètric i gestió de torns per a sala** | Permet controlar l'aforament i l'accés dels socis mitjançant terminals connectats a una base de dades local per a la direcció i recepció del centre. | MP04, MP06, MP08 |
| 3 | **Plataforma de reserva de classes dirigides i seguiment d'entrenaments** | Facilita als socis la reserva en línia d'activitats dirigides i als monitors la planificació de sessions des de tauletes connectades a la xarxa del centre. | MP07, MP08 |

## Idea triada i justificació
S'ha triat la **Idea 1: Infraestructura de xarxa segmentada i serveis centrals (XarxaGym)**. ÉS la base indispensable sobre la qual funciona qualsevol servei digital futur del centre esportiu: garanteix la segmentació IPv4 per departaments (administració, recepció, sala i convidats), automatitza la configuració de xarxa amb DHCP i DNS interns, proporciona presència informativa mitjançant un servidor web propi i protegeix el sistema amb tallafocs i còpies de seguretat periòdiques. A més, és plenament viable tècnicament i econòmicament per a ser implementada i verificada en un entorn virtualitzat i simulat dins de les 5 setmanes previstes.

## Organització destinatària
* **Tipus d'organització:** Empresa privada del sector esportiu, del fitnes i de la salut (centre esportiu local de nova obertura **XarxaGym**).
* **Activitat principal:** Prestació de serveis d'entrenament en sala de musculació i càrdio, activitats dirigides, assessorament esportiu i gestió d'abonaments de socis.
* **Persones i organització interna:** Plantilla inicial de 8 treballadors organitzada en tres àrees: Direcció i Administració (2 persones), Recepció i Atenció al Client (2 persones) i Monitors de Sala i Activitats (4 persones), donant servei a una previsió d'entre 250 i 400 socis actius.
* **Situació informàtica actual:** En tractar-se d'un local de nova obertura, només es compta amb l'alta d'accés a Internet de l'operador (router bàsic) i els equips d'escriptori adquirits per a recepció i administració, però sense cablejat estructurat per zones, sense segmentació de xarxa, sense servidors locals ni mesures de seguretat o còpies de seguretat configurades.

## Empresa que executaria el projecte
* **Tipus d'empresa del sector:** Empresa de serveis informàtics, integració de xarxes locals i manteniment de sistemes per a petites i mitjanes empreses (pimes).
* **Serveis que ofereix:** Disseny i desplegament de xarxes locals cablejades i sense fil, instal·lació i administració de servidors Linux/Windows, configuració de serveis de xarxa (DHCP, DNS, HTTP/HTTPS), seguretat perimetral (tallafocs), sistemes de còpia de seguretat i suport tècnic preventiu i correctiu.
* **Perfils professionals de SMX implicats:**
  * **Tècnic/a en instal·lació i manteniment de xarxes locals:** encarregat del disseny de l'esquema IPv4, segmentació per àrees, configuració d'encaminament i servei DHCP.
  * **Tècnic/a en administració de sistemes i seguretat:** responsable de la configuració dels servidors Linux, servei DNS intern, regles de tallafocs i política de còpies de seguretat.
  * **Tècnic/a en desplegament d'aplicacions web i suport:** encarregat de la posada en marxa del servidor web Apache/Nginx, proves de connectivitat i documentació tècnica per al client.

## Mòduls i RA preliminars
* **MP04 · Sistemes Operatius en Xarxa:** RA1 i RA2 (instal·lació, configuració i administració de sistemes operatius en xarxa, gestió d'usuaris i recursos compartits).
* **MP06 · Seguretat Informàtica:** RA2 i RA3 (implantació de mesures de seguretat activa i passiva, configuració de tallafocs i automatització de còpies de seguretat).
* **MP07 · Serveis en Xarxa:** RA1, RA2 i RA3 (configuració, administració i verificació dels serveis DHCP, DNS i HTTP en entorns de xarxa local).
* **MP08 · Aplicacions Web:** RA1 i RA2 (desplegament, configuració i manteniment del portal web corporatiu de XarxaGym).
* **Projecte Intermodular:** RA1 i RA2 (caracterització de l'organització destinatària i de l'empresa del sector, i anàlisi de viabilitat tècnica i econòmica).

## Viabilitat inicial
* **Temps estimat:** 5 setmanes d'execució tècnica (S1 a S5, de l'11/01/2027 al 12/02/2027), precedides per la fase de planificació i seguides pel tancament, proves finals i memòria.
* **Pressupost aproximat:** Entre 1.400 € i 1.900 € (IVA no inclòs), contemplant un servidor dedicat de gamma d'entrada o mini-PC servidor, commutador gestionable, punts d'accés WiFi professionals, cablejat/material auxiliar i les hores de mà d'obra tècnica.
* **Equipament i programari necessari:** Servidor Linux (Ubuntu Server / Debian), equips client de recepció i administració, encaminador/tallafocs, commutador amb suport VLAN, punts d'accés sense fil, servidor web Apache/Nginx i entorn de simulació/virtualització (VirtualBox / Proxmox i eines de diagnòstic com Wireshark, dig i nmap).

## Validació del professorat
*(Pendent de revisió i validació per part del professorat)*