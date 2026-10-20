# Esercizi

Segue una lista di esercizi, divisi per argomento.
Gli esercizi sono pensati per fare pratica sui mattoni fondamentali della programmazione: cicli, array e funzioni.

Sono presenti circa 100 esercizi:
non dovete farli tutti, non dovete farli adesso, non dovete farli in ordine.

### Indice

- [Iterazioni](#iterazioni)
- [Array Base](#array-base)
- [Array Methods](#array-methods)
- [Funzioni](#funzioni)
- [Iterative Array Methods](#iterative-array-methods)
- [Manipolazione DOM](#manipolazione-dom)

# Iterazioni

Esercizi sulla ciclomatica

1. Stampa i numeri da 1 a 10 usando un ciclo while.

2. Stampa i numeri da 1 a 10 usando un ciclo for.

3. Chiedi un numero N all'utente. Stampa i numeri da 0 a N usando un ciclo while.

4. Chiedi un numero N all'utente. Stampa i numeri da 0 a N usando un ciclo for.

5. Stampa la tabellina del 5.

6. Chiedi all'utente una parola e un numero N. Stampa quella parola N volte.

7. Chiedi un numero N all'utente. Calcola la somma di tutti i numeri da 1 a N e stampa il risultato.

8. Il computer sceglie un numero segreto (es. 7). Chiedi all'utente di indovinarlo. Continua finché l'utente non indovina il numero corretto.

9. Chiedi all'utente di inserire il prezzo di un prodotto. Continua a chiedere prezzi e sommarli al totale finché l'utente non inserisce "0" per terminare. Stampa il totale della spesa.

10. Chiedi all'utente di inserire i suoi voti. Stampa la media.

11. L'utente ha 3 tentativi per indovinare la password. Stampa "Benvenuto" se riesce nei tentativi consentiti, altrimenti "Bloccato"

12. Il computer pensa a un numero tra 1 e 100. L'utente indovina. Dopo ogni tentativo sbagliato, il computer dice "Troppo alto" o "Troppo basso" per aiutare l'utente.

13. Scrivi in un div della pagina 100 <p>. Ognuno conterrà uno dei numeri da 1 a 100. I numeri multipli di 3 però andranno sostituiti dalla stringa "Fizz". I multipli di 5 dalla stringa "Buzz". I multipli sia di 3 che di 5 riportano "FizzBuzz".


## Array Base

Esercizi sugli array da risolvere principalmente con l'uso di cicli

14. Dato un array di prodotti e uno di quantità, stampa se il prodotto è esaurito o se le scorte sono basse.

15. Dati i voti e i nomi degli studenti, stampa chi ha la sufficienza e chi no.

16. Dati i posti liberi per carrozza [2, 0, 4, 7, 12, 8], chiedi all'utente il numero di passeggeri del gruppo e assegna loro la prima carrozza che ha capienza sufficiente, stampando il numero della carrozza scelta.

17. Date le temperature settimanali, trova il valore massimo, il minimo e calcola la media aritmetica delle sette giornate.

18. Data la lista VIP per una serata, verifica se l'utente X è presente nella lista VIP o se è nella lista standard.

19. Date le ore lavorative giornaliere `[40, 35, 45, 38, 42]` e una paga base di 15€/ora, calcola lo stipendio totale settimanale applicando una maggiorazione di 5€ per ogni ora straordinaria oltre le 40 giornaliere.

20. Dati gli atleti `["Antonio", "Bruno", "Carlo", "Diego", "Emanuel"]` e i relativi punteggi `[78, 93, 86, 91, 82]`, determina chi ha ottenuto il punteggio più alto, il secondo e il terzo più alto per assegnare rispettivamente oro, argento e bronzo.

21. Un ospedale ha 7 infermieri con questi turni: ["mattina", "pomeriggio", "notte", "mattina", "pomeriggio", "notte", "mattina"]. Conta quanti infermieri lavorano in ciascun turno.

## Array Methods

Esercizi sugli array per esercitarvi su problemi specifici che richiedono l'uso di metodi specifici degli array come indexOf, includes, charAt ecc...
Aiutati con la dispensa e la documentazione.

22. In un parcheggio numerato, l'utente cerca la sua auto; trova la posizione (indice) del suo numero di targa.

23. Devi generare un codice CSV da inviare al server; trasforma un array in una stringa con i valori separati da ",".

24. Stai usando un browser web, clicchi il pulsante "Indietro" che ti riporta alla pagina precedente; rimuovi l'ultima URL visitata dallo storico di navigazione.

25. Un partecipante si ritira da una gara a metà percorso; rimuovi il suo nome dall'array della classifica mantenendo l'ordine degli altri.

26. Hai registrato le tue spese giornaliere in ordine cronologico; invertilo per vedere l'ultima spesa effettuata in cima alla lista.

27. Prima di aggiungere un amico sui social, controlla se il suo nickname è già presente nella tua lista di contatti bloccati.

28. Stai chattando con un tuo amico; quando arriva un nuovo messaggio, aggiungilo all'intera conversazione.

29. Devi inizializzare il report mensile per il mese successivo; imposta temporaneamente tutti i valori a "N/D".

30. Alla cassa del supermercato, il primo cliente della fila viene servito e se ne va; rimuovilo della coda per far avanzare gli altri.

31. Da un estratto conto bancario, estrai solo le ultime 10 transazioni effettuate.

32. Sei il buttafuori di un locale VIP: arriva un ospite importante che deve saltare la fila; inserisci il suo nome all'inizio della lista d'ingresso.

33. In un'app di ricette, hai gli ingredienti in un array; stampali in modo leggibile nella descrizione del piatto.

34. Gestisci una fila di pazienti in sala d'attesa; quando il dottore chiama il primo paziente, rimuovilo dalla lista.

35. Trova la posizione del giorno della settimana in cui è caduto il tuo compleanno quest'anno.

36. Stai sviluppando una "To-Do List": dato un array di task già presenti, chiedi all'utente di aggiungere una nuova attività.

37. In un magazzino, gli ultimi scatoloni arrivati sono i primi ad essere spediti. Il magazziniere spedisce un pacco, stampa la lista aggiornata

38. Nella classifica di Serie A, prendi le squadre che giocheranno l'Europa League (dal 5° all'8° posto in classifica)

39. Hai una lista di priorità lavorative; il capo ti assegna un'emergenza da fare subito: inseriscila come primo elemento dell'array e stampa la lista.

40. Stai creando una funzione "Undo" (Annulla); inverti l'ordine delle azioni compiute per poterle annullare nell'ordine corretto.

41. In un menu digitale, verifica se un ingrediente specifico è presente nella lista degli allergeni di un piatto.

42. Devi inserire una pubblicità dopo la terza notizia nel feed di un giornale online; inserisci l'elemento pubblicitario nella posizione corretta senza sovrascrivere nulla.

43. Dopo una partita di tris, inizializza la griglia di gioco con il valore "vuoto" a tutte le celle.

## Funzioni

Questi esercizi sono ideali per essere risolti tramite una funzione.

44. Stai pianificando un viaggio negli USA. Scrivi una funzione che converta una somma in Euro nel corrispondente valore in Dollari, dato il tasso di cambio del giorno.

45. Un taxi applica una tariffa extra fissa dopo la mezzanotte. Scrivi una funzione che calcoli il totale della corsa dato il prezzo base all'orario di partenza e all'orario di arrivo.

46. Scrivi una funzione che, dato l'anno di nascita e il genere (M/F), calcoli quanti anni mancano per raggiungere l'età pensionabile (fissata a 67 anni per gli uomini e 62 per le donne).

47. Un professore deve convertire un voto numerico in un giudizio. Scrivi una funzione che restituisca "Insufficiente", "Sufficiente" o "Ottimo" in base al punteggio.

48. Stai organizzando un evento. Scrivi una funzione che ti dica quanti giorni ha un determinato mese.

49. Hai la durata di un film in minuti totali. Scrivi una funzione che la converta in un formato più leggibile "X ore e Y minuti".

50. Finisce l'anno scolastico e vuoi fare la media dei tuoi voti. Scrivi una funzione che riceve tre voti numerici e restituisce la media aritmetica.

51. Un calendario digitale deve mostrare il giorno esteso. Scrivi una funzione che riceve un numero da 1 a 7 e restituisce il nome del giorno corrispondente (1 = Lunedì, ..., 7 = Domenica). Se il numero non è valido, restituisce "Errore".

52. Etichetta l'utente in base alla sua età. Sotto i 18 anni "Minorenne", "Giovane Adulto" tra 18 e 35, "Adulto" se tra 36 e 60, "Senior" oltre 60.

53. Un tracker di spedizioni usa codici numerici. Scrivi una funzione che riceve un codice (1, 2, 3) e restituisce "In elaborazione" per 1, "Spedito" per 2, "Consegnato" per 3. Se il codice non esiste, restituisce "Stato sconosciuto".

## Iterative Array Methods

Anche qui usiamo metodi degli array, ma ci riferiamo a quei metodi che usiamo per iterare, collegando una funzione ad ogni iterazione (each, map, filter, every ecc..)

54. data una lista di prezzi originali, applica uno sconto del 20% a ciascun prodotto

55. data una lista di voti di esami, trova il primo esame non superato

56. data una lista di consumi elettrici giornalieri in kWh, stampa ogni consumo. Usa console.warn per i consumi alti

57. data una lista di nomi, trova solo quelli che hanno una lunghezza tra 3 e 5 caratteri

58. data una lista di parole, verifica che nessuna abbia un carattere maiuscolo

59. data una lista di città, verifica se c'è qualche città composta da più parole (es. 'New York')

60. data una lista di calorie consumate, convertile in kJ

61. data una lista di ore lavorate ogni giorno della settimana, stampa per ogni giorno il tempo relativo lavorato, in minuti

62. data una lista di valutazioni (1-5 stelle), trova solo le recensioni con più di 4 stelle

63. data una lista di stati di prenotazione ("confermata", "annullata", "in attesa"), trova la prima prenotazione annullata

64. data una lista di test (true/false), verifica se sono stati tutti superati

65. data una lista di temperature medie giornaliere, verifica se c'è almeno un giorno in cui la temperatura è andata sotto 0

66. data una lista di voti in trentesimi, convertili in decimi

67. data una lista di prezzi al supermercato, stampa ogni prezzo con l'IVA al 22% inclusa

68. data una lista di punteggi di un test di selezione, trova i candidati con punteggio ≥ 70

69. data una lista di giorni rimanenti alla scadenza di documenti, trova il primo documento che scade entro 7 giorni

70. data una lista di voti, verifica se sono stati tutti positivi

71. data una lista di voti, verifica se c'è qualche esame non superato

72. data una lista di prezzi originali, applica uno sconto del 20% a ciascun prodotto

73. data una lista di consumi elettrici giornalieri in kWh, stampa ogni consumo. Usa console.warn per i consumi che superano una certa soglia di allarme

74. data una lista di nomi, trova solo quelli che hanno una lunghezza tra 3 e 5 caratteri

75. data una lista di voti di esami, trova il primo esame non superato

76. data una lista di parole, verifica che nessuna abbia un carattere maiuscolo

77. data una lista di città, verifica se c'è qualche città composta da più parole

## Manipolazione DOM

78. Crea una lista della spesa e aggiungi un nuovo articolo quando l'utente clicca sul pulsante.

79. In pagina c'è una notifica, falla scomparire quando l'utente clicca sulla "X" di chiusura.

80. Stai creando un contatore di click; incrementa il numero visualizzato nel pulsante dopo ogni click.

81. Un utente sta compilando un profilo; seleziona tutti gli input e valida che non siano vuoti quando il form viene inviato.

82. Vuoi cambiare il tema della pagina; aggiungi la classe .dark-mode quando l'utente clicca sull'interruttore del cambio tema.

83. Devi svuotare un carrello; seleziona tutti i bottoni con classe .rimuovi e cancella l'articolo corrispondente quando uno di essi viene cliccato.

84. Un campo password richiede una validazione; mostra un messaggio di errore se l'utente esce lascia l'input senza aver scritto nulla.

85. In un form, abilita il tasto "Registrati" solo se il checkbox della privacy è selezionato.

86. Devi evidenziare una riga di una tabella al passaggio del mouse.

87. Un utente sta scrivendo un commento; conta i caratteri rimanenti in tempo reale mentre scrive.

88. crea un input e un paragrafo. Mentre l'utente digita nell'input, il testo del paragrafo si aggiorna in tempo reale

89. crea un pulsante e un input password. Al click, cambia il tipo dell'input da password a text e viceversa

90. crea un input e un pulsante disabilitato. Abilita il pulsante solo quando l'input contiene almeno 3 caratteri

91. con due input password, mostra un messaggio di errore rosso se i valori non coincidono mentre l'utente digita nel secondo campo

92. dato un prezzo fisso e un input per la quantità, aggiorna in tempo reale un paragrafo che mostra il totale

93. dato un oggetto utente (nome, ruolo, img) e una struttura HTML vuota, inserisci i dati dell'oggetto nei rispettivi elementi della pagina

94. dato un oggetto prodotto con una quantità, mostra un badge del colore appropriato e con una descrizione appropriata

95. data una lista di colori, genera in pagina una serie di box, ognuno con il suo colore

96. dato il menù di una pizzeria, genera dinamicamente una lista HTML che mostri nome e prezzo di ogni pizza

97. data una lista di contatti telefonici, genera una lista HTML. Al click su un elemento, mostra il numero di telefono corrispondente tramite un alert
