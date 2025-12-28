# LiveAvatar – versione telefono (fullscreen)

## Cosa contiene
- `index.html` : landing con pulsante "Parla con l’assistente"
- `ai.html`    : pagina full-screen con iframe LiveAvatar e pulsante fullscreen

## Come pubblicare (Vercel)
1) Crea un nuovo progetto su Vercel
2) Importa questa cartella (o carica lo ZIP)
3) Deploy

## Note importanti (telefono)
- I permessi di microfono/fotocamera funzionano solo in HTTPS (Vercel lo è).
- Alcuni browser richiedono un tap iniziale: per questo c’è il pulsante "Avvia".
- Se vedi bande o margini DENTRO l’avatar, non è HTML: è layout interno dell’embed LiveAvatar.

## Link iframe usato
https://embed.liveavatar.com/v1/bd852dff-d57d-4ea4-bbcb-086a7837d695
