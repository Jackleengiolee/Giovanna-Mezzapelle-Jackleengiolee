# Monitoraggio Resi e Logistica 2026

Progetto di analisi e monitoraggio dei resi logistici sviluppato con Microsoft Excel e Google BigQuery.

## 📋 Obiettivi
* Monitorare il flusso dei resi
* Analizzare le cause delle restituzioni
* Misurare i principali KPI logistici

## 💻 Esempio di Query SQL
```sql
SELECT 
    motivo_reso,
    COUNT(id_articolo) AS totale_articoli,
    status_merce
FROM 
    `spring-radar-514414-u4.esercizi_sql.registro_resi`
GROUP BY 
    motivo_reso, 
    status_merce
ORDER BY 
    totale_articoli DESC;
