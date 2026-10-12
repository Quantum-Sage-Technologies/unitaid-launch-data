# Changelog

Every publish of `v1/dashboard.json`, newest first. Written by the publish workflow.

## 2026-10-12T10-37-04Z

12 changes for RBM's readers (published by @codebyjackson: Sources: public page links and raw-data addresses (PR #90)):

- `sources[clinicaltrials].dataUrl`: — → https://clinicaltrials.gov/api/v2/studies
- `sources[ema].dataUrl`: — → https://www.ema.europa.eu/en/documents/report/medicines-output-opinions_outside_eu-repo…
- `sources[nafdac].dataUrl`: — → http://greenbook.nafdac.gov.ng/
- `sources[tmda].url`: https://imis2.tmda.go.tz/portal/#/public/registered-medicines → https://imis2.tmda.go.tz/#/public/registered-medicines
- `sources[tmda].dataUrl`: — → https://imis2.tmda.go.tz/publicaccess/onSearchPublicRegisteredproducts
- `sources[dav].dataUrl`: — → https://dichvucong.dav.gov.vn/api/services/app/soDangKy/GetAllPublicServerPaging
- `sources[who-mft-guide].url`: https://iris.who.int/server/api/core/bitstreams/3429ad55-4291-4b1a-bdd9-783495692d9b/co… → https://www.who.int/publications/i/item/9789240103603
- `sources[who-mft-guide].alsoSee`: — → [{"label":{"en":"The PDF itself","fr":"Le PDF lui-même","pt":"O próprio PDF","es":"El p…
- `sources[who-pq-fpp].dataUrl`: — → https://extranet.who.int/prequal/medicines/prequalified/finished-pharmaceutical-product…
- `sources[zamra].url`: https://app.zamra.co.zm:42882/portal/publicaccess/onSearchPublicRegisteredproducts?sect… → https://app.zamra.co.zm:42882/portal/#/public/registered-medicines
- `sources[zamra].dataUrl`: — → https://app.zamra.co.zm:42882/portal/publicaccess/onSearchPublicRegisteredproducts
- `sources[mcaz].dataUrl`: — → https://onlineservices.mcaz.co.zw/onlineregister/Medicines/GetMedicinesByCategory?categ…

## 2026-10-08T14-54-47Z

1 change for RBM's readers (published by @codebyjackson: Add Spanish):

- language added: `es`, in all 501 texts (377 translated; the rest carry the English until they are)

## 2026-10-07T17-18-32Z

2 changes for RBM's readers (approval of proposal #38 by @codebyjackson):

- added `changelog`: 2026-10-08 · Each approved medicine now shows how many years late it is against the time each step is expected to take, with a new Time taken table. The expected times are LAUNCH's working estimates, except country registration, and are still to be agreed.
- `yardstick`: — → {"wholeYears":8,"expected":[null,null,{"years":2,"basis":"estimate"},{"years":1.5,"basi…

## 2026-10-06T10-50-09Z

46 changes for RBM's readers (published by @codebyjackson: Publish the latest data):

- `changelog[0].plain (fr)`: The country access map now shows only countries we can back with an official or peer-re… → La carte d'accès aux pays n'affiche désormais que les pays pour lesquels nous disposons…
- `changelog[0].plain (pt)`: The country access map now shows only countries we can back with an official or peer-re… → O mapa de acesso por país mostra agora apenas os países que podemos comprovar com uma f…
- `products[pyramax].flag (fr)`: Adoption is the current access barrier — strongly recommended by WHO since 2022 and on … → L'adoption constitue actuellement le principal obstacle à l'accès : fortement recommand…
- `products[pyramax].flag (pt)`: Adoption is the current access barrier — strongly recommended by WHO since 2022 and on … → A adoção é a atual barreira de acesso — fortemente recomendada pela OMS desde 2022 e pr…
- `products[pyramax].stages[4].note (fr)`: Confirmed in five national registers so far: Tanzania — 2 registrations (TMDA, issued 8… → Confirmé à ce jour dans cinq registres nationaux : Tanzanie — 2 enregistrements (TMDA, …
- `products[pyramax].stages[4].note (pt)`: Confirmed in five national registers so far: Tanzania — 2 registrations (TMDA, issued 8… → Confirmado em cinco registos nacionais até à data: Tanzânia — 2 registos (TMDA, emitido…
- `products[pyramax].detail.access[1] (fr)`: Registration confirmed in five national registers so far: Nigeria, Rwanda, Tanzania, Vi… → L'inscription a été confirmée à ce jour dans cinq registres nationaux : au Nigéria, au …
- `products[pyramax].detail.access[1] (pt)`: Registration confirmed in five national registers so far: Nigeria, Rwanda, Tanzania, Vi… → O registo foi confirmado até ao momento em cinco registos nacionais: Nigéria, Ruanda, T…
- `products[pyramax].detail.milestones[4].label (fr)`: 5 countries register-confirmed → 5 pays enregistrés
- `products[pyramax].detail.milestones[4].label (pt)`: 5 countries register-confirmed → 5 países com registo confirmado
- `products[pyramax].detail.milestones[4].date (fr)`: Rolling (VNM 2013, TZA 2022, NGA 2024, RWA 2024, ZMB 2025) → Roulant (VNM 2013, TZA 2022, NGA 2024, RWA 2024, ZMB 2025)
- `products[pyramax].detail.milestones[4].date (pt)`: Rolling (VNM 2013, TZA 2022, NGA 2024, RWA 2024, ZMB 2025) → Rolamento (VNM 2013, TZA 2022, NGA 2024, RWA 2024, ZMB 2025)
- `sources[who-wmr-annex-4b].label (fr)`: WHO national drug policy table → Tableau des politiques nationales en matière de médicaments de l'OMS
- `sources[who-wmr-annex-4b].label (pt)`: WHO national drug policy table → Tabela da política nacional de medicamentos da OMS
- `sources[who-wmr-annex-4b].alsoSee[0].label (fr)`: Annex 4B spreadsheet → Feuille de calcul de l'annexe 4B
- `sources[who-wmr-annex-4b].alsoSee[0].label (pt)`: Annex 4B spreadsheet → Ficha de trabalho do Anexo 4B
- `sources[who-wmr-annex-4b].plain (fr)`: Which malaria medicines each country's national treatment policy lists, and for which p… → Quels médicaments antipaludiques chaque pays répertorie-t-il dans sa politique national…
- `sources[who-wmr-annex-4b].plain (pt)`: Which malaria medicines each country's national treatment policy lists, and for which p… → Que medicamentos antimaláricos constam da lista das políticas nacionais de tratamento d…
- `sources[zamra].label (fr)`: Zambia: ZAMRA register → Zambie : registre de la ZAMRA
- `sources[zamra].label (pt)`: Zambia: ZAMRA register → Zâmbia: Registo ZAMRA
- `sources[zamra].plain (fr)`: The national register of every medicine approved for sale in Zambia. → Le registre national de tous les médicaments autorisés à la vente en Zambie.
- `sources[zamra].plain (pt)`: The national register of every medicine approved for sale in Zambia. → O registo nacional de todos os medicamentos aprovados para venda na Zâmbia.
- `sources[mcaz].label (fr)`: Zimbabwe: MCAZ register → Zimbabwe : Registre MCAZ
- `sources[mcaz].label (pt)`: Zimbabwe: MCAZ register → Zimbabué: Registo MCAZ
- `sources[mcaz].plain (fr)`: The national register of every medicine approved for sale in Zimbabwe. → Le registre national de tous les médicaments autorisés à la vente au Zimbabwe.
- `sources[mcaz].plain (pt)`: The national register of every medicine approved for sale in Zimbabwe. → O registo nacional de todos os medicamentos aprovados para venda no Zimbabué.
- `sources[dav].label (fr)`: Viet Nam: DAV register → Vietnam : Registre DAV
- `sources[dav].label (pt)`: Viet Nam: DAV register → Vietname: Registo DAV
- `sources[dav].plain (fr)`: The national register of every medicine approved for sale in Viet Nam. → Le registre national de tous les médicaments autorisés à la vente au Vietnam.
- `sources[dav].plain (pt)`: The national register of every medicine approved for sale in Viet Nam. → Registo nacional de todos os medicamentos aprovados para venda no Vietname.
- `sources[who-mft-guide].label (fr)`: WHO MFT implementation guide → Guide de mise en œuvre de l'OMS MFT
- `sources[who-mft-guide].label (pt)`: WHO MFT implementation guide → Guia de implementação da OMS MFT
- `sources[who-mft-guide].plain (fr)`: WHO's guide to using several first-line malaria treatments at once, with country examples. → Guide de l'OMS sur l'utilisation simultanée de plusieurs traitements antipaludiques de …
- `sources[who-mft-guide].plain (pt)`: WHO's guide to using several first-line malaria treatments at once, with country examples. → Guia da OMS sobre a utilização simultânea de vários tratamentos de primeira linha contr…
- `sources[bmjgh-rwanda-mft].label (fr)`: BMJ Global Health: Rwanda MFT, 2025 → BMJ Global Health : Rwanda MFT, 2025
- `sources[bmjgh-rwanda-mft].label (pt)`: BMJ Global Health: Rwanda MFT, 2025 → BMJ Global Health: Ruanda MFT, 2025
- `sources[bmjgh-rwanda-mft].plain (fr)`: How Rwanda uses several first-line malaria treatments, by region, to slow drug resistance. → Comment le Rwanda utilise, région par région, différents traitements de première intent…
- `sources[bmjgh-rwanda-mft].plain (pt)`: How Rwanda uses several first-line malaria treatments, by region, to slow drug resistance. → Como o Ruanda utiliza vários tratamentos de primeira linha contra a malária, por região…
- `sources[malariaj-burkina-mft].label (fr)`: Malaria Journal: Burkina Faso MFT, 2022 → Journal du paludisme : Burkina Faso MFT, 2022
- `sources[malariaj-burkina-mft].label (pt)`: Malaria Journal: Burkina Faso MFT, 2022 → Jornal da Malária: Burkina Faso MFT, 2022
- … and 6 more

## 2026-10-06T09-03-45Z

317 changes for RBM's readers (published by @codebyjackson: Hand publish of main 00354b1 while GitHub Actions is blocked (billing)):

- `stages[6]`: Procurement → Procurement (public channels)
- `stageInfo[0].source`: Trial registries and manufacturer announcements → Trial registries and manufacturer announcements
- `stageInfo[1].what`: A stringent regulator reviews the full evidence on quality, safety and effectiveness. F… → A stringent regulator reviews the full evidence on quality, safety and effectiveness. F…
- `stageInfo[1].source`: EMA registers → EMA registers
- `stageInfo[2].source`: WHO Guidelines for malaria → WHO Guidelines for malaria
- `stageInfo[3].source`: WHO prequalification list and EOI → WHO prequalification list and EOI
- `stageInfo[4].source`: National medicines registers → National medicines registers
- `stageInfo[5].source`: National treatment guidelines → National treatment guidelines
- `stageInfo[6].what`: Someone has to pay. Funders and governments run tenders, agree reference prices and for… → Someone has to pay. Funders and governments run tenders, agree reference prices and for…
- `stageInfo[6].source`: Global Fund price and quality reporting, PMI → Global Fund price and quality reporting, PMI
- `stageInfo[7].source`: Manufacturer and programme communications → Manufacturer and programme communications
- added `changelog`: 2026-10-06 · The country access map now shows only countries we can back with an official or peer-reviewed source. Some countries moved stage, some were added, and those we could not confirm now show No data. New sources include four national medicine registers and WHO's guide to using several first-line treatments. The country counts in each medicine's details now match the map.
- added `changelog`: 2026-10-02 · We changed some wording after reviewer feedback. The price card is gone, the procurement step is labelled as public channels only, and the page now says that health-authority review progress is usually not public. GanLum now credits Novartis as its developer, with the required acknowledgement of its funders, and the page has a disclaimer.
- added `changelog`: 2026-10-01 · We removed the drug-resistance results from the map. For that information, the page now points to the WHO Malaria Threats Map. The map's filters and legend have been tidied up, and you can now click any country to see its page.
- `products[ganlum].manufacturer`: Novartis · MMV → Novartis
- `products[ganlum].stages[0].date`: Announced 12 Nov 2025; trial completed 25 Nov 2025 → Announced 12 Nov 2025; trial completed 25 Nov 2025
- `products[ganlum].stages[0].nextDate`: — → —
- `products[ganlum].stages[1].date`: — → —
- `products[ganlum].stages[1].nextDate`: TBC → TBC
- `products[ganlum].stages[2].date`: — → —
- `products[ganlum].stages[2].nextDate`: — → —
- `products[ganlum].stages[3].date`: — → —
- `products[ganlum].stages[3].nextDate`: — → —
- `products[ganlum].stages[4].date`: — → —
- `products[ganlum].stages[4].nextDate`: — → —
- `products[ganlum].stages[5].date`: — → —
- `products[ganlum].stages[5].nextDate`: — → —
- `products[ganlum].stages[6].date`: — → —
- `products[ganlum].stages[6].nextDate`: — → —
- `products[ganlum].stages[7].date`: — → —
- `products[ganlum].stages[7].nextDate`: — → —
- removed `products[ganlum].detail.access`: Co-developed with MMV under access-oriented partnership
- `products[ganlum].detail.research.lead`: Novartis / MMV → Novartis
- `products[ganlum].detail.research.geographies`: 12 African countries (KALUMA trial sites) → 12 African countries (KALUMA trial sites)
- `products[ganlum].detail.research.timeline`: Phase III complete Nov 2025 → Phase III complete Nov 2025
- `products[ganlum].detail.milestones[0].date`: 12 Nov 2025 (trial completed 25 Nov 2025) → 12 Nov 2025 (trial completed 25 Nov 2025)
- `products[ganlum].detail.milestones[0].anticipated`: — → —
- `products[ganlum].detail.milestones[1].date`: — → —
- `products[ganlum].detail.milestones[1].anticipated`: TBC → TBC
- `products[ganlum].detail.milestones[2].date`: — → —
- … and 277 more

## 2026-10-02T07-17-55Z

6 changes for RBM's readers (published by @codebyjackson: Revert test):

- removed `changelog`: 2026-10-02 · GanLum — who pq listing was updated from the WHO prequalification list.
- `products[ganlum].stages[3].status`: done → idle
- `products[ganlum].stages[3].note`: Prequalified by WHO on 15 Sep 2026 (WHO ref TEST-0001, Novartis Pharma AG). → Not on the WHO PQ EOI list yet (24th malaria EOI, 27 Feb 2026, checked)
- `products[ganlum].stages[3].date`: 15 Sep 2026 → —
- `products[ganlum].stages[3].source`: WHO prequalification list (TEST-0001 — https://extranet.who.int/prequal/medicines/prequ… → WHO PQ EOI list (24th edition)
- `products[ganlum].stages[3].asOf`: 2026-09-21 → 2026-08-22

## 2026-10-02T07-08-24Z

6 changes for RBM's readers (approval of proposal #41 by @codebyjackson):

- added `changelog`: 2026-10-02 · GanLum — who pq listing was updated from the WHO prequalification list.
- `products[ganlum].stages[3].status`: idle → done
- `products[ganlum].stages[3].note`: Not on the WHO PQ EOI list yet (24th malaria EOI, 27 Feb 2026, checked) → Prequalified by WHO on 15 Sep 2026 (WHO ref TEST-0001, Novartis Pharma AG).
- `products[ganlum].stages[3].date`: — → 15 Sep 2026
- `products[ganlum].stages[3].source`: WHO PQ EOI list (24th edition) → WHO prequalification list (TEST-0001 — https://extranet.who.int/prequal/medicines/prequ…
- `products[ganlum].stages[3].asOf`: 2026-08-22 → 2026-09-21

## 2026-10-01T19-08-26Z

6 changes for RBM's readers (published by @codebyjackson: Revert test proposal #38):

- removed `changelog`: 2026-10-01 · GanLum — who pq listing was updated from the WHO prequalification list.
- `products[ganlum].stages[3].status`: done → idle
- `products[ganlum].stages[3].note`: Prequalified by WHO on 15 Sep 2026 (WHO ref TEST-0001, Novartis Pharma AG). → Not on the WHO PQ EOI list yet (24th malaria EOI, 27 Feb 2026, checked)
- `products[ganlum].stages[3].date`: 15 Sep 2026 → —
- `products[ganlum].stages[3].source`: WHO prequalification list (TEST-0001 — https://extranet.who.int/prequal/medicines/prequ… → WHO PQ EOI list (24th edition)
- `products[ganlum].stages[3].asOf`: 2026-09-21 → 2026-08-22

## 2026-10-01T18-54-58Z

6 changes for RBM's readers (approval of proposal #38 by @codebyjackson):

- added `changelog`: 2026-10-01 · GanLum — who pq listing was updated from the WHO prequalification list.
- `products[ganlum].stages[3].status`: idle → done
- `products[ganlum].stages[3].note`: Not on the WHO PQ EOI list yet (24th malaria EOI, 27 Feb 2026, checked) → Prequalified by WHO on 15 Sep 2026 (WHO ref TEST-0001, Novartis Pharma AG).
- `products[ganlum].stages[3].date`: — → 15 Sep 2026
- `products[ganlum].stages[3].source`: WHO PQ EOI list (24th edition) → WHO prequalification list (TEST-0001 — https://extranet.who.int/prequal/medicines/prequ…
- `products[ganlum].stages[3].asOf`: 2026-08-22 → 2026-09-21

## 2026-10-01T18-24-39Z

53 changes for RBM's readers (published by @codebyjackson: Revert test proposal #35):

- `changelog[0].date`: 2026-10-01 → 2026-09-10
- `changelog[0].product`: GanLum → All
- `changelog[0].plain`: GanLum — who pq listing was updated from the WHO prequalification list. → We now call a blocked step an "access barrier" instead of a "bottleneck". Only the word…
- `changelog[1].date`: 2026-09-10 → 2026-09-08
- `changelog[1].product`: All → ASPY
- `changelog[1].plain`: We now call a blocked step an "access barrier" instead of a "bottleneck". Only the word… → We found a real example of a country acting on the World Health Organization's advice: …
- `changelog[2].date`: 2026-09-08 → 2026-09-05
- `changelog[2].product`: ASPY → All
- `changelog[2].plain`: We found a real example of a country acting on the World Health Organization's advice: … → null
- `changelog[3].date`: 2026-09-05 → 2026-08-25
- `changelog[3].plain`: null → Everything we checked during the August review is now part of the main dataset. The sep…
- `changelog[4].date`: 2026-08-25 → 2026-08-23
- `changelog[4].product`: All → DHA–PPQ
- `changelog[4].plain`: Everything we checked during the August review is now part of the main dataset. The sep… → We checked Nigeria's and Tanzania's official medicine registers. Tanzania lists 10 appr…
- `changelog[5].product`: DHA–PPQ → ASPY
- `changelog[5].plain`: We checked Nigeria's and Tanzania's official medicine registers. Tanzania lists 10 appr… → We checked the official medicine registers: Tanzania approved this medicine in 2022, an…
- `changelog[6].product`: ASPY → DHA–PPQ
- `changelog[6].plain`: We checked the official medicine registers: Tanzania approved this medicine in 2022, an… → We corrected the year the World Health Organization first recommended this medicine. It…
- `changelog[7].product`: DHA–PPQ → ALAQ
- `changelog[7].plain`: We corrected the year the World Health Organization first recommended this medicine. It… → We updated the name of the main trial and reworded how we describe the medicine, so bot…
- `changelog[8].product`: ALAQ → GanLum
- `changelog[8].plain`: We updated the name of the main trial and reworded how we describe the medicine, so bot… → We reworded how we describe this medicine to match the manufacturer's own words: the fi…
- `changelog[9].product`: GanLum → All
- `changelog[9].plain`: We reworded how we describe this medicine to match the manufacturer's own words: the fi… → First batch of updates drawn from public databases — Global Fund purchasing records, Wo…
- `changelog[10].product`: All → DHA–PPQ
- `changelog[10].plain`: First batch of updates drawn from public databases — Global Fund purchasing records, Wo… → Purchasing figures added: the Global Fund has bought 11.5 million packs (US$41.5m) sinc…
- `changelog[11].product`: DHA–PPQ → ASPY
- `changelog[11].plain`: Purchasing figures added: the Global Fund has bought 11.5 million packs (US$41.5m) sinc… → Purchasing figures added: the Global Fund has bought 940,000 packs (US$14.5m) since 201…
- `changelog[12].product`: ASPY → GanLum
- `changelog[12].plain`: Purchasing figures added: the Global Fund has bought 940,000 packs (US$14.5m) since 201… → The main trial finished on 25 November 2025 with 1,720 participants — now confirmed fro…
- `changelog[13].date`: 2026-08-23 → 2026-08-15
- `changelog[13].product`: GanLum → All
- `changelog[13].plain`: The main trial finished on 25 November 2025 with 1,720 participants — now confirmed fro… → Added a poster view showing where each medicine sits in development.
- `changelog[14].plain`: Added a poster view showing where each medicine sits in development. → Added a country map, a chart of how long each step takes, a shareable widget, an update…
- `changelog[15].date`: 2026-08-15 → 2026-08-14
- `changelog[15].product`: All → ASPY
- `changelog[15].plain`: Added a country map, a chart of how long each step takes, a shareable widget, an update… → Renamed from Pyramax to ASPY. The brand name still appears underneath.
- `changelog[16].product`: ASPY → All
- `changelog[16].plain`: Renamed from Pyramax to ASPY. The brand name still appears underneath. → Added plain-language definitions, a download button, a print view, and the time taken b…
- `changelog[17].product`: All → GanLum
- … and 13 more

## 2026-10-01T18-08-30Z

53 changes for RBM's readers (approval of proposal #35 by @codebyjackson):

- `changelog[0].date`: 2026-09-10 → 2026-10-01
- `changelog[0].product`: All → GanLum
- `changelog[0].plain`: We now call a blocked step an "access barrier" instead of a "bottleneck". Only the word… → GanLum — who pq listing was updated from the WHO prequalification list.
- `changelog[1].date`: 2026-09-08 → 2026-09-10
- `changelog[1].product`: ASPY → All
- `changelog[1].plain`: We found a real example of a country acting on the World Health Organization's advice: … → We now call a blocked step an "access barrier" instead of a "bottleneck". Only the word…
- `changelog[2].date`: 2026-09-05 → 2026-09-08
- `changelog[2].product`: All → ASPY
- `changelog[2].plain`: null → We found a real example of a country acting on the World Health Organization's advice: …
- `changelog[3].date`: 2026-08-25 → 2026-09-05
- `changelog[3].plain`: Everything we checked during the August review is now part of the main dataset. The sep… → null
- `changelog[4].date`: 2026-08-23 → 2026-08-25
- `changelog[4].product`: DHA–PPQ → All
- `changelog[4].plain`: We checked Nigeria's and Tanzania's official medicine registers. Tanzania lists 10 appr… → Everything we checked during the August review is now part of the main dataset. The sep…
- `changelog[5].product`: ASPY → DHA–PPQ
- `changelog[5].plain`: We checked the official medicine registers: Tanzania approved this medicine in 2022, an… → We checked Nigeria's and Tanzania's official medicine registers. Tanzania lists 10 appr…
- `changelog[6].product`: DHA–PPQ → ASPY
- `changelog[6].plain`: We corrected the year the World Health Organization first recommended this medicine. It… → We checked the official medicine registers: Tanzania approved this medicine in 2022, an…
- `changelog[7].product`: ALAQ → DHA–PPQ
- `changelog[7].plain`: We updated the name of the main trial and reworded how we describe the medicine, so bot… → We corrected the year the World Health Organization first recommended this medicine. It…
- `changelog[8].product`: GanLum → ALAQ
- `changelog[8].plain`: We reworded how we describe this medicine to match the manufacturer's own words: the fi… → We updated the name of the main trial and reworded how we describe the medicine, so bot…
- `changelog[9].product`: All → GanLum
- `changelog[9].plain`: First batch of updates drawn from public databases — Global Fund purchasing records, Wo… → We reworded how we describe this medicine to match the manufacturer's own words: the fi…
- `changelog[10].product`: DHA–PPQ → All
- `changelog[10].plain`: Purchasing figures added: the Global Fund has bought 11.5 million packs (US$41.5m) sinc… → First batch of updates drawn from public databases — Global Fund purchasing records, Wo…
- `changelog[11].product`: ASPY → DHA–PPQ
- `changelog[11].plain`: Purchasing figures added: the Global Fund has bought 940,000 packs (US$14.5m) since 201… → Purchasing figures added: the Global Fund has bought 11.5 million packs (US$41.5m) sinc…
- `changelog[12].product`: GanLum → ASPY
- `changelog[12].plain`: The main trial finished on 25 November 2025 with 1,720 participants — now confirmed fro… → Purchasing figures added: the Global Fund has bought 940,000 packs (US$14.5m) since 201…
- `changelog[13].date`: 2026-08-15 → 2026-08-23
- `changelog[13].product`: All → GanLum
- `changelog[13].plain`: Added a poster view showing where each medicine sits in development. → The main trial finished on 25 November 2025 with 1,720 participants — now confirmed fro…
- `changelog[14].plain`: Added a country map, a chart of how long each step takes, a shareable widget, an update… → Added a poster view showing where each medicine sits in development.
- `changelog[15].date`: 2026-08-14 → 2026-08-15
- `changelog[15].product`: ASPY → All
- `changelog[15].plain`: Renamed from Pyramax to ASPY. The brand name still appears underneath. → Added a country map, a chart of how long each step takes, a shareable widget, an update…
- `changelog[16].product`: All → ASPY
- `changelog[16].plain`: Added plain-language definitions, a download button, a print view, and the time taken b… → Renamed from Pyramax to ASPY. The brand name still appears underneath.
- `changelog[17].product`: GanLum → All
- … and 13 more

## 2026-10-01T17-54-22Z

First publish (published by @codebyjackson: First publish).

4 products, 22 sources, schema v1.
