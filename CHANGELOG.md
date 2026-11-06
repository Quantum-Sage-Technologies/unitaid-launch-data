# Changelog

Every publish of `v1/dashboard.json`, newest first. Written by the publish workflow.

## 2026-11-06T07-23-56Z

9 changes for RBM's readers (published by @codebyjackson: Stage 2 names, timeline dots, no today; GanLum shown as Ganaplacide-lumefantrine / KLU156 (PRs #154, #155, #156)):

- `stages[1]`: Stringent Regulatory Review (SRA) → Stringent Regulatory Approval (SRA)
- `stageInfo[1].doneName`: Stringent Regulatory Approval (SRA) → —
- `stageInfo[1].pendingName`: — → Stringent Regulatory Review (SRA)
- added `changelog`: 2026-11-06 · This medicine is now listed under its full name, Ganaplacide–lumefantrine, with its development code KLU156. It was listed as GanLum.
- added `changelog`: 2026-11-06 · The second step is called "Stringent Regulatory Approval (SRA)". A medicine that has not yet completed it shows "Stringent Regulatory Review (SRA)" instead, and Ganaplacide–lumefantrine shows "Stringent Health Authority Review (SRA)". No dates, statuses or figures changed.
- removed `changelog`: 2026-11-06 · The second step is now called "Stringent Regulatory Review (SRA)" while a medicine is still waiting for approval, and "Stringent Regulatory Approval (SRA)" once it has been approved. No dates, statuses or figures changed.
- `products[ganlum].name`: GanLum → Ganaplacide–lumefantrine
- `products[ganlum].inn`: Ganaplacide–lumefantrine (KLU156) → KLU156
- `products[ganlum].stages[1].pendingName`: — → Stringent Health Authority Review (SRA)

## 2026-11-06T05-53-35Z

3 changes for RBM's readers (published by @codebyjackson: Stage 2: Stringent Regulatory Review (SRA) until completed (PR #153)):

- `stages[1]`: Stringent Regulatory Approval (SRA) → Stringent Regulatory Review (SRA)
- `stageInfo[1].doneName`: — → Stringent Regulatory Approval (SRA)
- added `changelog`: 2026-11-06 · The second step is now called "Stringent Regulatory Review (SRA)" while a medicine is still waiting for approval, and "Stringent Regulatory Approval (SRA)" once it has been approved. No dates, statuses or figures changed.

## 2026-11-05T11-27-24Z

