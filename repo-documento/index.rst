####################
Manuale OpenAgenda
####################

Con OpenAgenda, la P.A. propone un significativo cambio di paradigma rispetto al passato: 
rende autonomi e responsabilizza i cittadini nella gestione degli eventi pubblici, 
mantenendo un ruolo di coordinamento e di validazione dell’intero processo, 
a garanzia del suo corretto funzionamento.

OpenAgenda è un **calendario web collaborativo**, che gestisce principalmente contenuti di due tipi:

**Eventi**
  gli eventi che avvengono sul territorio
**Associazioni**
  schede che rappresentano le associazioni presenti sul territorio.


.. sidebar:: Collaborazione e moderazione

      Due concetti fondamentali per comprendere il funzionamento di OpenAgenda sono **collaborazione** e **moderazione**:
      OpenAgenda può infatti essere configurato per la **collaborazione**, in modo da consentire l'inserimento di eventi da 
      parte di utenti esterni (le Associazioni).
      Inoltre è possibile attivare la **moderazione** in modo che la pubblicazione degli eventi inseriti dalle 
      associazioni venga validata da una redazione centrale prima di essere resi visibili sul calendario.


Esempio tipico di funzionamento
-------------------------------
La situazione più comune è quella che vede le associazioni territoriali che curano 
la propria scheda (mantenendo aggiornati i dati) e caricano i propri eventi sul sistema OpenAgenda.
Una redazione centrale si occupa poi della moderazione degli eventi, aggiustando eventuali errori,
inserendo eventuali informazioni mancanti e/o immagini, prima di renderli visibili sul calendario.
      

Visualizzazione degli eventi
----------------------------

Gli eventi caricati sul sistema OpenAgenda sono visibili in tre modalità:

Lista (con filtri)
Gli eventi vengono mostrati in una lista che li presenta in ordine cronologico per data di inizio.
E' possibile filtrare per periodo (es. "i prossimi 7 giorni", "i prossimi 30 giorni" ), 
per tipologia evento, per destinatari.

Calendario 
La rappresentazione a calendario è utile per verificare la concomitanza di eventi in una stessa giornata, 
o per verificare la presenza di eventi in un determinato periodo.


Mappa
In fase di inserimento eventi, viene richiesto di inserire la geolocalizzazione.
Questo consente di rappresentare i contenuti su una mappa, come illustrato in figura:

//immagine mappa

.. important::


      OpenAgenda è stato progettato e implementato per garantire una visualizzazione ottimale sui dispositivi mobili.
      Per questo motivo la rappresentazione standard degli eventi è quella a lista, 
      perché risulta la pià facilmente fruibile da quei dispositivi.


Tipi di accesso
---------------
Gli utenti che possono accedere al sistema OpenAgenda sono:

**utenti amministratori** 
  possono gestire le configurazioni del sistema (attivare la modalità collaborativa, attivare la moderazione, modificare titoli e testi generali);
**utenti moderatori** 
  possono inserire eventi, modificare tutti gli eventi inseriti, moderare gli eventi inseriti dalle Associazioni;
**associazioni**
  possono gestire la propria scheda e inserire eventi;
**utenti registrati** 
  se il sistema dei commenti è attivato, utenti registrati possono inserire dei commenti sotto gli eventi inseriti nel sistema


La descrizione del funzionamento del sistema OpenAgenda si divide in due parti: 
un manuale per **Associazioni e istituti culturali**, e un manuale per **Amministratori e Moderatori**

.. toctree::

   _docs/cap1.rst
   _docs/cap2.rst
