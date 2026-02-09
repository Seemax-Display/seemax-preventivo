# Seemax – Foglio Preventivo (v7)

## Pubblicazione (GitHub Pages)
Carica nella ROOT del repository:
- index.html
- logo.png  (IL TUO LOGO, rinominato esattamente così)

Poi abilita GitHub Pages su branch main / root.

## Funzioni
- + Riga: aggiunge righe fino a max 5
- Reset: ripulisce i campi e lascia 1 riga
- Scarica PDF: genera un riepilogo A4 in 1 pagina (senza stampa)

##Il primo numero (001)

Se apri la pagina in un browser “pulito” (mai usato prima) parte da ...-001.

Se invece ti parte ancora da ...-002 è perché nel tuo browser è già stato salvato il contatore da test precedenti (è normale: il contatore deve restare in memoria per progredire tra aperture).

✅ Per farlo ripartire da 001 (solo test):

apri la pagina

F12 → Console

esegui:

SEEMAX_RESET_COUNTER()

Poi ricarica la pagina: riparte da ...-001.
