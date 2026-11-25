# dotto-spotify

La pagina di ritorno del login Spotify di Dotto: <https://andreaborio.github.io/dotto-spotify/>

Spotify rimanda il codice del login solo a un indirizzo https, mentre Dotto vive sul WiFi di casa in http. Questa
pagina statica (GitHub Pages) passa il codice a Dotto, trovato dallo `state` (`<casuale>~<indirizzo di Dotto>`) o
da `dotto.local`. Non salva e non manda niente altrove; il codice da solo non basta, serve anche la chiave PKCE che
resta su Dotto.
