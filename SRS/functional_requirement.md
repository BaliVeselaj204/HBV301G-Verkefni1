
# Virkniskrafa (Functional Requirement)

Lýsing á hegðun sem kerfið á að sýna við tilteknar aðstæður. Þetta er það sem forritarinn þarf að útfæra til að notendur geti lokið verkefnum sínum (sjá notendakröfur).

<!--

Afritið sniðmátið hér fyrir neðan fyrir hverja kröfu og gefið henni auðkenni 

## FR-1

## ⚙️ Lýsing
> Hvaða virkni á kerfið að framkvæma?

## 🧪 Staðfesting
> Hvernig væri hægt að sannreyna að kerfið uppfylli þessa kröfu?

## 🔗 Tengd notendakrafa
> Vísaðu í notendakröfu sem þessi virknikrafa styður, ef við á.

-->
## FR-1.1.1

## ⚙️ Lýsing
> Kerfið skal greina þegar ökutæki kemur inn á gjaldsvæði.

## 🧪 Staðfesting
> Aka ökutæki inn á gjaldsvæðið og staðfesta að kerfið nái að greina komu þess.

## 🔗 Tengd notendakrafa
> UR-1.1

## FR-1.1.2

## ⚙️ Lýsing
> Kerfið skal lesa skráningarnúmer ökutækis sem kemur inn á gjaldsvæði.

## 🧪 Staðfesting
> Aka mismunandi ökutækjum inn á gjaldsvæðið og staðfesta að rétt bílnúmer hafi verið lesið.

## 🔗 Tengd notendakrafa
> UR-1.1

## FR-1.1.3

## ⚙️ Lýsing
> Kerfið skal stofna virka talningu með bílnúmeri ökutækis, gjaldsvæði og komutíma.

## 🧪 Staðfesting
> Aka ökutæki inn á gjaldsvæðið og staðfesta að talning stæðistíma af rétt skráðu bílnúmeri, 
gjaldsvæði og komutíma.

## 🔗 Tengd notendakrafa
> UR-1.1

## FR-1.2.1

## ⚙️ Lýsing
> Kerfið skal greina þegar ökutæki yfirgefur gjaldsvæði.

## 🧪 Staðfesting
> Aka ökutæki út af gjaldsvæðinu og staðfesta að kerfið greini brottför þess.

## 🔗 Tengd notendakrafa
> UR-1.2

## FR-1.2.2

## ⚙️ Lýsing
> Kerfið skal lesa bílnúmer ökutækis við brottför og finna skráningu þess innan kerfisins.

## 🧪 Staðfesting
> Aka ökutæki sem er með virka talningu út af gjaldsvæðinu og staðfesta að kerfið finni rétta skráningu.

## 🔗 Tengd notendakrafa
> UR-1.2

## FR-1.2.3

## ⚙️ Lýsing
> Kerfið skal skrá brottfarartíma ökutæki og ljúka talningu stæðistíma þess ökutækis.

## 🧪 Staðfesting
> Aka ökutæki út af gjaldsvæðinu og staðfesta að brottfarartíminn sé skráður á rétt ökutæki og að henni 
sé merkt sem lokið.

## 🔗 Tengd notendakrafa
> UR-1.2

## FR-2.1.1

## ⚙️ Lýsing
> Kerfið skal reikna út lengd stæðistíma út frá skráðum komu- og brottfarartíma.

## 🧪 Staðfesting
> Prófa með mismunandi komu- og brottfarartímum og staðfesta að útreiknaður
stæðistími sé réttur í öllum tilvikum.

## 🔗 Tengd notendakrafa
> UR-2.1

## FR-2.1.2

## ⚙️ Lýsing
> Kerfið skal finna þá gjaldskrá sem gildir fyrir viðkomandi gjaldsvæði.

## 🧪 Staðfesting
> Leggja bíl í mismunandi gjaldsvæði og staðfesta að kerfið velji rétta
gjaldskrá fyrir hvert svæði.

## 🔗 Tengd notendakrafa
> UR-2.1

## FR-2.1.3

