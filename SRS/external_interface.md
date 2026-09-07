

# Ytri tenging (External interface)

Lýsing á tengingu milli hugbúnaðarkerfisins og notanda, annars hugbúnaðar, vélbúnaðar eða samskiptakerfis.


<!--

Afritið sniðmátið hér fyrir neðan fyrir hverja kröfu og gefið henni auðkenni 

## UI-1

## 🔌 Skil
> Við hvern eða hvað hefur kerfið samskipti?

## 📥 Inntak / úttak
> Hvaða gögn, skipanir eða merki fara milli kerfisins og ytri aðilans?

## 📚 Samskipti og staðlar
> Hvernig fara samskiptin fram? Eru tiltekin snið, samskiptareglur eða staðlar notaðir?

 ## 📌 Tegund skila
- [x ] Notendaviðmót (User interface)
- [ ] Hugbúnaðarviðmót (Software interface)
- [ ] Vélbúnaðarviðmót (Hardware interface)
- [ ] Samskiptaviðmót (Communications interface)
-->

## UI-1

## 🔌 Skil
> Kerfið hefur samskipti við Ísland.is til að senda og uppfæra stöðu reikninga notanda.

## 📥 Inntak / úttak
> Frá kerfinu: reikningsnúmer, upphæð, kennitala notanda, staða greiðslu.
Frá Ísland.is: staðfesting á móttöku eða villuboð ef sending mistekst.

## 📚 Samskipti og staðlar
> Samskiptin fara fram með API-tengingu við Ísland.is samkvæmt þeim stöðlum og gagnasniðum
sem þjónustan skilgreinir.

 ## 📌 Tegund skila
- [ ] Notendaviðmót (User interface)
- [x] Hugbúnaðarviðmót (Software interface)
- [ ] Vélbúnaðarviðmót (Hardware interface)
- [ ] Samskiptaviðmót (Communications interface)

## UI-2

## 🔌 Skil
> Kerfið hefur samskipti við greiðslugátt/netbanka fjármálastofnana til að senda
greiðslukröfur og taka við greiðslum.

## 📥 Inntak / úttak
> Frá kerfinu: kennitala eða reikningsnúmer notanda, upphæð, gjalddagi.
Frá greiðslugátt: staðfesting á greiðslu eða höfnun/villuboð.

## 📚 Samskipti og staðlar
> Samskiptin fara fram með öruggri API-tengingu við greiðslugátt bankans,
samkvæmt stöðlum sem íslenskar fjármálastofnanir styðja.

 ## 📌 Tegund skila
- [ ] Notendaviðmót (User interface)
- [x] Hugbúnaðarviðmót (Software interface)
- [ ] Vélbúnaðarviðmót (Hardware interface)
- [ ] Samskiptaviðmót (Communications interface)
