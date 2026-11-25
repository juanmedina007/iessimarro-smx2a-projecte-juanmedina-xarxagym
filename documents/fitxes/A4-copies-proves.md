# Fitxa d'activitat A4 · Còpies: Còpies de seguretat automatitzades i verificació

- **Codi i nom:** A4 - Còpies de seguretat automatitzades i verificació
- **Incidència vinculada:** #13
- **Fita:** M0 Planificació
- **Rol assignat:** Rol A
- **Mòduls i RA implicats:** MP06 (RA3), MP07 (RA3), MP04 (RA2)
- **Durada estimada:** 8 hores (Setmana S4)

## Descripció de l'activitat
Implementar una estratègia de còpies de seguretat periòdiques dels fitxers de configuració dels serveis i del portal web de XarxaGym, i realitzar una bateria de proves integrals de connectivitat i restauració.

## Entregables i evidències
- Script o programació de còpies de seguretat i pla de proves a proves/.
- Registres d'execució de còpies i proves de restauració a evidencies/.

## Instrument d'avaluació (100 %)

| Criteri d'avaluació | Pes | Evidència comprovable |
|---|---|---|
| Automatització de les còpies de seguretat periòdiques | 30 % | Programació activa (cron / systemd timer) i script funcional |
| Prova real de restauració de dades/configuració sense pèrdues | 30 % | Evidència de recuperació correcta d'un fitxer de prova |
| Verificació global de la xarxa i dels serveis desplegats | 20 % | Resultat de proves de connectivitat i diagnòstic |
| Coherència amb el repte, el pressupost i la resta de fitxes | 20 % | Fitxa completa i vinculada a #13 |