## ⚙️ Lýsing
> Kerfið skal reikna greiðsluupphæð út frá stæðistíma og gildandi gjaldskrá.

## 🧪 Staðfesting
> Prófa með mismunandi samsetningum af stæðistíma og gjaldskrám og staðfesta
að útreiknuð upphæð sé rétt í hverju tilviki.

## 🔗 Tengd notendakrafa
> UR-2.1

## FR-2.2.1

## ⚙️ Lýsing
> Kerfið skal tengja skráningarnúmer ökutækis við réttan notandareikning.

## 🧪 Staðfesting
> Prófa með mismunandi skráningarnúmerum og staðfesta að kerfið finni og
tengi þau við rétta notendareikninga í hvert sinn

## 🔗 Tengd notendakrafa
> UR-2.2

## FR-2.2.2

## ⚙️ Lýsing
> Kerfið skal stofna greiðslubeiðni fyrir rétta upphæð á réttan notanda.

## 🧪 Staðfesting
> Bera saman stofnaða greiðslubeiðni við útreiknaða upphæð og skráðan notanda,
og staðfesta að hvort tveggja sé rétt.

## 🔗 Tengd notendakrafa
> UR-2.2

## FR-2.2.3

## ⚙️ Lýsing
> Kerfið skal senda greiðslubeiðnina í netbanka innan 5 mínútna frá lokum stæðistíma.

## 🧪 Staðfesting
> Mæla tímann frá lokum stæðistíma þar til krafa birtist í netbanka notanda og staðfesta
að hann sé innan 5 mínútna.

## 🔗 Tengd notendakrafa
> UR-2.2

## FR-3.1.1

## ⚙️ Lýsing
> Kerfið skal hefja tilkynningarferli þegar ný skráning er stofnuð.

## 🧪 Staðfesting
> Stofna skráningu ökutækis og staðfesta að tilkynningarferlið hefjist.

## 🔗 Tengd notendakrafa
> UR-3.1

## FR-3.1.2

## ⚙️ Lýsing
> Kerfið skal finna kennitölu skráðs eiganda ökutækis þegar ný talning er stofnuð.

## 🧪 Staðfesting
> Stofna skráningu fyrir ökutæki með þekkt bílnúmer og staðfesta að kerfið finni kennitölu hjá 
skráðum eiganda.

## 🔗 Tengd notendakrafa
> UR-3.1

## FR-3.1.3

## ⚙️ Lýsing
> Kerfið skal senda tilkynningu til skráðs eiganda ökutækisins í gegnum Ísland.is innan tiltekins tíma 
frá því að skráningin sé stofnuð.

## 🧪 Staðfesting
> Stofna skráningu og mæla tímann þar til tilkynning berst réttum notanda í gegnum Ísland.is.

## 🔗 Tengd notendakrafa
> UR-3.1

## FR-3.2.1

## ⚙️ Lýsing
> Kerfið skal hefja tilkynningarferli þegar greiðslubeiðni hefur verið stofnuð.

## 🧪 Staðfesting
> Stofna greiðslubeiðni fyrir ökutæki og staðfesta að tilkynningarferli kerfisins hefjist.

## 🔗 Tengd notendakrafa
> UR-3.2

## FR-3.2.2

## ⚙️ Lýsing
> Tilkynning um greiðslubeiðni skal innihalda upphæð greiðslubeiðninnar og upplýsingar um hvaða 
gjaldsvæði hún tilheyrir.

## 🧪 Staðfesting
> Stofna greiðslubeiðni með fyrirfram þekktri upphæð og staðfesta að tilkynningin innihaldi rétta 
upphæð og vísi í rétt gjaldsvæði.

## 🔗 Tengd notendakrafa
> UR-3.2

## FR-3.2.3

## ⚙️ Lýsing
> Kerfið skal senda tilkynningu um greiðslubeiðnina til viðkomandi notanda í gegnum Ísland.is.

## 🧪 Staðfesting
> Stofna greiðslubeiðni fyrir prófunarnotanda og staðfesta að tilkynning berist viðkomandi notanda 
í gegnum Ísland.is.

## 🔗 Tengd notendakrafa
> UR-3.2

