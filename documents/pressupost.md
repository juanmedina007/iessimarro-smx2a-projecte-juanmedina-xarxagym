# Pressupost del projecte · XarxaGym

## 1. Desglossament econòmic per capítols

| Capítol | Concepte / Partida | Quantitat | Preu unitari (sense IVA) | Import (sense IVA) | Font / Proveïdor |
|---|---|---:|---:|---:|---|
| **Equipament** | Mini-PC Servidor Intel Core i5 (16 GB RAM, SSD NVMe 512 GB) | 1 | 389,00 € | 389,00 € | PcComponentes |
| **Equipament** | SAI (Sistema d'Alimentació Ininterrompuda) 900 VA | 1 | 84,99 € | 84,99 € | Amazon Business |
| **Xarxa** | Encaminador / Tallafocs amb suport VLAN (TP-Link Omada ER605) | 1 | 59,90 € | 59,90 € | PcComponentes |
| **Xarxa** | Commutador gestionable Gigabit 16 ports amb VLAN (TP-Link TL-SG1016DE) | 1 | 79,99 € | 79,99 € | Amazon Business |
| **Xarxa** | Punt d'accés WiFi 6 de sostre amb suport multi-SSID (TP-Link EAP610) | 2 | 94,90 € | 189,80 € | PcComponentes |
| **Programari** | Sistema Operatiu Servidor (Ubuntu Server 24.04 LTS) i serveis (ISC DHCP, BIND9, Nginx, UFW) | 1 | 0,00 € | 0,00 € | Programari lliure (Canonical / Open Source) |
| **Materials** | Bobina cable UTP Cat 6 (100 m) + connectors RJ45 + canaleta | 1 | 68,50 € | 68,50 € | Leroy Merlin / Cablematic |
| **Materials** | Armari rack mural 19" 6U + regleta PDU 6 preses | 1 | 92,00 € | 92,00 € | PcComponentes |
| **Mà d'obra** | Rol A · Disseny IPv4, configuració d'encaminament, VLAN i servidor DHCP | 12 h | 22,00 €/h | 264,00 € | Tarifa tècnic SMX |
| **Mà d'obra** | Rol B · Desplegament servidor Linux, DNS intern, tallafocs i còpies de seguretat | 12 h | 22,00 €/h | 264,00 € | Tarifa tècnic SMX |
| **Mà d'obra** | Rol C · Desplegament servidor web, proves de xarxa i documentació tècnica | 10 h | 22,00 €/h | 220,00 € | Tarifa tècnic SMX |

## 2. Resum total

| Concepte | Import |
|---|---:|
| **Base imposable (subtotal sense IVA)** | **1.712,17 €** |
| **IVA (21 %)** | **359,56 €** |
| **TOTAL PRESSUPOST (IVA inclòs)** | **2.071,73 €** |

## 3. Comparativa de la partida principal (Servidor central)

Per a la partida principal d'equipament (el servidor encarregat d'allotjar els serveis DHCP, DNS, portal web i còpies de seguretat), s'han comparat dues alternatives:

| Criteri | Opció A (Triada): Mini-PC Servidor Intel i5 (16 GB RAM / 512 GB NVMe) | Opció B (Descartada): Mini-PC bàsic Intel N100 (8 GB RAM / 256 GB SSD) |
|---|---|---|
| **Proveïdor** | PcComponentes | Marketplace genèric (importació) |
| **Preu (sense IVA)** | 389,00 € | 219,00 € |
| **Garantia i suport** | 3 anys de garantia oficial a Espanya i substitució en 24-48 h | 1 any de garantia limitada sense suport tècnic directe |
| **Termini d'entrega** | 24-48 hores laborables | Entre 10 i 15 dies laborables |
| **Capacitat d'ampliació** | Ampliable fins a 32 GB RAM i segon disc per a còpies locals | RAM soldada sense possibilitat d'ampliació |

**Justificació de l'elecció:** Tot i que l'**Opció B** és 170 € més barata, s'ha descartat perquè la memòria RAM soldada de 8 GB limita el creixement futur del centre esportiu (nous serveis com control d'accés o bases de dades de socis) i el termini d'entrega de fins a dues setmanes posa en risc el cronograma d'implantació. L'**Opció A** ofereix millor rendiment sostingut, marge d'ampliació, garantia oficial de 3 anys a Espanya i disponibilitat immediata.