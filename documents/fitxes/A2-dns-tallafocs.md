# Fitxa d'activitat A2 · DNS: Servidor DNS intern i tallafocs

- **Codi i nom:** A2 - Servidor DNS intern i tallafocs
- **Incidència vinculada:** #13
- **Fita:** M0 Planificació
- **Rol assignat:** Rol B
- **Mòduls i RA implicats:** MP07 (RA2, RA3), MP06 (RA2), MP04 (RA2)
- **Durada estimada:** 12 hores (Setmana S2)

## Descripció de l'activitat
Desplegar el servidor DNS intern per resoldre els noms locals dels serveis de XarxaGym (resolucions directes i inverses) i configurar les regles del tallafocs per aplicar una política restrictiva per defecte permetent només el trànsit necessari.

## Entregables i evidències
- Configuració de zones DNS i regles de tallafocs a proves/.
- Captures de resolució (dig / 
slookup) i proves de bloqueig/permís a evidencies/.

## Instrument d'avaluació (100 %)

| Criteri d'avaluació | Pes | Evidència comprovable |
|---|---|---|
| Resolució directa i inversa operativa al servidor DNS intern | 30 % | Sortida de dig / 
slookup resolent noms interns de XarxaGym |
| Política de tallafocs restrictiva per defecte i obertura controlada de ports | 30 % | Regles actives de tallafocs revisades i auditades |
| Verificació de ports i serveis exposats des de la xarxa | 20 % | Captura de comprovació amb 
map o proves de connexió |
| Claredat documental i traçabilitat al repositori | 20 % | Fitxa completa i evidències associades a #13 |