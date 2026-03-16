# HUSMYK — Have You Seen My Keys?
Norsk hjemorganiseringsapp. Én HTML-fil med localStorage (nøkkel: hm6).
Prioritet: retention over acquisition.
Fargepalett: teal (#2D7D7B), amber (#E8A857), mørk bakgrunn.
Teknologi: vanilla JS, ingen rammeverk, CSS custom properties.

## Utført
- Sveip-til-slett på gjenstander i lister (.swipe-row / attachSwipeHandlers)
- Rediger-knapp (✎) synlig per rad, slett (✕) fjernet (sveip er primær)
- Innfallsanimasjon på kollapsbare rom-kort (.cbody)
- Tips-fane (4. tab): 45 tips fra KonMari/The Home Edit/#CleanTok/Reddit
  - 7 kategorier, filter-chips, ♥ favoritter lagret i hm_tipfavs (localStorage)
- Uke-fanen: ukens fremdriftsbar m/ prikker per dag + amber-markering for i dag
- Daglig påminnelse: toggle + tidspunkt, Browser Notifications API (hm_notif)
- 🔥 Streak-teller: daglig streak i hm_streak, milestone-animasjoner (3/7/14/30/60/100)
- Undo-toast: 5 sek angre-knapp etter sletting av ting
- PWA-støtte: meta-tags (iOS), manifest via data URI, beforeinstallprompt-banner

## Todo
- Flerspråklig støtte (EN)
- Familiedeling / felles husstand
- Eksport/import av data (JSON)
- Bildelagring per gjenstand
- Ukentlig oppsummerings-toast
- Pull-down hurtigsøk fra alle skjermer