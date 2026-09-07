# 📄 Software Requirements Specification (SRS)

## 1. Inngangur
### 1.1 Tilgangur
Tilgangurinn með okkar kerfi er að gera ökumönnum kleift að leggja bíl í stæði án nokkurrar
handvirkrar aðgerðar. Kerfið skráir sjálfkrafa komu og brottför ökutækis, reiknar út stæðisgjald
og sendir greiðslu á notanda.


### 1.2 Umfang og mörk kerfisins
Innan kerfisins: sjálfvirk skráning á komu/brottför bíla, útreikningur á stæðistíma og gjaldi, og sending greiðslubeiðna.

Utan kerfisins: sjálf greiðslumiðlunin (bankar), skráning notenda hjá Ísland.is,
og myndavélar/skynjarar sem safna gögnum.

Helstu tengiliðir: ökumenn, rekstraraðili stæðisins, greiðslugátt og Ísland.is.


### 1.3 Skilgreiningar
| Hugtak | Skýring |
|--------|---------|
| SRS | Software Requirements Specification |
| Stæðistími | Sá tími sem ökutæki stendur í stæði, frá komu til brottfarar |
| Gjaldsvæði | Afmarkað svæði með sína eigin gjaldskrá fyrir stæði |


### 1.4 Tilvísanir
- ISO/IEC/IEEE International Standard - Systems and software engineering -- Life cycle processes -- Requirements engineering," in ISO/IEC/IEEE 29148:2018(E) , vol., no., pp.1-104, 30 Nov. 2018, doi: 10.1109/IEEESTD.2018.8559686.ISO/IEC/IEEE 29

---

## 2. Almenn lýsing
### 2.1 Notendahópar
- **Ökumenn** — nota kerfið til að leggja í stæði og greiða fyrir stæðistíma sjálfkrafa.
- **Rekstraraðili stæðisins** — hefur hag af skilvirkri innheimtu og minni þörf fyrir handvirkt eftirlit.

### 2.2 Viðskiptaávinningur
Kerfið fækkar sektum sem stafa af gleymdri greiðslu og gerir stæðisupplifun ökumanna einfaldari
og áreynslulausari, á sama tíma og það eykur skilvirkni innheimtu fyrir rekstraraðila.

---

## 3. Kröfur fyrir kerfið

