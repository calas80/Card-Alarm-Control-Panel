# Card Alarm Control Panel


# PER PIACERE NON MI CHIEDETE AIUTI SU COME FAR FUNZIONARE LE CARD SE USATE LA UI. 
Io scrivo le mie card in YAML. Non vi so aiutare se usate la UI, mai usata e mai la userò  ^_- 



* SCHERMATA PRINCIPALE
<img width="403" alt="Schermata 2022-09-24 alle 11 15 05" src="https://user-images.githubusercontent.com/48358142/192149035-a781597d-cb8f-4428-9dc7-17639bfcb3cb.png">

* SCHERMATA PRINCIPALE con ospiti in casa
<img width="408" alt="Schermata 2022-09-25 alle 16 46 45" src="https://user-images.githubusercontent.com/48358142/192149851-4acbd3b0-70ee-40f7-a89d-e3b51a36dbe9.png">

- INDICATORE DI STATO DI CARICA
<img width="408" alt="Schermata 2022-09-25 alle 00 43 15" src="https://user-images.githubusercontent.com/48358142/192149009-c46d9292-b8e9-48d7-9d8e-5365280aa9e1.png">

- TAB IMPOSTAZIONI
<img width="408" alt="Schermata 2022-09-25 alle 15 46 18" src="https://user-images.githubusercontent.com/48358142/192149018-765a5bf2-3819-4333-8ebf-bc28bfa0899f.png">

- GESTIONE TIPI DI ALLARME
<img width="806" alt="Schermata 2022-09-25 alle 17 18 13" src="https://user-images.githubusercontent.com/48358142/192151290-d8f87640-7a6e-4aad-938c-a08e123e42a8.png">


<img width="500" alt="Schermata 2022-09-25 alle 17 18 13" src="https://user-images.githubusercontent.com/48358142/192542069-237dd193-c310-4b0a-93f7-f9253cf47322.jpeg">




# Tutto realizzato con una solo button custom card.
https://github.com/custom-cards/button-card

Per l'installazione dovete copiare il file principale + il contenuto del file template.
Come usare il file template di custom button card è spiegato nella sua documentazione. Essenzialmente dovete creare un file template.yaml e poi dovete aggiungere una riga simile - button_card_templates: !include template.yaml - al vostro ui-lovelace.yaml (scrivo simile perchè il percorso può cambiare in base a dove decidete di creare il file template.yaml
https://github.com/custom-cards/button-card#configuration-templates

Caratteristiche:

Tab HOME
- Indicatore della zona della persona
- Indicatore del livello di batteria
- indicatore dello stato di carica
- Indicatore del numero di finestre aperte
- indicatore del numero di inferriate aperte
- Tasto per smart locke: alla pressione prolungata se è aperto chiude se è chiuso apre
- 3 tasti per abilitirare o meno l'inserimento automatico dell'allame notte, fuori casa e in casa
- Tasto per abilitare il simulatore di presenza
- Indicatore dello stato della modalità ospite + indicatore del numero di ospiti prendenti in casa
- Tenendo premuto lo scudetto si apre un popup con il quale è possibile abilitare i vari tipi di allarme
- Ai lati dello scudetto centrale le due icone servon ad aprire la porta (se la serratura è aperta e a spegnere la sirena se sta suondando)

Tab IMPOSTAZIONI

- Richiesta disabilitazione preventiva allarme per batteria scarica cellulare
- Invio foto con allarme triggerato
- Telefonata con allarme trigerato
- Triggera allarme se la serratura gira
- Disabilitazione preventiva allarme se allarme notte è inserito
- Triggera allarme se vengono premuti tasti delle luci
- Chiudi la serratura se l'allarme è inserito
- Spegni luci se l'allarme è attivo

