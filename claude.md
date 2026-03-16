# HUSMYK — Have You Seen My Keys?
Norsk hjemorganiseringsapp. Én HTML-fil med localStorage (nøkkel: hm6).
Prioritet: retention over acquisition.
Fargepalett: teal (#2D7D7B), amber (#E8A857), mørk bakgrunn.
Teknologi: vanilla JS, ingen rammeverk, CSS custom properties.

## Utført
- Sveip-til-slett på gjenstander i lister (.swipe-row / attachSwipeHandlers)
- Rediger-knapp (✎) synlig per rad, slett (✕) som backup
- Innfallsanimasjon på kollapsbare rom-kort (.cbody)
- Tips-fane (4. tab): 30 tips fra KonMari/The Home Edit/#CleanTok/Reddit
  - 5 kategorier, filter-chips, ♥ favoritter lagret i hm_tipfavs (localStorage)

## Todo
- Flerspråklig støtte (EN)
- Familiedeling / felles husstand
- Daglige påminnelser / push-notifikasjoner
- Uke-fanen: fremdriftsvisning per dag, ukentlig oppsummering
- Streaks / gamification
- Eksport/import av data (JSON)