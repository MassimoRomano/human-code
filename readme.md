# Istruction 

Contare i posti a tavola di 2 in 2
Ci s(t)iamo tutti?
Per il pranzo di Natale, diamo una mano a nonna per preparare la tavola: zio Rino, la piccola Emy, zia Lucia e nonno Carlo… siamo davvero in tanti!
Non sarà un pranzo formale, perciò non servono i segnaposto con i nomi, però dobbiamo verificare che ci sia un posto per ciascuno. Per essere più rapidi contiamo i posti a tavola di 2 in 2 e ci accorgiamo che avevamo dimenticato un posto!

## Steps

Step 1:Chiedere alla nonna se ha bisogno di aiuto

- if:ha bisogno di aiuto(step successivo)

- else: fine esercizio


Step 2: Andare nella sala da pranzo 

- if: La porta e' chiusa
    - Apri la porta
       - Attraversi la porta

- else:La porta e' aperta
     - Attraversi la porta   


Step 3: Contare i posti di 2 in 2

- if: I posti sono giusti
    - Tornare dalla nonna
      - Comunicare il numero di posti (fine step)

- else: Mancano posti a sedere
    - conti il numero di posti mancati
      - passo allo step 4


Step 4:Prendere la sedia

- if: la sedia e nella stessa sala
    - prendo la sedia
     - passo allo step 5

- else:la sedia non e' nella stessa sala
    - passo allo step 6 


Step 5:Vado nella sala da pranzo

- if: la porta e chiusa
    - apro la porta
      - entro in sala
        - posiziono la sedia

- else: porta aperta
    - entro in sala 
      - posiziono la sedia
        - comunico alla nonna (step 8) 


Step 6:Vado in cucina

- if: la sedia e in cucina
    - prendo la sedia
      - passo allo step 5

- else: Chiedo dove trovare la sedia
    - chiedo alla nonna dove trovare la sedia
     - passo allo step 7
     

Step 7: Vado in un altra sala

- if: trovo la sedia
    - prendo la sedia
      - passo allo step 5

- else: non trovo la sedia
   - passo ad un altra sala
    - riavvio lo step 7


Step 8: comunico alla nonna

- if: la nonna e soddisfatta
   - Fine esercizio

- else: la nonna ha bisogno ancora di aiuto
   - chiedo di cosa ha bisogno
     - passo allo step successivo 
