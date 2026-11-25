# Fitxa d'activitat A1 · Xarxa: Disseny IPv4, VLAN i servidor DHCP

- **Codi i nom:** A1 - Disseny IPv4, VLAN i servidor DHCP
- **Incidència vinculada:** #13
- **Fita:** M0 Planificació
- **Rol assignat:** Rol A
- **Mòduls i RA implicats:** MP07 (RA1, RA3), MP04 (RA1)
- **Durada estimada:** 12 hores (Setmana S1)

## Descripció de l'activitat
Definir l'esquema d'adreçament IPv4 segmentat per àrees del gimnàs XarxaGym (administració, recepció, sala/monitors i convidats), configurar l'encaminament/VLAN i desplegar el servidor DHCP per a l'assignació automàtica d'adreces IP, màscara, porta d'enllaç i DNS.

## Entregables i evidències
- Esquema d'adreçament i taula de subxarxes a documents/planols/ o proves/.
- Fitxers de configuració del servei DHCP i captures de verificació a proves/ i evidencies/.

## Instrument d'avaluació (100 %)

| Criteri d'avaluació | Pes | Evidència comprovable |
|---|---|---|
| Disseny coherent de subxarxes IPv4 i segmentació per departaments sense solapaments | 25 % | Taula IPv4 i esquema de xarxa verificats |
| Configuració correcta del servidor DHCP (àmbits, *lease time*, *gateway* i opcions) | 30 % | Fitxer de configuració DHCP i inici del servei sense errors |
| Assignació automàtica i correcta als equips client de prova | 25 % | Captura d'assignació IP (ip a / dhclient / ipconfig) i connectivitat |
| Documentació i ordre del procediment al repositori | 20 % | Fitxa completa i commits vinculats a #13 |