# 📚 Libreria Personale
# 🔗 Link: https://cortrifer.github.io/Libreria/

Un'applicazione web elegante e interattiva per gestire la tua collezione personale di libri.

### ⌨️ *Utilizzare al PC!*

## ✨ Caratteristiche

- **Gestione Libreria**: Aggiungi e rimuovi libri dalla tua collezione
- **Tracking Possesso**: Segna quali libri possiedi e quali devi acquistare
- **Statistiche Live**: Contatori aggiornati in tempo reale
- **Drag & Drop**: Riordina i libri con un'interfaccia intuitiva
- **Salvataggio Automatico**: Dati persistiti nel localStorage
- **Notifiche**: Feedback visivo per tutte le operazioni

## 🎯 Utilizzo

### Aggiungere un Libro
1. Clicca **"Aggiungi Libro"**
2. Inserisci titolo, autore e opzionalmente l'URL della copertina
3. Conferma con "Aggiungi Libro"

### Gestire il Possesso
- Spunta **"Possiedo questo libro"** sotto ogni libro

### Eliminare Libri
1. Seleziona **"Rimuovere dalla libreria"** per i libri da eliminare
2. Clicca **"Elimina Libro/i"**

### Riordinare
- Trascina i libri nella posizione desiderata

## 📊 Struttura Dati

I libri sono memorizzati come:

```javascript
{
  id: number,        // ID univoco auto-incrementale
  title: string,     // Titolo del libro
  author: string,    // Autore
  cover: string,     // URL copertina (default se non fornito)
  owned: boolean     // Stato possesso
}
```

## 🛠 Tecnologie Utilizzate

- **HTML5** - Struttura semantica e markup
- **CSS3** - Stili avanzati con gradienti, flexbox, grid e animazioni
- **JavaScript ES6** - Logica applicativa e gestione dello stato
- **SortableJS** - Funzionalità drag-and-drop per il riordino libri
- **LocalStorage API** - Persistenza dati lato client

## 🚀 Come Iniziare

### Metodo: Usa Link all'inizio

### Metodo: Browser Locale

1. Scarica i file del progetto
2. Apri `index.html` nel tuo browser preferito
3. Inizia ad aggiungere i tuoi libri!
