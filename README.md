# QR-Gen

Generatore QR code online per URL, testo e contatti vCard. Crea e scarica codici QR istantaneamente senza registrazione.

## ✨ Caratteristiche

- **3 modalità di generazione**: URL, Testo libero, Contatti vCard
- **Generazione istantanea**: Il QR si aggiorna in tempo reale mentre digiti
- **Scarica come PNG**: Salva il codice QR ad alta qualità
- **Copia dati**: Copia il contenuto del QR negli appunti
- **Generazione URL automatica**: Aggiunge https:// se mancante
- **vCard per contatti**: Genera QR con informazioni di contatto complete
- **Interfaccia moderna**: Design responsivo con Tailwind CSS
- **Mobile-friendly**: Perfetto su desktop e dispositivi mobili

## 🚀 Come usare

### URL
1. Seleziona tab "URL"
2. Inserisci un sito web (con o senza https://)
3. Il QR viene generato automaticamente
4. Scarica o copia i dati

### Testo
1. Seleziona tab "Testo"
2. Digita qualsiasi contenuto
3. QR aggiornato in tempo reale
4. Scarica o copia

### Contatti
1. Seleziona tab "Contatto"
2. Compila i campi desiderati (nome, telefono, email, etc.)
3. QR generato in formato vCard (scannerabile da contatti)
4. Scarica o copia

## 📋 Formato vCard

Il QR per contatti segue lo standard vCard 3.0:
- Nome e Cognome
- Numero di telefono
- Email
- Organizzazione
- Sito web

Scansionando il QR da contatti, importa automaticamente i dati.

## 🎨 Design

- Gradiente moderno (viola → blu → indaco)
- Tema light con interfaccia pulita
- Tab intuitiva per switch tra modalità
- Feedback visivo con animazioni

## 💾 File

- `index.html` - App completa (single page)

## 📦 Dipendenze

- **Tailwind CSS**: Styling via CDN
- **QRious**: Generazione QR code

Nessuna necessità di backend o build tools.

## 🔒 Privacy

Tutto elaborato localmente nel browser. Nessun dato inviato a server.

---

Genera QR code istantaneamente. 🔲