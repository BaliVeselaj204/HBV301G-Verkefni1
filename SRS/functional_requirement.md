
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
> Kerfið skal skrá komu bíls í stæði sjálfkrafa (t.d. með myndavél) og skrá tímasetningu komunnar.

## 🧪 Staðfesting
> Leggja bíl í stæði og athuga hvort kerfið skrái komutíma innan tiltekins tímaramma (t.d. innan 10 sekúndna)
án handvirkar aðgerðar notanda.

## 🔗 Tengd notendakrafa
> UR-2.1

## FR-2.1.2

## ⚙️ Lýsing
> Kerfið skal greina sjálkrafa þegar bíll yfirgefur stæðið og skrá tímasetningu brottfarar.

## 🧪 Staðfesting
> Fjarlægja bíl úr stæði og athuga hvort kerfið skrái brottfarartíma án handvirkar aðgerðar notanda.
án handvirkar aðgerðar notanda.

## 🔗 Tengd notendakrafa
> UR-2.1

## FR-2.1.3

## ⚙️ Lýsing
> Kerfið skal reikna út heildarlengd stæðistíma út frá skráðri komu- og borttfarartíma.

## 🧪 Staðfesting
> Bera saman útreiknaðan stæðistíma kerfisins við raunverulegan tíma sem bíll var lagður í stæðinu
og staðfesta að þau séu alveg eins.

## 🔗 Tengd notendakrafa
> UR-2.1

## FR-2.2.1

## ⚙️ Lýsing
> Kerfið skal reikna út greiðsluupphæð sjálkrafa út frá stæðistíma og gildandi gjaldskrá.

## 🧪 Staðfesting
> Prófa með mismunandi stæðistíma og staðfesta að útreiknuð upphæð sé í samræmi  við gjaldskrá kerfisins.

## 🔗 Tengd notendakrafa
> UR-2.2

## FR-2.2.2

## ⚙️ Lýsing
> Kerfið skal tengja skráða bílnúmerið við notandareikning til að finna réttar upplýsingar fyrir reikning.

## 🧪 Staðfesting
> Athuga með mismunandi bílnúmerum að kerfið finni réttan notanda.

## 🔗 Tengd notendakrafa
> UR-2.2

## FR-2.2.3

## ⚙️ Lýsing
> Kerfið skal senda notanda sjálfvirka greiðslu í netbanka innan 5 mínútna frá brottför úr stæði.

## 🧪 Staðfesting
> Mæla tímann frá brottför bíls þar til krafa birtist í netbanka og staðfesta að hann sé innan tilskilins tímamarka.

## 🔗 Tengd notendakrafa
> UR-2.2