### 3.1 Viðskiptakröfur
| ID                                        | Titill                    |
|-------------------------------------------|---------------------------|
| [BREQ-1](business_requirements.md#breq-1) | Færri sektir vegna gleymsku |
| [BREQ-2](business_requirements.md#breq-2) | Einföld stæðisupplifun |

### 3.2 Kerfiskrafa
| ID                              | Titill                 |
|---------------------------------|------------------------|
| [SR-1](system_requirement.md#sr-1) | Sjálfvirk skráning og innheimta stæðisgjalda |

### 3.3 Eiginleikar (Features)
| ID                     | Titill                 |
|------------------------|------------------------|
| [F-1](feature.md#f-1)  | Sjálfvirk skráning frá eftirlitsmyndavél |
| [F-2](feature.md#f-2)  | Sjálfvirk greiðslubeiðni til notanda |
| [F-3](feature.md#f-3)  | Senda stöðu reikninga í gegnum Ísland.is |

### 3.4 Notendakröfur
| ID                                    | Titill                                     | Eiginleiki |
|----------------------------------------|---------------------------------------------|------------|
| [UR-1.1](user_requirement.md#ur-11)   | Akstur inn í gjaldsvæði                    | F-1        |
| [UR-1.2](user_requirement.md#ur-12)   | Yfirgefa gjaldsvæði                        | F-1        |
| [UR-2.1](user_requirement.md#ur-21)   | Rétt upphæð fyrir rukkun                   | F-2        |
| [UR-2.2](user_requirement.md#ur-22)   | Sjálfvirk greiðslubeiðni eftir stæðistíma  | F-2        |
| [UR-3.1](user_requirement.md#ur-31)   | Tilkynning um lagðan bíl                   | F-3        |
| [UR-3.2](user_requirement.md#ur-32)   | Upplýsingar um greiðslu stæðis             | F-3        |

### 3.5 Virknikröfur
| ID                                            | Titill                                        | Notendakrafa |
|-----------------------------------------------|---------------------------------------------|--------------|
| [FR-1.1.1](functional_requirement.md#fr-111)   | Greina komu ökutækis                          | UR-1.1       |
| [FR-1.1.2](functional_requirement.md#fr-112)   | Lesa skráningarnúmer                          | UR-1.1       |
| [FR-1.1.3](functional_requirement.md#fr-113)   | Skrá talningu                                 | UR-1.1       |
| [FR-1.2.1](functional_requirement.md#fr-121)   | Greina brottför ökutækis                      | UR-1.2       |
| [FR-1.2.2](functional_requirement.md#fr-122)   | Lesa bílnúmer við brottför                    | UR-1.2       |
| [FR-1.2.3](functional_requirement.md#fr-123)   | Skrá brottfarartíma                           | UR-1.2       |
| [FR-2.1.1](functional_requirement.md#fr-211)   | Reikna stæðistíma                             | UR-2.1       |
| [FR-2.1.2](functional_requirement.md#fr-212)   | Finna gjaldskrá gjaldsvæðis                   | UR-2.1       |
| [FR-2.1.3](functional_requirement.md#fr-213)   | Reikna greiðsluupphæð                         | UR-2.1       |
| [FR-2.2.1](functional_requirement.md#fr-221)   | Tengja skráningarnúmer við notanda            | UR-2.2       |
| [FR-2.2.2](functional_requirement.md#fr-222)   | Stofna greiðslubeiðni                         | UR-2.2       |
| [FR-2.2.3](functional_requirement.md#fr-223)   | Senda greiðslubeiðni í netbanka               | UR-2.2       |
| [FR-3.1.1](functional_requirement.md#fr-311)   | Senda staðfestingu um að stæðisferli sé hafið | UR-3.1       |
| [FR-3.1.2](functional_requirement.md#fr-312)   | Finna kennitölu skráð eiganda                 | UR-3.1       |
| [FR-3.1.3](functional_requirement.md#fr-313)   | Senda tilkynningu á island.is                 | UR-3.1       |
| [FR-3.2.1](functional_requirement.md#fr-321)   | Hefja tilkynningarferli                       | UR-3.2       |
| [FR-3.2.2](functional_requirement.md#fr-322)   | Upplýsingar sem tilkynning inniheldur         | UR-3.2       |
| [FR-3.2.3](functional_requirement.md#fr-323)   | Tilkynna ef greiðsla er ógreidd eftir gjalddaga | UR-3.2     |

### 3.6 Viðskiptareglur
| ID                                | Titill                              |
|-------------------------------------|--------------------------------------|
| [BRG-1](business_rule.md#brg-1)   | BR-1 — Gjaldskrá eftir svæði og tíma       |
| [BRG-2](business_rule.md#brg-2)   | BR-2 — Ábyrgð notanda á réttum upplýsingum |

### 3.7 Gæðaeiginleikar
| ID                                    | Titill                                 |
|------------------------------------------|-------------------------------------------|
| [QA-1](quality_attribute.md#qa-1)     | Nákvæmni skráningar                    |
| [QA-2](quality_attribute.md#qa-2)     | Áreiðanleiki sendingar greiðslubeiðna  |

### 3.8 Takmarkanir
| ID                            | Titill                              |
|-----------------------------------|--------------------------------------|
| [C-1](constraint.md#c-1)      | Samhæfni við greiðslulausnir banka  |
| [C-2](constraint.md#c-2)      | Fylgni við persónuverndarlög        |

### 3.9 Ytri skil (Interfaces)
| ID                                    | Titill                                |
|------------------------------------------|-------------------------------------------|
| [UI-1](external_interface.md#ui-1)    | Tenging við Ísland.is                  |
| [UI-2](external_interface.md#ui-2)    | Tenging við greiðslugátt/netbanka      |

---

## 4. Viðaukar
### 4.1 Orðalisti
| Hugtak     | Skilgreining                                                  |
|------------|----------------------------------------------------------------|
| Stæðistími | Tíminn sem ökutæki stendur í stæði, frá komu til brottfarar    |
| Gjaldsvæði | Afmarkað svæði með sína eigin gjaldskrá                        |
| Netbanki   | Rafræn bankaþjónusta þar sem greiðslukröfur birtast notanda    |

### 4.2 Samþykktir
- Kennari: ____________________  
- Nemandi: Bali og Kristinn
