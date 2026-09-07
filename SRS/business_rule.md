# Viðskiptareglur (Business Rules)

Takmörkun sem þrengir valkosti hönnuða við gerð og þróun hugbúnaðarins.
<!--
 
Afritið sniðmátið hér fyrir neðan fyrir hverja viðskiptareglu og gefið henni næsta lausa auðkenni: BR-1, BR-2, BR-3, ... 
Notið auðkennið til að vísa í kröfuna úr SRS.md, t.d. business_requirements.md/#br1

## BRG-1

## 📜 Lýsing
> Hver er reglan?

## 🧠 Rökrétt samhengi
> Af hverju er þessi regla til staðar? Hvaða áhrif hefur hún?

## 🔗 Tengsl við kröfur eða ferla
-->
## BR-1 — Gjaldskrá eftir svæði og tíma

## BRG-1

## 📜 Lýsing
> Stæðisgjald skal ákvarðast samkvæmt þeirri gjaldskrá sem gildir fyrir viðkomandi
gjaldsvæði og þann tíma sem ökutækið er í stæði.

## 🧠 Rökrétt samhengi
> Gjaldsvæði geta haft mismunandi gjaldskrár og gjaldskrár geta einnig verið mismunandi eftir tíma dags.
Kerfið verður því að nota rétta gjaldskrá þegar greiðsluupphæð er reiknuð.

## 🔗 Tengsl við kröfur eða ferla
Tengist UR-2.1, FR-2.1.1, FR-2.1.2 og FR-2.1.3.

## BR-2 — Ábyrgð notanda á réttum upplýsingum

## BRG-2

## 📜 Lýsing
> Notandi ber ábyrgð á að skráningarnúmer ökutækis og aðrar upplýsingar sem tengja ökutækið
við notandann séu réttar og uppfærðar.

## 🧠 Rökrétt samhengi
> Kerfið notar skráningarnúmer til að tengja stæðisferli við réttan notanda. Rangarr upplýsingar
geta leitt til þess að greiðslubeiðni berist röngum notanda eða að ekki sé hægt að innheimta gjaldið.

## 🔗 Tengsl við kröfur eða ferla
Tengist UR-2.2, FR-2.2.1 og FR-3.1.2.
