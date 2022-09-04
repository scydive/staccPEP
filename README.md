# Oppgavebeskrivelse.
Jeg har valgt å ta i bruk KYC APIen til Stacc for å utføre PEP sjekker av personer med et Python program.
For å gjøre prosjektet mer interessant er koden i form av en discord bot, både input og output skjer på discord.


# Hvordan kjøre prosjektet
Dessverre litt komplisert da koden krever en discord bot.

Alternativt til dette kan jeg invitere til en discord server hvor botten kjører, eller jeg kan oppgi en invitasjonslink for å få botten på en server. For dette vennligst kontakt meg på aadne1999@live.no


For å hoste din egen discord bot:

Ha eller lag en discord konto.

Gå til https://discord.com/developers/applications.

Klikk 'New application' og navngi den.

Trykk på 'bot' på menyen til venstre, så 'add bot'. Du vil blant annet bli utdelt en token til denne botten.

Åpne python programmet.

øverst i koden finner du TOKEN = ('Discord bot token her'). Erstatt teksten med din token.

I developer portal trykker du nå på OAuth2, så URL generator.

På scopes, velg 'bot'. På bot permissions velg 'send messages'

Kopier URLen nederst og følg den, velg så en server som du vil ha botten til i, du trenger de nødvendige privilegiene til dette.

Kjør python programmet

Skriv .pepSjekk VALGFRITT NAVN. 

Dersom et vanlig fornavn/etternavn blir brukt vil en stor del resultater forekomme. For å spare APIen og for å unngå å sende 100+ meldinger blir max 10 navn oppgitt.

For best resultat, oppgi dermed full navn.

Avhengigheter er discord.py og requests.