34 changes for RBM's readers (published by @KylerXiv: Unitaid feedback 5 Nov 2026: procurement figures parked (presentations only), class label removed, translators' wording (PRs #148, #149)):

- added `changelog`: 2026-11-05 · Procurement figures are withdrawn while they are reviewed. Each medicine's procurement section lists the presentations bought through Global Fund-financed orders, and the figures will be added again once they are confirmed.
- added `changelog`: 2026-10-15 · We updated the name of WHO's malaria department to the Department of Malaria and Neglected Tropical Diseases (MNT). The country counts for ASPY and DHA–PPQ now match the country access map, and we show how many countries a national medicines register confirms. We removed the years-late figures until the way they are worked out is agreed; the expected time for each stage stays. ALAQ's description now says it is still in clinical development and that its future role depends on trial results, regulators, WHO and countries. ASPY's description now says that registration and adoption vary by country and that LAUNCH is checking them country by country. For DHA–PPQ we explain what its share of Global Fund orders is measured against, describe its uses more carefully, and corrected Nigeria's count of active registrations from 26 to 25. No dates or statuses changed.
- added `changelog`: 2026-09-08 · We found a real example of a country acting on the World Health Organization's advice: Ghana added this medicine as a backup first-choice treatment in 2022. It's still the only country confirmed to have done so. We also recorded the years Global Fund purchasing began for both recommended medicines (2018 and 2008).
- added `changelog`: 2026-08-23 · Global Fund purchasing figures were added (orders since 2008). Nine versions of the medicine have passed World Health Organization quality checks.
- added `changelog`: 2026-08-23 · Global Fund purchasing figures were added (orders since 2018). The European medicines decision date is now recorded.
- removed `changelog`: 2026-10-15 · We updated the name of WHO's malaria department to the Department of Malaria and Neglected Tropical Diseases (MNT). The country counts for ASPY and DHA–PPQ now match the country access map, and we show how many countries a national medicines register confirms. We removed the years-late figures until the way they are worked out is agreed; the expected time for each stage stays. ALAQ's description now says it is still in clinical development and that its future role depends on trial results, regulators, WHO and countries. ASPY's description now says that registration and adoption vary by country and that LAUNCH is checking them country by country. For DHA–PPQ we explain what the 0.9–4.5% is a share of, describe its uses more carefully, and corrected Nigeria's count of active registrations from 26 to 25. No dates or statuses changed.
- removed `changelog`: 2026-09-08 · We found a real example of a country acting on the World Health Organization's advice: Ghana added this medicine as a backup first-choice treatment in 2022. It's still the only country confirmed to have done so. We also recorded the years Global Fund purchasing began for both underused medicines (2018 and 2008).
- removed `changelog`: 2026-08-23 · Purchasing figures added: the Global Fund has bought 11.5 million packs (US$41.5m) since 2008, with a sharp rise in 2025. Nine versions of the medicine have passed World Health Organization quality checks.
- removed `changelog`: 2026-08-23 · Purchasing figures added: the Global Fund has bought 940,000 packs (US$14.5m) since 2018, most of it in 2025 for Uganda and Burkina Faso. The European medicines decision date is now recorded.
- `products[pyramax].classLabel`: Recommended · underutilized → WHO-recommended
- `products[pyramax].stages[6].note`: Global Fund procurement 2018–2025: 68 transactions, US$14.5m — modest overall, but US$1… → Bought through Global Fund-financed procurement since 2018. The procurement figures are…
- `products[pyramax].stages[6].next`: Verify 2025 surge holds in next quarterly PQR extract → Procurement figures to be added after review
- `products[pyramax].stages[6].nextDate`: Q4 2026 → TBC
- `products[pyramax].detail.volume`: {"total":{"en":"68 transactions · US$14.5m (2018–2025)","fr":"68 transactions · 14,5 mi… → null
- `products[pyramax].detail.milestones[7].label`: US$14.5m, 68 transactions (GF, to 2025) → Figures under review
- `products[pyramax].detail.milestones[7].date`: US$11.6m in 2025 → Since 2018
- `products[pyramax].detail.milestones[7].next`: Verify surge in next PQR extract → Figures to be added after review
- `products[pyramax].detail.milestones[7].anticipated`: Q4 2026 → TBC
- `products[pyramax].detail.volumeNote`: — → Procurement figures are being reviewed and will be added later.
- `products[pyramax].detail.procurement`: — → {"presentations":[{"en":"20/60 mg granules · 90 sachets","fr":"Granulés de 20/60 mg · 9…
- `products[dhappq].classLabel`: Recommended · underutilized → WHO-recommended
- `products[dhappq].flag`: Procurement is the current access barrier — 0.9–4.5% of the value of all antimalarial m… → Procurement is the current access barrier, despite a WHO recommendation dating to 2010.…
- `products[dhappq].barrier`: Only 0.9–4.5% of Global Fund antimalarial orders by value, 2022–24 → Procurement; figures under review
- `products[dhappq].stages[6].note`: Global Fund orders go back to 2008 (US$41.5m over 234 transactions, 2008–2026), but hav… → Bought through Global Fund-financed procurement since 2008; the timeline counts from WH…
- `products[dhappq].stages[6].next`: Verify 2025 surge holds in next quarterly PQR extract → Procurement figures to be added after review
- `products[dhappq].stages[6].nextDate`: Q4 2026 → TBC
- `products[dhappq].detail.price.note`: Pooled procurement reference pricing to be displayed once confirmed for release; PQR me… → Pooled procurement reference pricing to be displayed once confirmed for release
- `products[dhappq].detail.volume`: {"total":{"en":"234 transactions · US$41.5m (2008–2026)","fr":"234 transactions · 41,5 … → null
- `products[dhappq].detail.milestones[9].label`: US$41.5m since 2008 → Figures under review
- `products[dhappq].detail.milestones[9].date`: US$15.3m in 2025 → Since 2008
- `products[dhappq].detail.milestones[9].next`: Verify surge in next PQR extract → Figures to be added after review
- `products[dhappq].detail.milestones[9].anticipated`: Q4 2026 → TBC
- `products[dhappq].detail.volumeNote`: — → Procurement figures are being reviewed and will be added later.
- `products[dhappq].detail.procurement`: — → {"presentations":[{"en":"20/160 mg dispersible tablets · blister of 3","fr":"Comprimés …

## 2026-11-04T16-41-40Z

669 changes for RBM's readers (published by @codebyjackson: French and Brazilian Portuguese from the professional translators):

- `stages[0] (fr)`: Recherche et développement et clinique → R&D et essais cliniques
- `stages[0] (pt)`: P&D e Clínica → P&D e Área Clínica
- `stages[1] (fr)`: Approbation réglementaire rigoureuse (SRA) → Approbation d’une autorité de réglementation rigoureuse (SRA)
- `stages[1] (pt)`: Aprovação regulatória rigorosa (SRA) → Aprovação Regulatória Rigorosa (SRA)
- `stages[2] (fr)`: Recommandation de l'OMS → Recommandation de l’OMS
- `stages[3] (fr)`: Liste OMS PQ → Préqualification de l’OMS
- `stages[3] (pt)`: Lista da OMS PQ → Listagem de pré-qualificação da OMS
- `stages[4] (fr)`: Enregistrement du pays → Enregistrement national
- `stages[4] (pt)`: Registro do país → Registro de país
- `stages[5] (fr)`: adoption de la politique nationale → Inscription dans les politiques nationales
- `stages[6] (fr)`: Achats (voies publiques) → Achats (canaux publics)
- `stages[6] (pt)`: Licitações (canais públicos) → Aquisição (canais públicos)
- `stages[7] (fr)`: Livraison à l'intérieur du pays → Mise en œuvre dans le pays
- `stages[7] (pt)`: Entrega no país → Distribuição no país de destino
- `stageInfo[0].what (fr)`: La découverte en laboratoire est suivie de trois phases d'essais cliniques : une premiè… → Les recherches en laboratoire sont suivies de trois phases d’essais cliniques : une pou…
- `stageInfo[0].what (pt)`: A descoberta em laboratório é seguida por três rodadas de testes em humanos: primeiro p… → Descoberta em laboratório, seguida de três fases de ensaios clínicos em seres humanos: …
- `stageInfo[0].who (fr)`: Le fabricant, souvent dans le cadre d'un partenariat de développement de produits tel q… → Le fabricant, souvent dans le cadre d’un partenariat de développement de produit tel qu…
- `stageInfo[0].who (pt)`: O fabricante, geralmente em parceria para desenvolvimento de produtos, como MMV → O fabricante, frequentemente em parceria com uma organização de desenvolvimento de prod…
- `stageInfo[0].stall (fr)`: Recruter suffisamment de patients et mettre en place des centres d'essais cliniques dan… → Recruter suffisamment de patients et mener des essais dans plusieurs pays.
- `stageInfo[0].stall (pt)`: Recrutar pacientes suficientes e realizar ensaios clínicos em diversos países. → Recrutar um número suficiente de pacientes e conduzir ensaios clínicos em vários países.
- `stageInfo[0].source (fr)`: Registres d'essais cliniques et annonces des fabricants → Les registres d’essais cliniques et les communiqués des fabricants.
- `stageInfo[0].source (pt)`: Registros de ensaios clínicos e comunicados dos fabricantes → Registros de ensaios clínicos e comunicados de fabricantes.
- `stageInfo[1].what (fr)`: Un organisme de réglementation rigoureux examine l'ensemble des données probantes relat… → Une autorité de réglementation rigoureuse examine l’ensemble des données probantes sur …
- `stageInfo[1].what (pt)`: Uma entidade reguladora rigorosa analisa todas as evidências sobre a qualidade, seguran… → Uma autoridade reguladora rigorosa analisa todas as evidências relativas à qualidade, s…
- `stageInfo[1].who (fr)`: L'EMA, ou un autre organisme de réglementation rigoureux comme la FDA américaine, → L’EMA, ou une autre autorité de réglementation rigoureuse comme la Food and Drug Admini…
- `stageInfo[1].who (pt)`: EMA, ou outro órgão regulador rigoroso como o FDA dos EUA. → EMA ou outra autoridade reguladora rigorosa, como a FDA dos EUA.
- `stageInfo[1].stall (fr)`: Préparer le dossier complet, puis attendre l'examen. → Préparer l’ensemble du dossier, puis attendre la fin de l’examen.
- `stageInfo[1].stall (pt)`: Preparar o dossiê completo e depois aguardar a revisão. → Preparar o dossiê completo e, em seguida, aguardar a conclusão da análise.
- `stageInfo[1].source (fr)`: EMA enregistre → Les registres de l’EMA.
- `stageInfo[2].stall (fr)`: Le groupe se réunit selon son propre calendrier, il est donc difficile de prévoir les d… → Ce groupe se réunit à sa propre convenance, il est donc difficile d’anticiper des délai…
- `stageInfo[2].stall (pt)`: O grupo se reúne de acordo com seu próprio calendário, então é difícil prever o horário. → O grupo se reúne de acordo com seu próprio calendário, por isso é difícil prever quando…
- `stageInfo[3].who (fr)`: Équipe de préqualification de l'OMS → L’équipe de préqualification de l’OMS
- `stageInfo[3].who (pt)`: Equipe de pré-qualificação da OMS → Equipe de Pré-qualificação da OMS
- `stageInfo[3].stall (fr)`: En attente d'une invitation, puis des inspections. → Attendre un nouveau cycle d’invitation, puis les inspections.
- `stageInfo[3].stall (pt)`: Aguardando convites para a rodada de visitas, e depois as inspeções. → Aguardar uma rodada de convites e, em seguida, as inspeções.
- `stageInfo[3].source (fr)`: Liste de préqualification de l'OMS et déclaration d'intérêt → La liste de préqualification de l’OMS et l’appel à manifestation d’intérêt.
- `stageInfo[3].source (pt)`: Lista de pré-qualificação da OMS e Manifestação de Interesse → Lista de pré-qualificação e Manifestação de Interesse da OMS
- `stageInfo[4].what (fr)`: Chaque organisme de réglementation national délivre une autorisation de mise sur le mar… → L’autorité de réglementation de chaque pays délivre une autorisation de mise sur le mar…
- `stageInfo[4].what (pt)`: Cada órgão regulador nacional licencia o medicamento antes que ele possa ser vendido ou… → A autoridade reguladora de cada país autoriza o medicamento antes que ele possa ser com…
- `stageInfo[4].who (fr)`: organismes nationaux de réglementation des médicaments → Les autorités nationales de réglementation des médicaments.
- … and 629 more

## 2026-11-03T13-00-15Z

131 changes for RBM's readers (published by @codebyjackson: Partner feedback: map shows one access stage at a time; registrations from 14 more national registers (DHA–PPQ 20, ASPY 14); dated timeline; STOP-AMDR; Market/Country Access; WHO GDG wording):

- `stageInfo[2].what`: A WHO expert group weighs clinical evidence and decides whether the medicine is include… → WHO's Guideline Development Group (GDG) for malaria reviews the graded evidence (GRADE)…
- `stageInfo[2].who`: WHO Department of Malaria and Neglected Tropical Diseases (MNT) and its Guidelines Deve… → WHO Department of Malaria and Neglected Tropical Diseases (MNT) and its Guideline Devel…
- `stageInfo[2].source`: WHO Guidelines for malaria → WHO Guidelines for malaria; WHO handbook for guideline development, 2nd ed. (2014), p. 130
- `stageInfo[3].what`: A separate WHO check of quality and manufacturing, including factory inspections. Prequ… → A separate WHO check of quality and manufacturing, including factory inspections. Prequ…
- `glossary.GDG`: Guidelines Development Group — the WHO expert group that reviews evidence and formulate… → Guideline Development Group — the group WHO convenes to make the recommendations in a W…
- added `changelog`: 2026-11-03 · We checked the official medicine registers of 14 more countries. DHA–PPQ is now confirmed as registered in 20 countries and ASPY in 14. The map also shows Uganda and DR Congo, where the STOP-AMDR project plans to use these medicines.
- added `changelog`: 2026-11-03 · The research sections for ASPY and DHA–PPQ now mention STOP-AMDR, a Unitaid-funded project in six African countries, and which of those countries have plans to use each medicine. The disclaimer and the procurement note now say more clearly that the figures are the best information available and that Global Fund orders are not all public purchases.
- added `changelog`: 2026-11-03 · The medicines table now has separate Market Access and Country Access columns, so you can see which medicines have reached market access. We describe what WHO's Guideline Development Group does using WHO's own handbook, and say that the prequalification step described is the one for medicines.
- added `changelog`: 2026-11-03 · The country access map now shows one stage at a time: choose Registered, In national guidelines or In MFT plans. Each view shows every country we have a source for at that stage, so a country can appear in more than one. This means the map and the text now give the same numbers: for example, DHA–PPQ is registered in 6 countries on the map, as the text says.
- added `changelog`: 2026-11-03 · The timelines now show when ASPY and DHA–PPQ were first registered in a country (Viet Nam, 2013 and 2010), which was before WHO recommended ASPY and before DHA–PPQ was prequalified. ASPY's procurement since 2018 is now on its timeline too, and both medicines list their MFT pilots.
- added `changelog`: 2026-11-03 · For ASPY we now mention that its makers report it is registered in 29 countries, and what a 2023 trial paper says about where the tablets and granules are registered, and for DHA–PPQ that Pierre Fabre has had a licence to sell Eurartesim in 32 African countries since 2015. Both are the companies' own statements; the map still shows only countries we could check in an official register or publication.
- added `changelog`: 2026-11-03 · We now call the WHO group that recommends a medicine by its official name, the Guideline Development Group (GDG), and explain what it does for malaria medicines.
- `products[pyramax].flag`: Adoption is the current access barrier — strongly recommended by WHO since 2022 and on … → Adoption is the current access barrier — strongly recommended by WHO since 2022 and on …
- `products[pyramax].stages[4].note`: Confirmed in five national registers so far: Tanzania — 2 registrations (TMDA, issued 8… → Confirmed in 14 national registers so far: Benin, Burkina Faso, Cameroon, DR Congo, Eth…
- `products[pyramax].stages[4].date`: Rolling → Since 2013 (Viet Nam, the earliest registration on the national registers checked); rol…
- `products[pyramax].stages[4].source`: NAFDAC, TMDA, Rwanda FDA, ZAMRA and DAV registers → National registers of 14 countries (see the country access map); MMV and Shin Poong, No…
- `products[pyramax].stages[4].asOf`: 2026-10-05 → 2026-11-03
- added `products[pyramax].stages[4].sources`: abmed-benin
- added `products[pyramax].stages[4].sources`: fasofda-burkina
- added `products[pyramax].stages[4].sources`: dpml-cameroon
- added `products[pyramax].stages[4].sources`: acorep-drc
- added `products[pyramax].stages[4].sources`: efda-ethiopia
- added `products[pyramax].stages[4].sources`: ppb-kenya
- added `products[pyramax].stages[4].sources`: anarme-mozambique
- added `products[pyramax].stages[4].sources`: fda-myanmar
- added `products[pyramax].stages[4].sources`: arp-senegal
- added `products[pyramax].stages[4].sources`: mmv-shinpoong-pyramax-2022
- added `products[pyramax].stages[4].sources`: bmjopen-pyrapreg-2023
- `products[pyramax].stages[5].note`: In national guidelines in 7 countries on the country access map, and in MFT plans in 4 … → In national guidelines in 9 countries on the country access map, three of them (Nigeria…
- added `products[pyramax].detail.access`: Registration confirmed in 14 national registers so far: Benin, Burkina Faso, Cameroon, …
- added `products[pyramax].detail.access`: MMV and Shin Poong reported registration in 29 countries in Africa and Asia (November 2…
- added `products[pyramax].detail.access`: The PYRAPREG trial protocol (BMJ Open, 2023) reports the tablets registered in 19 Afric…
- removed `products[pyramax].detail.access`: Registration confirmed in five national registers so far: Nigeria, Rwanda, Tanzania, Vi…
- `products[pyramax].detail.research.lead`: MMV and partners → MMV and partners (efficacy studies); Jhpiego, funded by Unitaid (STOP-AMDR)
- `products[pyramax].detail.research.geographies`: Ghana, Vietnam, Burkina Faso and others (efficacy studies) → Efficacy studies: Ghana, Viet Nam, Burkina Faso and others. STOP-AMDR (2025–2029): Burk…
- `products[pyramax].detail.research.timeline`: Ongoing → Ongoing; STOP-AMDR 2025–2029
- `products[pyramax].detail.country.registered`: 2 → 14
- `products[pyramax].detail.country.inGuidelines`: 7 → 9
- `products[pyramax].detail.country.inMft`: 4 → 6
- `products[pyramax].detail.countries.note`: Every country listed is cited to a national medicines regulator's own register, a WHO p… → Every country listed is cited to a national medicines regulator's own register, a WHO p…
- … and 91 more

## 2026-10-28T16-27-03Z

240 changes for RBM's readers (published by @codebyjackson: Portuguese is now Brazilian (pt-BR), as RBM's site):

- `stages[0] (pt)`: I&D e Clínica → P&D e Clínica
- `stages[1] (pt)`: Aprovação regulamentar rigorosa (SRA) → Aprovação regulatória rigorosa (SRA)
- `stages[4] (pt)`: Registo de país → Registro do país
- `stages[6] (pt)`: Concursos (canais públicos) → Licitações (canais públicos)
- `stageInfo[0].what (pt)`: A descoberta em laboratório é seguida por três rondas de testes em humanos: primeiro pa… → A descoberta em laboratório é seguida por três rodadas de testes em humanos: primeiro p…
- `stageInfo[0].who (pt)`: O fabricante, geralmente em parceria para o desenvolvimento de produtos, como o MMV → O fabricante, geralmente em parceria para desenvolvimento de produtos, como MMV
- `stageInfo[0].stall (pt)`: Recrutar doentes suficientes e realizar ensaios clínicos em diversos países. → Recrutar pacientes suficientes e realizar ensaios clínicos em diversos países.
- `stageInfo[0].source (pt)`: Registos de ensaios clínicos e comunicados dos fabricantes → Registros de ensaios clínicos e comunicados dos fabricantes
- `stageInfo[1].what (pt)`: Uma entidade reguladora rigorosa analisa todas as evidências sobre a qualidade, seguran… → Uma entidade reguladora rigorosa analisa todas as evidências sobre a qualidade, seguran…
- `stageInfo[1].who (pt)`: EMA, ou outro organismo regulador rigoroso como a FDA dos EUA. → EMA, ou outro órgão regulador rigoroso como o FDA dos EUA.
- `stageInfo[1].stall (pt)`: Preparar o dossier completo e depois aguardar a revisão. → Preparar o dossiê completo e depois aguardar a revisão.
- `stageInfo[1].source (pt)`: Registos da EMA → Registros da EMA
- `stageInfo[2].what (pt)`: Um grupo de peritos da OMS avalia as provas clínicas e decide se o medicamento será inc… → Um grupo de especialistas da OMS avalia as evidências clínicas e decide se o medicament…
- `stageInfo[2].who (pt)`: Departamento de Malária e Doenças Tropicais Negligenciadas (MNT) da OMS e o seu Grupo d… → Departamento de Malária e Doenças Tropicais Negligenciadas (MNT) da OMS e seu Grupo de …
- `stageInfo[2].stall (pt)`: O grupo reúne-se de acordo com o seu próprio calendário, pelo que é difícil prever o ho… → O grupo se reúne de acordo com seu próprio calendário, então é difícil prever o horário.
- `stageInfo[2].source (pt)`: Orientações da OMS para a malária → Diretrizes da OMS para a malária
- `stageInfo[3].what (pt)`: Uma verificação independente da OMS sobre a qualidade e o fabrico, incluindo inspeções … → Uma verificação independente da OMS sobre a qualidade e a fabricação, incluindo inspeçõ…
- `stageInfo[3].who (pt)`: Equipa de pré-qualificação da OMS → Equipe de pré-qualificação da OMS
- `stageInfo[3].stall (pt)`: Aguarda convites para a ronda de visitas, e depois as inspecções. → Aguardando convites para a rodada de visitas, e depois as inspeções.
- `stageInfo[4].what (pt)`: Cada organismo regulador nacional licencia o medicamento antes de este poder ser vendid… → Cada órgão regulador nacional licencia o medicamento antes que ele possa ser vendido ou…
- `stageInfo[4].who (pt)`: reguladores nacionais do medicamento → reguladores nacionais de medicamentos
- `stageInfo[4].stall (pt)`: Indo país a país, cada um com a sua fila. → Indo país por país, cada um com sua própria fila.
- `stageInfo[4].source (pt)`: Registos nacionais de medicamentos → Registros nacionais de medicamentos
- `stageInfo[5].what (pt)`: Os Ministérios da Saúde incluem o medicamento nas orientações nacionais de tratamento. … → Os Ministérios da Saúde incluem o medicamento nas diretrizes nacionais de tratamento. S…
- `stageInfo[5].stall (pt)`: Os comités nacionais de orientações reúnem-se raramente e seguem os seus próprios calen… → Os comitês nacionais de diretrizes se reúnem raramente e seguem seus próprios cronogramas.
- `stageInfo[5].source (pt)`: Orientações nacionais de tratamento → Diretrizes nacionais de tratamento
- `stageInfo[6].what (pt)`: Os financiadores públicos, como o Fundo Global, outros doadores e governos nacionais, r… → Financiadores públicos, como o Fundo Global, outros doadores e governos nacionais, real…
- `stageInfo[6].who (pt)`: O Fundo Global, outros doadores, a UNICEF e os governos nacionais. → O Fundo Global, outros doadores, o UNICEF e os governos nacionais.
- `stageInfo[6].stall (pt)`: Ciclos de financiamento. As subvenções do Fundo Global, por exemplo, têm a duração de t… → Ciclos de financiamento. As subvenções do Fundo Global, por exemplo, têm duração de trê…
- `stageInfo[7].what (pt)`: Abastecimento do porto até à unidade de saúde, formação dos profissionais de saúde e fa… → Abastecimento do porto até a unidade de saúde, treinamento de profissionais de saúde e …
- `stageInfo[7].stall (pt)`: Preparação da cadeia de abastecimento e formação de profissionais de saúde. → Preparação da cadeia de suprimentos e treinamento de profissionais de saúde.
- `glossary.ACT (pt)`: Terapia combinada à base de artemisinina — a classe padrão de tratamentos para a malári… → Terapia combinada à base de artemisinina — a classe padrão de tratamentos para malária …
- `glossary.SRA (pt)`: Autoridade Reguladora Rigorosa — o termo antigo da OMS para um organismo regulador avan… → Autoridade Regulatória Rigorosa — o termo antigo da OMS para um órgão regulador avançad…
- `glossary.WLA (pt)`: Autoridade listada pela OMS — entidade reguladora avaliada pela OMS como operando a um … → Autoridade listada pela OMS — órgão regulador avaliado pela OMS como operando em um nív…
- `glossary.EU-M4all (pt)`: Medicamentos da UE para todos, anteriormente o procedimento do artigo 58.º — Parecer ci… → Medicamentos da UE para todos, anteriormente o procedimento do Artigo 58 — Parecer cien…
- `glossary.GDG (pt)`: Grupo de Desenvolvimento de Guidelines — o grupo de peritos da OMS que analisa a evidên… → Grupo de Desenvolvimento de Diretrizes — o grupo de especialistas da OMS que analisa as…
- `glossary.PQ (pt)`: Pré-qualificação da OMS — a avaliação da qualidade, segurança e eficácia cujo resultado… → Pré-qualificação da OMS — a avaliação de qualidade, segurança e eficácia cujo resultado…
- `glossary.MFT (pt)`: Terapias múltiplas de primeira linha — a utilização deliberada e gerida de duas ou mais… → Terapias múltiplas de primeira linha — o uso deliberado e gerenciado de duas ou mais AC…
- `glossary.EOI (pt)`: Manifestação de Interesse — a lista de convites para pré-qualificação da OMS; um produt… → Manifestação de Interesse — a lista de convites para pré-qualificação da OMS; um produt…
- `glossary.AMA (pt)`: A Agência Africana do Medicamento — a agência continental do medicamento da União Afric… → A Agência Africana de Medicamentos — a agência continental de medicamentos da União Afr…
- … and 200 more

## 2026-10-28T14-57-39Z

No change for RBM's readers (published by @codebyjackson: One file per language for the React version (dashboard.en/fr/pt.json)): the data is identical to what is published.

First publish of one file per language: `v1/dashboard.en.json`, `v1/dashboard.fr.json`, `v1/dashboard.pt.json`, with their contract `v1/schema.lang.json`.

## 2026-10-27T08-38-13Z

1 change for RBM's readers (published by @codebyjackson: Spanish removed: RBM's platform does not support it):

- language removed: `es`

## 2026-10-20T09-43-27Z

1 change for RBM's readers (published by @codebyjackson: Acknowledgement card translated (fr/pt/es)):

- `products[ganlum].acknowledgement`: Developed by Novartis with the scientific and financial support of MMV, and within the … → Developed by Novartis with the scientific and financial support of MMV, and within the …

## 2026-10-20T09-34-25Z

409 changes for RBM's readers (published by @codebyjackson: Google translation restored: fr/pt/es 100%):

- `stages[0] (fr)`: R&D and Clinical → Recherche et développement et clinique
- `stages[0] (pt)`: R&D and Clinical → I&D e Clínica
- `stages[0] (es)`: R&D and Clinical → Investigación y desarrollo y clínica
- `stages[1] (fr)`: Stringent Regulatory Approval (SRA) → Approbation réglementaire rigoureuse (SRA)
- `stages[1] (pt)`: Stringent Regulatory Approval (SRA) → Aprovação regulamentar rigorosa (SRA)
- `stages[1] (es)`: Stringent Regulatory Approval (SRA) → Aprobación regulatoria rigurosa (SRA)
- `stageInfo[0].who (fr)`: The manufacturer, often with a product development partnership such as MMV → Le fabricant, souvent dans le cadre d'un partenariat de développement de produits tel q…
- `stageInfo[0].who (pt)`: The manufacturer, often with a product development partnership such as MMV → O fabricante, geralmente em parceria para o desenvolvimento de produtos, como o MMV
- `stageInfo[0].who (es)`: The manufacturer, often with a product development partnership such as MMV → El fabricante, a menudo con una asociación de desarrollo de productos como MMV
- `stageInfo[1].what (fr)`: A stringent regulator reviews the full evidence on quality, safety and effectiveness. F… → Un organisme de réglementation rigoureux examine l'ensemble des données probantes relat…
- `stageInfo[1].what (pt)`: A stringent regulator reviews the full evidence on quality, safety and effectiveness. F… → Uma entidade reguladora rigorosa analisa todas as evidências sobre a qualidade, seguran…
- `stageInfo[1].what (es)`: A stringent regulator reviews the full evidence on quality, safety and effectiveness. F… → Un organismo regulador riguroso revisa exhaustivamente la evidencia sobre calidad, segu…
- `stageInfo[1].who (fr)`: EMA, or another stringent regulator such as the US FDA → L'EMA, ou un autre organisme de réglementation rigoureux comme la FDA américaine,
- `stageInfo[1].who (pt)`: EMA, or another stringent regulator such as the US FDA → EMA, ou outro organismo regulador rigoroso como a FDA dos EUA.
- `stageInfo[1].who (es)`: EMA, or another stringent regulator such as the US FDA → La EMA u otro organismo regulador estricto como la FDA de EE. UU.
- `stageInfo[2].what (fr)`: A WHO expert group weighs clinical evidence and decides whether the medicine is include… → Un groupe d'experts de l'OMS évalue les données cliniques et décide si le médicament do…
- `stageInfo[2].what (pt)`: A WHO expert group weighs clinical evidence and decides whether the medicine is include… → Um grupo de peritos da OMS avalia as provas clínicas e decide se o medicamento será inc…
- `stageInfo[2].what (es)`: A WHO expert group weighs clinical evidence and decides whether the medicine is include… → Un grupo de expertos de la OMS evalúa la evidencia clínica y decide si el medicamento s…
- `stageInfo[2].who (fr)`: WHO Department of Malaria and Neglected Tropical Diseases (MNT) and its Guidelines Deve… → Département du paludisme et des maladies tropicales négligées (MNT) de l'OMS et son Gro…
- `stageInfo[2].who (pt)`: WHO Department of Malaria and Neglected Tropical Diseases (MNT) and its Guidelines Deve… → Departamento de Malária e Doenças Tropicais Negligenciadas (MNT) da OMS e o seu Grupo d…
- `stageInfo[2].who (es)`: WHO Department of Malaria and Neglected Tropical Diseases (MNT) and its Guidelines Deve… → Departamento de Malaria y Enfermedades Tropicales Desatendidas (MNT) de la OMS y su Gru…
- `stageInfo[3].what (fr)`: A separate WHO check of quality and manufacturing, including factory inspections. Prequ… → Un contrôle distinct de la qualité et de la fabrication, mené par l'OMS et comprenant d…
- `stageInfo[3].what (pt)`: A separate WHO check of quality and manufacturing, including factory inspections. Prequ… → Uma verificação independente da OMS sobre a qualidade e o fabrico, incluindo inspeções …
- `stageInfo[3].what (es)`: A separate WHO check of quality and manufacturing, including factory inspections. Prequ… → La OMS realiza una verificación independiente de calidad y fabricación, que incluye ins…
- `stageInfo[3].who (fr)`: WHO Prequalification Team → Équipe de préqualification de l'OMS
- `stageInfo[3].who (pt)`: WHO Prequalification Team → Equipa de pré-qualificação da OMS
- `stageInfo[3].who (es)`: WHO Prequalification Team → Equipo de precalificación de la OMS
- `stageInfo[4].what (fr)`: Each country's own regulator licenses the medicine before it can be sold or used there,… → Chaque organisme de réglementation national délivre une autorisation de mise sur le mar…
- `stageInfo[4].what (pt)`: Each country's own regulator licenses the medicine before it can be sold or used there,… → Cada organismo regulador nacional licencia o medicamento antes de este poder ser vendid…
- `stageInfo[4].what (es)`: Each country's own regulator licenses the medicine before it can be sold or used there,… → El organismo regulador de cada país autoriza el medicamento antes de que pueda venderse…
- `stageInfo[4].who (fr)`: National medicines regulators → organismes nationaux de réglementation des médicaments
- `stageInfo[4].who (pt)`: National medicines regulators → reguladores nacionais do medicamento
- `stageInfo[4].who (es)`: National medicines regulators → organismos reguladores nacionales de medicamentos
- `stageInfo[5].what (fr)`: Ministries of Health include the medicine in national treatment guidelines. These decid… → Les ministères de la Santé intègrent ces médicaments dans les recommandations nationale…
- `stageInfo[5].what (pt)`: Ministries of Health include the medicine in national treatment guidelines. These decid… → Os Ministérios da Saúde incluem o medicamento nas orientações nacionais de tratamento. …
- `stageInfo[5].what (es)`: Ministries of Health include the medicine in national treatment guidelines. These decid… → Los Ministerios de Salud incluyen el medicamento en las guías nacionales de tratamiento…
- `stageInfo[5].who (fr)`: Ministries of Health and national malaria programmes → Ministères de la Santé et programmes nationaux de lutte contre le paludisme
- `stageInfo[5].who (pt)`: Ministries of Health and national malaria programmes → Ministérios da Saúde e programas nacionais de combate à malária
- `stageInfo[5].who (es)`: Ministries of Health and national malaria programmes → Ministerios de Salud y programas nacionales contra la malaria
- `stageInfo[6].what (fr)`: Public funders, such as the Global Fund, other donors and national governments, run ten… → Les organismes publics de financement, tels que le Fonds mondial, d'autres donateurs et…
- … and 369 more

## 2026-10-19T07-39-24Z

56 changes for RBM's readers (published by @KylerXiv: Feedback of 15 Oct (#111, #120): GanLum's status, claims checked against sources, glossary, procurement as transactions, access milestones. French, Portuguese and Spanish text follows once translation runs.):

- `stageInfo[1].what`: A stringent regulator reviews the full evidence on quality, safety and effectiveness. F… → A stringent regulator reviews the full evidence on quality, safety and effectiveness. F…
- `stageInfo[3].what`: A separate WHO check of quality and manufacturing, including factory inspections. Prequ… → A separate WHO check of quality and manufacturing, including factory inspections. Prequ…
- `glossary.SRA`: Stringent Regulatory Authority — an advanced regulator (e.g. EMA, US FDA) whose review … → Stringent Regulatory Authority — the older WHO term for an advanced regulator such as E…
- `glossary.Article 58`: EMA procedure giving a scientific opinion on high-priority medicines intended for marke… → —
- `glossary.PQ`: WHO prequalification — the quality, safety and efficacy assessment whose outcome, a lis… → WHO prequalification — the quality, safety and efficacy assessment whose outcome, a lis…
- `glossary.MFT`: Multiple first-line therapies — deploying several first-line treatments in parallel to … → Multiple first-line therapies — the deliberate, managed use of two or more effective AC…
- `glossary.AMA`: African Medicines Agency — continental body coordinating regulatory review across Afric… → African Medicines Agency — the African Union's continental medicines agency, based in K…
- `glossary.EU-M4all`: — → EU-Medicines for all, formerly the Article 58 procedure — EMA's scientific opinion on h…
- added `changelog`: 2026-10-19 · We checked every claim on the medicine pages against its source. Claims that no published result supports were removed or reworded, and some statements were corrected: most DHA–PPQ presentations rely on a single supplier of the main ingredient, ASPY's 2025 pregnancy label covers the second and third trimesters, and the ALAQ development partnership is now named correctly.
- added `changelog`: 2026-10-19 · The regulatory approval step now reads "Not started": a submission is being prepared, but none has been announced. We also removed some claims that were not attributed to a source.
- added `changelog`: 2026-10-19 · We updated several definitions in the glossary, including multiple first-line therapies (MFT) and WHO prequalification, to match current WHO and EMA terminology. Procurement is now shown as transactions and value, with packs listed by presentation and treatment courses only where they can be counted; the figures cover Global Fund-recorded purchases only.
- added `changelog`: 2026-10-19 · The medicines table now shows two milestones instead of one open-ended count: the year a medicine reached market access (recommended and prequalified by WHO), and how long it has been moving towards access in countries since then. We also explain what "Delayed" means, and a new About LAUNCH section explains why the dashboard follows these four medicines.
- `products[ganlum].stages[0].note`: Phase III (KALUMA, NCT05842954) met primary endpoint: 97.4% PCR-corrected cure rate; re… → Met its Phase III primary endpoint in KALUMA (NCT05842954): 97.4% PCR-corrected cure at…
- `products[ganlum].stages[1].status`: prog → idle
- `products[ganlum].stages[1].note`: Regulatory submissions in preparation following Phase III success → Regulatory submission in preparation following Phase III success; no filing announced a…
- `products[ganlum].stages[1].date`: — → Regulatory submission in preparation
- `products[ganlum].stages[1].asOf`: 2026-08-14 → 2026-10-15
- `products[ganlum].detail.useCase`: Non-artemisinin combination — the first major innovation in malaria treatment since ACT… → Non-artemisinin combination in late-stage development. Novartis presents it as having t…
- `products[ganlum].detail.access[0]`: Access and affordability provisions under discussion → Price not public. MMV has said it will be supplied on a "largely not-for-profit" basis …
- `products[ganlum].detail.access[1]`: Once-daily, 3-day granule sachet — no separate paediatric development needed → In Phase III: granules in a sachet, once daily for 3 days with a light meal, for adults…
- `products[ganlum].detail.adoption[0]`: New chemical class — pharmacovigilance planning required → New chemical class (imidazolopiperazine). Safety monitoring after approval will need pl…
- `products[ganlum].detail.research.question`: Efficacy against resistant parasites and transmission blocking → Does it cure infections carrying artemisinin partial-resistance (kelch13) mutations as …
- `products[alaq].manufacturer`: Fosun Pharma · MORU / DeTACT partnership → Fosun Pharma · MORU (FD-TACT)
- `products[alaq].stages[0].note`: Co-formulated fixed-dose triple ACT in pivotal Phase III (FD-TACT; first patient Sep 20… → Co-formulated fixed-dose triple ACT in pivotal Phase III (FD-TACT, NCT05951595; started…
- `products[alaq].detail.access[0]`: Developed through MORU-led DeTACT partnership with Fosun Pharma → Fixed-dose combination developed and made by Fosun Pharma. Pivotal trial (FD-TACT) run …
- `products[alaq].detail.access[1]`: Designed for affordability in endemic-country public sectors → Fosun Pharma has committed to make it "accessible and affordable for malaria-endemic co…
- `products[alaq].detail.access[2]`: Child-friendly dispersible formulation → Paediatric dispersible tablet (20/120/40 mg) being tested in FD-TACT.
- `products[alaq].detail.adoption[1]`: Health-worker training (3-drug regimen) → Training on a new co-formulated product (same 6-dose, 3-day schedule as AL).
- `products[alaq].detail.research.lead`: MORU / DeTACT consortium → MORU / University of Oxford (FD-TACT), with Fosun Pharma
- `products[alaq].detail.research.geographies`: Multi-site, Africa and Asia (DeTACT / FD-TACT trials) → Rwanda, Uganda, Angola, Nigeria and Thailand (FD-TACT sites named by the GHIT Fund; the…
- `products[alaq].detail.research.question`: Safety, efficacy and adherence of co-formulated ALAQ at scale → Is fixed-dose ALAQ as effective as AL and ASAQ (28-day cure, FD-TACT), and safe? Adhere…
- `products[pyramax].stages[1].note`: EMA positive scientific opinion (Article 58/EU-M4all, 16 Feb 2012); label updated 2025 … → EMA positive scientific opinion (Article 58/EU-M4all, 16 Feb 2012); 2025 label update: …
- `products[pyramax].stages[1].source`: EMA EU-M4all opinions table; MMV, 20 Aug 2025 → EMA EU-M4all opinions table; EMA product information, 6 Aug 2025; MMV, 20 Aug 2025
- `products[pyramax].stages[6].note`: Global Fund procurement 2018–2025: 940,111 packs / US$14.5m — modest overall, but US$11… → Global Fund procurement 2018–2025: 68 transactions, US$14.5m — modest overall, but US$1…
- `products[pyramax].detail.access[0]`: WHO PQ held for tablets and paediatric granules → On the WHO list of prequalified medicines (tablets and granules), through the EMA EU-M4…
- `products[pyramax].detail.access[2]`: Co-developed with MMV under access-oriented partnership → Co-developed by Shin Poong and MMV.
- `products[pyramax].detail.adoption[1]`: No cold chain or special administration needs → No cold chain (store below 30°C). Once daily for 3 days, with or without food. Not for …
- `products[pyramax].detail.volume.total`: 940,111 packs · US$14.5m (2018–2025) → 68 transactions · US$14.5m (2018–2025)
- `products[pyramax].detail.volume.period`: Global Fund PQR transactions, 2018–2025 (68 orders; US$11.6m in 2025 alone; top buyers … → Global Fund PQR, 2018–2025 · US$11.6m in 2025 · top buyers Uganda, Burkina Faso, Ghana
- `products[pyramax].detail.volume.byPresentation`: — → [{"label":{"en":"60/180 mg tablets · pack of 90","fr":"60/180 mg tablets · pack of 90",…
- … and 16 more

## 2026-10-19T06-05-03Z

76 changes for RBM's readers (published by @codebyjackson: Citations on individual claims and 14 verified references (15 Oct feedback, #117)):

- added `changelog`: 2026-10-19 · Each stage and milestone now links to the public source behind it, and we added 14 references to the Sources list. We removed ALAQ's target dates for approval and WHO prequalification, which no public source confirms, and corrected a few details to match the sources. No statuses changed.
- `products[ganlum].stages[0].note`: Phase III (KALUMA, NCT05842954) met primary endpoint: 97.4% PCR-corrected cure rate; re… → Phase III (KALUMA, NCT05842954) met primary endpoint: 97.4% PCR-corrected cure rate; re…
- `products[ganlum].stages[0].sources`: — → ["novartis-kaluma","mmv-ganlum-phase3","ctgov-kaluma"]
- `products[ganlum].stages[1].sources`: — → ["novartis-kaluma","mmv-ganlum-phase3"]
- `products[ganlum].stages[3].note`: Not on the WHO PQ EOI list yet (24th malaria EOI, 27 Feb 2026, checked) → Not on the WHO PQ EOI list yet (24th malaria EOI, updated 27 Feb 2026, checked)
- `products[ganlum].stages[3].sources`: — → ["who-pq-eoi-malaria-24","who-pq-fpp"]
- `products[ganlum].detail.milestones[0].sources`: — → ["novartis-kaluma","mmv-ganlum-phase3","ctgov-kaluma"]
- `products[ganlum].detail.milestones[1].sources`: — → ["novartis-kaluma","mmv-ganlum-phase3"]
- `products[ganlum].detail.milestones[2].sources`: — → ["who-pado-malaria-2025"]
- `products[ganlum].detail.milestones[3].sources`: — → ["who-pq-eoi-malaria-24"]
- `products[alaq].stages[0].note`: Co-formulated fixed-dose triple ACT in pivotal Phase III (FD-TACT, successor to the DeT… → Co-formulated fixed-dose triple ACT in pivotal Phase III (FD-TACT; first patient Sep 20…
- `products[alaq].stages[0].sources`: — → ["clinicaltrials-fd-tact","cpt-alaq-dose-2025","who-pado-malaria-2025","ghit-alaq-fdc"]
- `products[alaq].stages[1].next`: SRA/WLA submission — partnership targets approval by ~2027 → Regulatory submission after Phase III results
- `products[alaq].stages[1].nextDate`: ~2027 → TBC
- `products[alaq].stages[1].source`: DeTACT partnership statements → ClinicalTrials.gov NCT05951595; GHIT Fund project G2022-205
- `products[alaq].stages[1].sources`: — → ["clinicaltrials-fd-tact","ghit-alaq-fdc"]
- `products[alaq].stages[3].note`: Not yet included in WHO PQ Expression of Interest list (24th malaria EOI, 27 Feb 2026, … → Not yet included in WHO PQ Expression of Interest list (24th malaria EOI, updated 27 Fe…
- `products[alaq].stages[3].next`: PQ targeted by ~2027 per partnership → WHO prequalification planned after Phase III
- `products[alaq].stages[3].nextDate`: ~2027 → TBC
- `products[alaq].stages[3].sources`: — → ["who-pq-eoi-malaria-24","who-pado-malaria-2025","ghit-alaq-fdc"]
- `products[alaq].detail.milestones[0].sources`: — → ["cpt-alaq-dose-2025"]
- `products[alaq].detail.milestones[1].sources`: — → ["clinicaltrials-fd-tact"]
- `products[alaq].detail.milestones[2].anticipated`: ~2027 → TBC
- `products[alaq].detail.milestones[3].anticipated`: ~2027 → TBC
- `products[alaq].detail.milestones[3].sources`: — → ["who-pq-eoi-malaria-24","who-pado-malaria-2025"]
- `products[pyramax].stages[0].sources`: — → ["mmv-pyramax","mmv-pyramax-pregnancy"]
- `products[pyramax].stages[1].note`: EMA positive scientific opinion (Article 58/EU-M4all, 16 Feb 2012); label updated 2025 … → EMA positive scientific opinion (Article 58/EU-M4all, 16 Feb 2012); label updated 2025 …
- `products[pyramax].stages[1].source`: EMA EU-M4all opinions table; MMV, 31 Jul 2025 → EMA EU-M4all opinions table; MMV, 20 Aug 2025
- `products[pyramax].stages[1].sources`: — → ["ema-pyramax","mmv-pyramax-pregnancy"]
- `products[pyramax].stages[2].sources`: — → ["who-guidelines","mmv-pyramax"]
- `products[pyramax].stages[3].sources`: — → ["who-pq-fpp","ema-pyramax"]
- `products[pyramax].stages[4].sources`: — → ["nafdac","tmda","rwanda-fda","zamra","dav"]
- `products[pyramax].stages[5].sources`: — → ["who-wmr-annex-4b","who-mft-guide","frontiers-ghana-tes","bmjgh-rwanda-mft","malariaj-…
- `products[pyramax].stages[6].sources`: — → ["global-fund-pqr"]
- `products[pyramax].detail.volume.sources`: — → ["global-fund-pqr"]
- `products[pyramax].detail.milestones[0].sources`: — → ["ema-pyramax","ema"]
- `products[pyramax].detail.milestones[1].sources`: — → ["who-pq-fpp"]
- `products[pyramax].detail.milestones[2].sources`: — → ["who-guidelines"]
- `products[pyramax].detail.milestones[3].source`: EMA EU-M4all opinions table; MMV, 31 Jul 2025 → EMA EU-M4all opinions table; MMV, 20 Aug 2025
- `products[pyramax].detail.milestones[3].sources`: — → ["ema-pyramax","mmv-pyramax-pregnancy"]
- … and 36 more

## 2026-10-15T15-09-20Z

58 changes for RBM's readers (published by @codebyjackson: Partner feedback 15 Oct (PRs #107-#110, #112); fr/pt/es translations pending the Google key):

- `stages[0]`: R&D & clinical → R&D and Clinical
- `stages[1]`: Regulatory approval (SRA) → Stringent Regulatory Approval (SRA)
- `stageInfo[0].who`: The manufacturer, often with a product development partnership such as MMV. → The manufacturer, often with a product development partnership such as MMV
- `stageInfo[1].what`: A stringent regulator reviews the full evidence on quality, safety and effectiveness. F… → A stringent regulator reviews the full evidence on quality, safety and effectiveness. F…
- `stageInfo[1].who`: EMA, or another stringent regulator such as the US FDA. → EMA, or another stringent regulator such as the US FDA
- `stageInfo[2].what`: A WHO expert group weighs the clinical evidence and decides whether the medicine goes i… → A WHO expert group weighs clinical evidence and decides whether the medicine is include…
- `stageInfo[2].who`: WHO Global Malaria Programme and its Guidelines Development Group. → WHO Department of Malaria and Neglected Tropical Diseases (MNT) and its Guidelines Deve…
- `stageInfo[3].what`: A separate WHO check of quality and manufacturing, including factory inspections. A pla… → A separate WHO check of quality and manufacturing, including factory inspections. Prequ…
- `stageInfo[3].who`: WHO Prequalification Team. → WHO Prequalification Team
- `stageInfo[4].what`: Each country's own regulator licenses the medicine before it can be sold or used there,… → Each country's own regulator licenses the medicine before it can be sold or used there,…
- `stageInfo[4].who`: National medicines regulators. → National medicines regulators
- `stageInfo[5].what`: The health ministry writes the medicine into the national treatment guidelines. These d… → Ministries of Health include the medicine in national treatment guidelines. These decid…
- `stageInfo[5].who`: Ministries of health and national malaria programmes. → Ministries of Health and national malaria programmes
- `stageInfo[6].what`: Someone has to pay. Funders and governments run tenders, agree reference prices and for… → Public funders, such as the Global Fund, other donors and national governments, run ten…
- `stageInfo[6].who`: The Global Fund, the US President's Malaria Initiative, UNICEF and national governments. → The Global Fund, other donors, UNICEF and national governments
- `stageInfo[6].source`: Global Fund price and quality reporting, PMI → Global Fund price and quality reporting
- `stageInfo[7].what`: Getting the medicine from the port to the health facility, training health workers, and… → Supply from port to health facility, health-worker training, and pharmacovigilance once…
- `stageInfo[7].who`: Governments and implementing partners. → Governments and implementing partners
- added `changelog`: 2026-10-15 · We updated the name of WHO's malaria department to the Department of Malaria and Neglected Tropical Diseases (MNT). The country counts for ASPY and DHA–PPQ now match the country access map, and we show how many countries a national medicines register confirms. We removed the years-late figures until the way they are worked out is agreed; the expected time for each stage stays. ALAQ's description now says it is still in clinical development and that its future role depends on trial results, regulators, WHO and countries. ASPY's description now says that registration and adoption vary by country and that LAUNCH is checking them country by country. For DHA–PPQ we explain what the 0.9–4.5% is a share of, describe its uses more carefully, and corrected Nigeria's count of active registrations from 26 to 25. No dates or statuses changed.
- added `changelog`: 2026-10-15 · We reworded the explanations of the steps on the pathway after partner feedback, and renamed the first two steps "R&D and Clinical" and "Stringent Regulatory Approval (SRA)". No dates, statuses or figures changed.
- `products[alaq].detail.useCase`: Triple ACT to protect artemisinin partner drugs — MFT component and first-line option w… → Triple artemisinin-based combination therapy in clinical development. Its potential fut…
- `products[pyramax].inn`: Pyronaridine–artesunate (Pyramax) → Artesunate–pyronaridine (Pyramax)
- `products[pyramax].stages[5].note`: National guideline inclusion lags WHO's 2022 strong recommendation — Ghana introduced a… → In national guidelines in 7 countries on the country access map, and in MFT plans in 4 …
- `products[pyramax].stages[5].date`: Ghana only (2022) → Ghana 2022; WHO policy table 2024
- `products[pyramax].stages[5].source`: Peer-reviewed therapeutic-efficacy study, Ghana 2023 (published 2026); LAUNCH assessmen… → WHO World Malaria Report 2025, Annex 4B (policy as of 2024); WHO MFT implementation gui…
- `products[pyramax].stages[5].asOf`: 2026-09-08 → 2026-10-05
- `products[pyramax].detail.useCase`: First-line diversification / MFT component; paediatric granules available; label includ… → WHO-recommended ACT with verified registration and adoption varying by country. LAUNCH …
- `products[pyramax].detail.research.question`: MFT deployment models with pyronaridine–artesunate → MFT deployment models with artesunate–pyronaridine
- `products[pyramax].detail.country.registered`: 13 → 2
- `products[pyramax].detail.country.inGuidelines`: 11 → 7
- `products[pyramax].detail.countries.list[9].note`: WHO writes "PY"; read as pyronaridine-artesunate → WHO writes "PY"; read as artesunate–pyronaridine
- `products[pyramax].detail.milestones[5].label`: Ghana only — 1 country confirmed → 7 countries, plus 4 with MFT plans
- `products[pyramax].detail.milestones[5].date`: Ghana, 2022 → Ghana 2022; WHO policy table 2024
- `products[pyramax].detail.milestones[5].source`: Peer-reviewed therapeutic-efficacy study, Ghana 2023 (published 2026) → WHO World Malaria Report 2025, Annex 4B (policy as of 2024); WHO MFT implementation gui…
- `products[dhappq].flag`: Procurement is the current access barrier — 0.9–4.5% of Global Fund antimalarial spend … → Procurement is the current access barrier — 0.9–4.5% of the value of all antimalarial m…
- `products[dhappq].barrier`: Only 0.9–4.5% of Global Fund spend, 2022–24 → Only 0.9–4.5% of Global Fund antimalarial orders by value, 2022–24
- `products[dhappq].stages[4].note`: Registered widely; adopted as first-line in several Southeast Asian countries. Register… → Confirmed in six national registers so far: Nigeria, Rwanda, Tanzania, Viet Nam, Zambia…
- `products[dhappq].stages[4].source`: MMV / WHO; NAFDAC Greenbook + TMDA IMIS2 registers (extracts 23 Aug 2026) → NAFDAC, Rwanda FDA, TMDA, DAV, ZAMRA and MCAZ registers (see the country access map); N…
- `products[dhappq].stages[4].asOf`: 2026-08-23 → 2026-10-05
- `products[dhappq].stages[5].note`: First-line in several SE Asian countries; consideration in African MFT strategies growi… → In national guidelines in 9 countries on the country access map, and in MFT plans in 4 …
- … and 18 more

## 2026-10-13T08-50-14Z

6 changes for RBM's readers (published by @codebyjackson: Revert test proposal #99 (end-to-end test, 13 Oct)):

- removed `changelog`: 2026-10-13 · GanLum — WHO PQ listing updated (source: WHO prequalification list).
- `products[ganlum].stages[3].status`: done → idle
- `products[ganlum].stages[3].note`: Prequalified by WHO on 15 Sep 2026 (WHO ref TEST-0001, Novartis Pharma AG). → Not on the WHO PQ EOI list yet (24th malaria EOI, 27 Feb 2026, checked)
- `products[ganlum].stages[3].date`: 15 Sep 2026 → —
- `products[ganlum].stages[3].source`: WHO prequalification list (TEST-0001 — https://extranet.who.int/prequal/medicines/prequ… → WHO PQ EOI list (24th edition)
- `products[ganlum].stages[3].asOf`: 2026-09-21 → 2026-08-22

## 2026-10-13T08-38-11Z

6 changes for RBM's readers (approval of proposal #99 by @codebyjackson):

- added `changelog`: 2026-10-13 · GanLum — WHO PQ listing updated (source: WHO prequalification list).
- `products[ganlum].stages[3].status`: idle → done
- `products[ganlum].stages[3].note`: Not on the WHO PQ EOI list yet (24th malaria EOI, 27 Feb 2026, checked) → Prequalified by WHO on 15 Sep 2026 (WHO ref TEST-0001, Novartis Pharma AG).
- `products[ganlum].stages[3].date`: — → 15 Sep 2026
- `products[ganlum].stages[3].source`: WHO PQ EOI list (24th edition) → WHO prequalification list (TEST-0001 — https://extranet.who.int/prequal/medicines/prequ…
- `products[ganlum].stages[3].asOf`: 2026-08-22 → 2026-09-21

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
