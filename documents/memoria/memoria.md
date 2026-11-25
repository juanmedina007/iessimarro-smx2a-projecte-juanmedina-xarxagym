# Memòria del projecte · XarxaGym - Infraestructura de xarxa i serveis per a centre esportiu

## 1. Resum executiu
Aquest projecte presenta el disseny, la planificació i l'estructura d'implantació de la infraestructura de xarxa i serveis bàsics per al centre esportiu **XarxaGym**. L'objectiu és dotar el gimnàs d'una xarxa local segmentada, assignació automàtica d'adreces IP, resolució de noms interna, portal web informatiu i mesures de seguretat i còpies de seguretat periòdiques.

## 2. Caracterització de l'organització i el repte
- **Organització destinatària:** Centre esportiu local de nova obertura (**XarxaGym**), amb plantilla inicial de 8 persones (direcció/administració, recepció i monitors) i previsió d'entre 250 i 400 socis.
- **Necessitat principal:** Absència de xarxa segmentada ni serveis centrals operatius en el local d'obertura.
- **Solució triada:** Desplegament d'infraestructura de xarxa segmentada per àrees amb serveis DHCP, DNS, servidor web corporatiu, tallafocs i còpies de seguretat automatitzades.

## 3. Arquitectura tècnica i serveis
- **Adreçament i segmentació:** Esquema IPv4 separat per departaments (administració, recepció, sala/monitors i convidats) mitjançant commutació/encaminament amb VLAN i punts d'accés WiFi.
- **Serveis de xarxa:** Servidor DHCP per a l'assignació dinàmica als clients i servidor DNS intern per a la resolució directa i inversa dels serveis locals.
- **Portal web:** Servidor web (Apache/Nginx) amb la informació del gimnàs, horaris, tarifes i contacte per als socis i usuaris interns.
- **Seguretat i còpies:** Política restrictiva al tallafocs permetent només els ports necessaris i còpies de seguretat programades de configuracions i contingut web.

## 4. Planificació, rols i seguiment
- **Rols:** Coordinació tècnica, xarxa i DHCP (**Rol A**); DNS intern i tallafocs (**Rol B**); desplegament web i documentació (**Rol C**).
- **Seguiment:** Repositori Git amb *Conventional Commits* i Refs #<incidència>, fitxes d'activitat (A1 a A4), cronograma (S1 a S5) i tauler Kanban / Roadmap en GitHub Projects.

## 5. Viabilitat econòmica i conclusions
- El pressupost detalla les partides d'equipament, xarxa, programari, materials i mà d'obra, amb comparativa tècnica i econòmica del servidor central per garantir rendiment, garantia i disponibilitat.
- El projecte és viable tècnicament i econòmicament, i queda documentat per a la seva validació i defensa oral.