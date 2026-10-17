# Procedura sperimentale: calore specifico e calore latente di fusione del ghiaccio

Corso di Termodinamica e Laboratorio

Foglio di raccolta dati associato: `Raccolta_dati_calore_specifico_latente.xlsx`

## 1. Scopo

- Misurare il calore specifico di quattro materiali (ipoteticamente alluminio, ottone, okite, granito).
- Misurare il calore latente di fusione del ghiaccio.

## 2. Formule di riferimento

Temperatura di equilibrio di due corpi in contatto termico, senza scambi con l'esterno:

```
c1 m1 (Tf - T1) = c2 m2 (T2 - Tf)                                   (1)
```

Calore specifico del blocchetto (con massa equivalente `Me` del thermos, `ca = 1 cal/gK`):

```
c1 = ca (ma + Me)(Ta - Tf) / [ m1 (Tf - T1) ]                       (3)
```

Calore latente del ghiaccio (`Tg = 0 °C`):

```
λg = ca [ (ma + Me)(Ta - Tf) - mg (Tf - Tg) ] / mg                  (4)
```

Massa equivalente del thermos:

```
Me = m2 (T2 - Tf) / (Tf - T1) - m1                                  (da 1)
```

Si assume `Me = (25 ± 5) g`, se non misurata.

## 3. Apparato

- due thermos
- bilancia digitale
- due termometri
- bollitore elettrico
- quattro blocchetti (alluminio, ottone, okite, granito) con filo
- ghiaccio

## 4. Prima di iniziare

1. Aprire il foglio Excel e controllare il foglio **Parametri**: `ca`, `Me`, incertezza di `Me`, risoluzione di bilancia e termometri.
2. Annotare la risoluzione reale della bilancia e dei termometri e aggiornare le incertezze in **Parametri**.
3. Pesare i thermos vuoti (con tappo se si pesano chiusi, in modo coerente per tutte le misure) e annotare le masse.
4. Pesare ciascun blocchetto (`m1`) e riportarlo nel foglio **Calore specifico**.

## 5. Misura del calore specifico

Foglio Excel: **Calore specifico**. Una riga per ogni misura.

1. Riempire un thermos con abbondante acqua a circa 65 °C (bollitore).
2. Immergere il blocchetto in questo thermos, coprire con il tappo e inserire il termometro. Agitare delicatamente fino all'equilibrio. Misurare **T1**.
3. Nell'altro thermos versare circa 200 g di acqua a temperatura ambiente (circa 25 °C). Pesare il thermos con l'acqua per ottenere `ma` (per differenza dal thermos vuoto). Coprire, inserire il termometro, agitare e misurare **Ta**.
4. Scoprire i due thermos e con un gesto deciso spostare il blocchetto da uno all'altro. Chiudere con il tappo, inserire il termometro, agitare delicatamente e attendere l'equilibrio. Misurare **Tf**.
5. Inserire nel foglio: `m1`, `T1`, massa thermos vuoto, massa thermos + acqua, `Ta`, `Tf`. Il valore di `c1` e la sua incertezza si calcolano da soli.
6. Ripetere per **ciascuno dei 4 campioni**, con almeno una seconda misura per verificare la stabilità del risultato.
7. Per l'**alluminio** eseguire almeno **5 misure ripetute** e studiare media e dispersione nel foglio **Riepilogo c**.

Consigli:

- Asciugare il blocchetto dall'acqua in eccesso prima del trasferimento, senza perdere tempo.
- Rinnovare l'acqua tra una misura e l'altra e lasciare che il blocchetto torni alla temperatura di partenza.
- Per ridurre le dispersioni termiche, scegliere le temperature in modo che `Tf` sia vicina alla temperatura ambiente.

## 6. Misura del calore latente

Foglio Excel: **Calore latente**.

1. Riempire un thermos con acqua e due abbondanti manciate di ghiaccio. Attendere qualche minuto fino a `Tg = 0 °C`.
2. Nell'altro thermos versare circa 200 g di acqua a circa 55 °C. Coprire, inserire il termometro, agitare un poco e misurare **Ta**. Pesare il thermos con l'acqua calda (`ma` per differenza dal thermos vuoto).
3. Togliere il tappo e con un gesto deciso, scolando l'acqua in eccesso, trasferire circa 70 g di ghiaccio nel thermos caldo.
4. Chiudere con il tappo, inserire il termometro, agitare e attendere che il ghiaccio sia completamente sciolto. Misurare **Tf**.
5. Pesare di nuovo il thermos con il contenuto: `mg` è l'aumento di massa rispetto alla pesata precedente.
6. Inserire i dati nel foglio. Eseguire almeno **due misure ripetute** per verificare stabilità e incertezze.

## 7. Misura della massa equivalente (opzionale)

Foglio Excel: **Massa equivalente**.

1. In un thermos mettere circa 100 g di acqua a circa 50 °C. Coprire, inserire il termometro, agitare e misurare **T1** (annotare `m1`).
2. Nell'altro thermos mettere circa 100 g di acqua a circa 5 °C (aiutarsi con il ghiaccio). Agitare e misurare **T2** (annotare `m2`).
3. Con un gesto deciso versare l'acqua fredda nel thermos caldo. Chiudere, agitare e attendere l'equilibrio. Misurare **Tf**.
4. Inserire i dati: il foglio calcola `Me`. Se si decide di usare il valore misurato, aggiornarlo in **Parametri**.

## 8. Analisi dei dati

- **Riepilogo c**: media, deviazione standard e deviazione standard della media per ogni materiale. Confrontare la dispersione `s` con l'incertezza propagata: se `s` è molto maggiore, cercare errori sistematici o condizioni non controllate.
- Confrontare i risultati con i valori di letteratura (indicativi, da verificare) e discutere gli scarti. Identificare i materiali in base ai calori specifici misurati.
- Valutare l'effetto dell'incertezza su `Me` (± 5 g) sui risultati.
- Per il calore latente confrontare con il valore atteso (circa 80 cal/g, 333,5 J/g) e commentare dispersioni termiche e acqua aderente al ghiaccio.

## 9. Incertezze

Le incertezze sono propagate in quadratura con derivate parziali, assumendo errori indipendenti. Contributi considerati: masse (singola pesata e differenza di due pesate), temperature, massa equivalente `Me`. Le risoluzioni usate sono ipotesi iniziali (0,1 g e 0,1 °C) da sostituire con quelle reali degli strumenti.

## 10. Checklist

- [ ] Parametri aggiornati (risoluzioni, `Me`)
- [ ] Masse dei thermos vuoti e dei 4 blocchetti
- [ ] Calore specifico: 4 materiali, almeno 2 misure ciascuno
- [ ] Alluminio: almeno 5 misure
- [ ] Calore latente: almeno 2 misure
- [ ] (Opzionale) massa equivalente
- [ ] Confronto con letteratura e discussione degli errori
