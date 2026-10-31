YOUNGEXCHANGE V6 - RICOSTRUZIONE GRAFICA / ANTEPRIMA

Questa versione e una ricostruzione delle otto pagine, NON un exchange operativo.
Mercati: CoinGecko REST (60 secondi), grafici storici reali. Non e un feed tick-by-tick WebSocket.
Account: lettura di wallets.eur_balance e requests su Supabase se config.js e configurato.
Saldi crypto, operazioni, Twilio e pannello admin NON sono ancora completati.
Non vengono creati movimenti o valori fittizi.
Assistenza: codice ProvideSupport ps_h=mAwv incluso in tutte le 8 pagine.

PER PROVARE SENZA SOSTITUIRE IL SITO PUBBLICO:
1. Estrarre lo ZIP su Windows.
2. In config.js incollare SOLTANTO URL Supabase e chiave PUBLISHABLE pubblica.
3. NON inserire chiavi secret/service_role, token Twilio o password.
4. Caricare i file nella cartella v6/ del repository GitHub Pages, mantenendo la V5.
5. Aprire https://USERNAME.github.io/REPOSITORY/v6/dashboard.html
6. Verificare le 8 pagine e il pulsante Assistenza in alto a destra.
7. Dopo approvazione del design, implementare la logica server e i controlli di sicurezza.

ATTENZIONE: file login.html, reset.html e admin.html provengono dalla V5 e non sono stati
ancora ridisegnati in questa fase. NON attivare funzionalita amministrative in produzione.
