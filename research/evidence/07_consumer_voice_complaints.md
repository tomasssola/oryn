# 07 — Consumer Voice: Complaints, Reviews and Unmet Needs on the Costa del Sol (Málaga province)

Research date: 18 September 2026.

## Method and evidence-strength caveats (read first)

- Tooling: this session's WebSearch budget was already exhausted when the task began, and direct fetching (curl/WebFetch) of reddit.com, ine.es and most other domains is blocked by the proxy. All evidence therefore comes from 53 distinct Firecrawl web searches (limit 20, `tbs: qdr:y` for the last 12 months), run one at a time because the Firecrawl endpoint is shared with six other agents and returned HTTP 429 on every parallel attempt (four separate back-off periods were needed). The requested 60+ searches were not reached; 53 were completed.
- Quotes are taken verbatim from the search index descriptions/highlights of the pages (the pages themselves were not opened). They are accurate to what the index returned but may be truncated mid-sentence; truncation is shown with "..." and never filled in.
- "Frequency" in Section 1 is the number of distinct threads, posts, reviews pages or articles I actually saw for that topic across the 53 searches. It is a relative signal of prominence in search-visible consumer voice, not a population estimate. Intensity (1-5) reflects the emotional/financial severity expressed in the sources.
- Dates are given when the index showed them. Items marked [unverified] come from aggregator or marketing sites whose numbers I could not check. Real-estate and legal-marketing content (especially on squatting and property fraud) is flagged as biased.
- Raw search log with all snippets: `/tmp/claude-0/-home-user-oryn/6a9ee237-3837-592a-8c05-9d3326c608a9/scratchpad/research/_notes_07.md`.

---

## 1. COMPLAINT FREQUENCY TABLE (ranked)

| # | Topic | Freq (distinct items seen) | Intensity (1-5) | Who complains | Example sources |
|---|---|---|---|---|---|
| 1 | Long-term rental: unaffordable, unavailable, landlord "won't choose you", agency fees, no pets | ~24 | 5 | Locals (esp. young), newcomers, remote workers | reddit.com/r/GoingToSpain/comments/1t3d51r ; reddit.com/r/GoingToSpain/comments/1uvvrff ; facebook.com/esdecirdiario (Málaga demo) ; laopiniondemalaga.es FB post "tercera provincia que más esfuerzo de renta" |
| 2 | Rental scams (fake Idealista listings, fake landlords, deposits taken) and deposit non-return | ~14 | 5 | Newcomers, students, tourists renting | facebook.com/groups/507811220036834/posts/2153381558813117 ; surinenglish.com/.../three-years-prison-20260727143310-nt.html ; idealista.com/en/news/.../2026/03/03/886915 |
| 3 | Public healthcare: cannot get GP appointment, waiting lists, strikes, unfinished hospitals | ~12 | 5 | Everyone; acute for elderly and non-Spanish speakers | laopiniondemalaga.es/malaga/2026/02/16/pacientes-afectados... ; malagahoy.es/.../cita-medico-cabecera-malaga-mision-agotadora... ; diariosur.es/.../balance-primer-dia-huelga-malaga-20260216140632-nt.html |
| 4 | Tourist flats (VUT) and mass tourism pushing residents out; neighbour associations suing the city | ~12 | 5 | Málaga centre residents, Marbella/Estepona residents | centroantiguomalaga.com/actualidad/ ; facebook.com/PTVMalaga (vecinos llevarán al Ayuntamiento a los tribunales) ; facebook.com/OlivePressNewspaper (hundreds face eviction) |
| 5 | Bureaucracy: cita previa / TIE / NIE / extranjería collapse; appointment bots | ~12 | 5 | Non-EU residents (Brits, Americans, Latin Americans), DNV holders | theolivepress.es/spain-news/2026/05/21/brit-expats-in-spain-face-14-week-wait-for-tie-residency-cards/ ; facebook.com/CSIFNacional (1.2M solicitudes) ; easytospain.com/blogs/cita-previa-spain-2026 |
| 6 | Airport car hire: deposits withheld, pre-existing damage disputes, upfront "SCAM" charges, queues | ~12 (Trustpilot company pages) | 4 | Tourists and second-home owners | trustpilot.com/review/www.recordrentacar.com ; trustpilot.com/review/thrifty.es ; trustpilot.com/review/www.delpasocarhire.com |
| 7 | Hospitality/small business: cannot hire staff (7,000 short) vs low wages, bars closing days | ~12 | 4 | Bar/restaurant/chiringuito owners; hospitality workers | lasexta.com/.../hosteleria-malaga-limite...202607036a47f943dcb2092ca8c4b028.html ; malagahoy.es/malaga/verano-sin-mano-obra-hosteleria-malaga_0_2006827184.html |
| 8 | Traffic on A-7 and AP-7 summer toll hikes (+68%) | ~12 | 4 | Commuters, western Costa residents, Campo de Gibraltar | theolivepress.es/spain-news/2026/06/01/ap7-toll-road-summer-rates-costa-del-sol/ ; euroweeklynews.com/2026/05/31/toll-prices-rise... ; malagahoy.es/tag/carreteras-malaga/ |
| 9 | Public transport: Cercanías chaos, planned 6-month C1 closure, Marbella/Estepona with no train | ~10 | 4 | Commuters, workers without cars | facebook.com/queestapasandoQEP (CAOS EN EL CERCANÍAS, 10 Feb 2026) ; facebook.com/101tvmalaga (MEDIO AÑO SIN TREN) |
| 10 | Noise: terraces, hotels, neighbours, botellón | ~10 | 4 | Málaga centre, Torremolinos, urbanisations | facebook.com/AyuntamientodeMalaga (weekly 39-87 denuncias) ; euroweeklynews.com/2026/08/11/fed-up-and-angry-torremolinos-residents... ; diariosur.es/.../conflicto-ruidos-acaba-punetazos... |
| 11 | Finding trusted English-speaking tradespeople (plumber, electrician, builder) and gestor | ~18 FB threads | 3 | Foreign homeowners across the coast | facebook.com/groups/580086446811884/posts/1523766075777245 ; facebook.com/groups/ExpatsInMalaga/posts/27444353201890860 ; facebook.com/groups/346826998670639/posts/28969815699278387 |
| 12 | Nanny / housekeeper / dog-sitter / pet-sitter sourcing | ~15 FB threads | 2 | Families (Marbella, Sotogrande, Fuengirola), pet owners | facebook.com/groups/217378758273941 ; facebook.com/groups/346826998670639/posts/28251689157757715 |
| 13 | Property purchase fraud: fake lawyers, email hijack of conveyancing, notary/POA fraud | ~8 | 5 | Foreign buyers (high-value) | theolivepress.es/spain-news/2026/08/25/fake-lawyer-marbella-property-scam/ ; surinenglish.com/.../fake-solicitor-been-20260826105911-nt.html ; surinenglish.com/.../the-complex-computer-fraud-that-swindled-two-20260312111923-nt.html |
| 14 | Málaga airport: passport-control queues (EES), delays (63% punctuality), disorganisation | ~8 | 4 | UK/non-EU travellers, residents flying home | trustpilot.com/review/www.airport-malaga.com (1.5/5) ; thespanisheye.com/2025/11/14/its-a-nightmare... ; surinenglish.com/.../million-passengers-face-20260730101157-nt.html |
| 15 | Water: summer network at its limit, cuts/low pressure in Mijas/Benalmádena urbanisations; flooding | ~9 | 3 | Urbanisation residents (Mijas, Benalmádena, Alhaurín), Casares | facebook.com/diariosur (demanda de agua pone al límite la red) ; facebook.com/AndaluciaDirecto (Collejares sin agua potable) |
| 16 | Squatting (okupas) fear; 2,800 active files in Andalucía | ~8 (mostly marketing/legal content, biased) | 3 | Second-home owners | healthplanspain.com/blog/spain-news/2257-... ; theolivepress.es/spain-news/2025/12/12/marbella-police-what-to-do-squatters/ |
| 17 | International schools: waiting lists, non-refundable waiting-list fee (€2k) + deposit (€3k), fees €7-18k | ~8 | 3 | Relocating families | abarzo.com/journal/.../international-schools-in-marbella-2026... ; facebook.com/groups/294388724750178/posts/2293129334876097 |
| 18 | Anti-expat/anti-tourist resentment; language barrier; "expats leaving" | ~10 | 3 | Both locals and foreigners | theolivepress.es/spain-news/2026/04/24/marbellasequeja-expats-dont-speak-spanish/ ; facebook.com/groups/lacalahangout/posts/2745157009185171 ; reddit.com/r/GoingToSpain/comments/1utkcfc |
| 19 | Elderly foreigners: isolation, dementia care, English-speaking care homes, post-Brexit relatives | ~7 | 4 | Over-75s and their families | facebook.com/groups/brexpatsinspain/posts/3144770035683984 ; euroweeklynews.com/2026/09/11/marbella-volunteers-are-checking-on-240-older-people-who-live-alone/ ; carehomesspain.com |
| 20 | Beach-bar/tourist rip-offs, beach fines, chiringuito inspections | ~7 | 3 | Tourists, residents | facebook.com/OlivePressNewspaper (Marbella police crackdown on beach bars) ; euroweeklynews.com/2026/08/28/tourists-horrified-by-spain-paella-bill... |
| 21 | Banking: non-resident fees (€10-15/mo), branch staff without English, FATCA for Americans | ~7 | 2 | Newcomers, non-residents, Americans | facebook.com/groups/1556813121287509/posts/4009153182720145 ; spainexpat.com/information/banking_options_for_expats_in_spain |
| 22 | Cleanliness, homelessness, incivility, safety (hyper-local "se queja" pages) | ~7 | 3 | Residents of Marbella, Fuengirola, Torremolinos, Benalmádena | facebook.com/Marbellasequeja (193k likes) ; instagram.com/fuengirolasequeja ; laopiniondemalaga.es/.../2026/08/20/polemica-fuengirola-persona-hogar-desnudo... |
| 23 | Internet/mobile: 47,000 homes without adequate broadband; outages | ~6 | 3 | Inland/urbanisation residents (Mijas, Coín, Alhaurín, Casares) | malagahoy.es/provincia/hogares-malaga-acceso-internet_0_2005113540.html ; facebook.com/groups/lacalahangout/posts/2931038707263666 |
| 24 | Crime perception: robberies, pickpockets at airport train station, cyber-scams +11% | ~6 | 3 | Residents, tourists | facebook.com/surenglish (Torremolinos taser robberies, "fed up with the ever-increasing crime rate") ; malaga.is/p/topic-malaga-crime-rates-q1-2026-en |
| 25 | Cyber/phone scams targeting expats (Hacienda texts, booking WhatsApp, tech support) | ~6 | 3 | Pensioners, all expats | theolivepress.es/spain-news/2026/03/25/hacienda-scam-alert... ; theolivepress.es/spain-news/2026/04/01/the-new-way-fraudsters-are-targeting-expats-in-spain-in-2026/ |
| 26 | Private health insurance: pre-existing/pregnancy exclusions, rising premiums, visa compliance | ~6 | 3 | Visa applicants, families | facebook.com/groups/957315298668782/posts/1627132751687030 ; facebook.com/yana.sokosyuk (pregnancy not covered) |
| 27 | Jobs: few, low-paid; hard for foreigners; salaries vs rents | ~6 | 3 | Working-age migrants, locals | reddit.com/r/expat/comments/1utxpe3 ; reddit.com/r/Malaga/comments/1p3nnts |
| 28 | Parking scarcity/prices, gorrillas | ~6 | 3 | Drivers in Marbella, Málaga hospital users | euroweeklynews.com/2026/08/29/enjoy-marbella-for-cheaper-this-september... ; facebook.com/VivaMalagaPeriodico (Hospital Civil parking protest) |
| 29 | Digital nomads: "overrated, expensive", DNV bureaucracy, need local help for leases/banks | ~6 | 2 | Remote workers | reddit.com/r/digitalnomad/comments/1pv5gjr ; reddit.com/r/digitalnomad/comments/1v3ot8x |
| 30 | Accessibility: beach access distances, lack of adapted spaces | ~5 | 3 | People with reduced mobility | facebook.com/ayto.torremolinos (denuncia playas Las Palmas) ; surinenglish.com/.../fuengirola-accessible-beaches-welcome-almost-8000-users-20260825101242-nt.html |
| 31 | Builder/renovation fraud, disappearing contractors | ~5 | 4 | Foreign homeowners | facebook.com/groups/210098326366137/posts/1924306448278641 (home improvement fraud Estepona/Marbella) ; facebook.com/groups/931380393706802/posts/3534249200086562 |
| 32 | Non-resident tax (Modelo 210/720) surprises and fines | ~5 | 2 | Non-resident owners | facebook.com/groups/133217347273496/posts/2089717574956787 ; facebook.com/everythingisboffo |
| 33 | English-speaking doctors/dentists: bad experiences, overcharging fear | ~5 | 2 | Foreign residents | facebook.com/groups/ExpatsInMalaga/posts/24738112789181595 ; facebook.com/groups/7099977763373411/posts/26340772265534006 |
| 34 | Community of owners: fees, penalties, administrators; property-management fee opacity | ~5 | 2 | Owners in urbanisations | facebook.com/groups/507811220036834/posts/2104171257067481 ; holidaysmalaga.com/blog/holiday-rental-management-fees-malaga |
| 35 | Electricity: bills +15%, multi-day cuts (Palma-Palmilla), 2025 blackout compensation | ~4 | 3 | Households | facebook.com/groups/793354344359351/posts/2938364483191649 ; facebook.com/AndaluciaDirecto (Palma-Palmilla cuatro días sin luz) |
| 36 | Expat mental health, loneliness, "should I go home" | ~5 | 3 | Single expats, retirees | reddit.com/r/expats/comments/1qwmp8r ; reddit.com/r/expats/comments/1qsesw8 |
| 37 | Beach closures from sewage/bacteria in peak season | ~3 | 3 | Hoteliers, bathers | theolivepress.es/spain-news/2026/08/21/malaga-hotels-complain-beach-closures... ; theolivepress.es/spain-news/2026/07/24/costa-del-sol-beach-scare... |
| 38 | 24-hour English-speaking emergency vet; registering pets | ~4 | 2 | Pet owners (Estepona esp.) | facebook.com/groups/507811220036834/posts/2161857631298843 |

---

## 2. VERBATIM SNIPPETS (top 20 topics)

All quotes are exactly as returned by the search index; truncations kept as "...".

### 2.1 Long-term rental unaffordable / unavailable
- "Yes it is this bad. 1000€ is impossible in Málaga for a 2 persons apartment which is not a studio and not a room only." — r/GoingToSpain, "How the hell do people actually find an apartment in Málaga?" https://www.reddit.com/r/GoingToSpain/comments/1t3d51r/ (2025-26)
- "In Málaga, the biggest challenge isn't always being able to afford the rent. It's getting the landlord to choose you. With around €3,650 net a month..." — r/GoingToSpain "2026 cost of living" https://www.reddit.com/r/GoingToSpain/comments/1uvvrff/ (2026)
- "Finding an apartment to rent is very hard, prices are huge right now. Renting a flat with a dog will be nearly impossible." — r/GoingToSpain https://www.reddit.com/r/GoingToSpain/comments/1s9brqd/
- "many agencies are asking tenants to pay the equivalent of one month's rent as an [agency fee]" — r/GoingToSpain https://www.reddit.com/r/GoingToSpain/comments/1np7222/
- "si no puedo pagar un alquiler qué hacemos los malagueños nos quedamos en la calle ... sube todo y nuestros sueldos..." — commenter under Es Decir Diario post on Málaga housing demonstration https://www.facebook.com/esdecirdiario/posts/1838024344278646/ (2026)
- "Rental prices on the Costa del Sol have risen 34% since 2020. A 2-bedroom apartment in Marbella now costs €1,500–€2,500/month; in Estepona, €1,200–€1,900." — waypointsur guide (2026) [unverified secondary]
- "Málaga destaca claramente por la vivienda como principal problema provincial. Un 64% de los encuestados la señala" — RTV Alhaurín news bulletin, 8 Jun 2026 https://www.facebook.com/Rtvalhaurin/posts/1575749337893465/ [survey source not identified]

### 2.2 Rental scams and deposit non-return
- "Many times apartment listings are fake or it is a squatter pretending to be the property owner." — r/SpainAuxiliares https://www.reddit.com/r/SpainAuxiliares/comments/1o56ajy/
- "Rental scam in Estepona through Idealista" / "Rental Scam Warning in Spain: An American family preparing to move..." — FB group 507811220036834 https://www.facebook.com/groups/507811220036834/posts/2153381558813117/
- "Beware of apartment rental scam in Nerja, Spain... WARNING!!!!! We have been completely deceived" — FB group 97904645004 https://www.facebook.com/groups/97904645004/posts/10174420561100005/
- "As an immigrant it's extremely difficult to find a place to live, and because of this scammers..." — r/GoingToSpain "Just got scammed" https://www.reddit.com/r/GoingToSpain/comments/1q8zj09/
- "Marbella fake landlord sentenced to prison... compensation amounts to 6,580 euros, a sum which corresponds exactly to what the victims had paid as a deposit." — Sur in English, 27 Jul 2026 https://www.surinenglish.com/malaga/marbella-san-pedro/three-years-prison-20260727143310-nt.html
- "Landlords will try and keep deposits, my only advice... don't pay rent for the months they have in deposit" — FB group cumbredelsol https://www.facebook.com/groups/cumbredelsol/posts/24942686032020736/ (thread also: "Disputing rental deposit return in Marbella")
- "one of the biggest challenges tenants face in Spain when their tenancy agreement ends is the non-return of their security deposit" — Idealista, 3 Mar 2026 (AVRA deposit scheme abolished Jan 2026) https://www.idealista.com/en/news/property-for-rent-in-spain/2026/03/03/886915-rental-deposit-scheme-abolished-in-andalusia

### 2.3 Public healthcare access
- "Uno de cada cinco pacientes en Málaga se queda sin cita al intentar pedirla en Atención Primaria" — FB group 1037975736236105 https://www.facebook.com/groups/1037975736236105/posts/26697532769853716/
- "En la provincia, la demora para conseguir cita con el médico de cabecera supera los 8 días de media, y hay casos en los que la espera puede llegar hasta los 20" — SUR (Instagram), Feb 2026 https://www.instagram.com/reel/DSDDCW-kxef/
- "Después de un año esperando la cita, he venido hoy y me han dicho que están de huelga" — patient, La Opinión de Málaga, 16 Feb 2026 https://www.laopiniondemalaga.es/malaga/2026/02/16/pacientes-afectados-malaga-huelga-medicos-consultas-canceladas-126905451.html
- "Conseguir cita con el médico de cabecera en Málaga, una misión agotadora" — Málaga Hoy https://www.malagahoy.es/malaga/cita-medico-cabecera-malaga-mision-agotadora-huelga_0_2005440486.html
- "-Hospitales de Ronda y Guadalhorce cerrados. -Hospitales de Estepona y Fuengirola-Mijas sin empezar. -Hospital Costa del Sol sin acabar." — 101TV Málaga https://www.facebook.com/101tvmalaga/posts/1443681147758035/
- "Fui a operarme a las 6 am y a las 10 am recién nos dijeron que había huelga de anestesistas" — commenter, Area Costa del Sol (Hospital Costa del Sol) https://www.facebook.com/areacostadelsol/posts/1604541711676445/
- "Even doctors here don't speak English. A life relying on google translate is so so so tough." — r/GoingToSpain https://www.reddit.com/r/GoingToSpain/comments/1utkcfc/

### 2.4 Tourist flats / mass tourism displacing residents
- "Los vecinos del Centro de Málaga llevarán al Ayuntamiento de Málaga a los tribunales por la proliferación de pisos turísticos" — PTV Málaga https://www.facebook.com/PTVMalaga/posts/1901877807867003/
- "sin que los edificios residenciales sean convertidos en hoteles encubiertos" / "el 92% de las terrazas del centro incumplían la ordenanza" — AAVV Centro Antiguo de Málaga, 21 Jul 2026 https://centroantiguomalaga.com/actualidad/
- "muchas quejas, muchas molestias a los vecinos y posibles inquilinos que no encuentran vivienda para comprar o alquilar" — SER Málaga (Martiricos/Centro) https://www.facebook.com/SERMalaga/posts/1477597884394279/
- "Málaga prohibirá nuevas viviendas turísticas en 43 barrios" — Diario Sur https://www.facebook.com/diariosur/posts/1437321465097474/
- "En 2025, el PP ha autorizado en Málaga proyectos que suman 340 nuevos apartamentos turísticos, el doble que el año..." — Podemos Málaga https://www.facebook.com/podemosmalaga/posts/1342084271060482/
- "Hundreds of Costa del Sol residents, including British expats, are at risk of being forced out of their homes to make way for a mass-tourism development" — Olive Press https://www.facebook.com/OlivePressNewspaper/posts/1358718046270541/
- "Locals are so exhausted with influx of foreigners buying up properties." — r/GoingToSpain https://www.reddit.com/r/GoingToSpain/comments/1u11pgl/

### 2.5 Bureaucracy / cita previa / TIE
- "Colapso en Extranjería: la administración está desbordada, se han recibido más de 1,2 millones de solicitudes. Falta personal" — CSIF; commenter: "Llevamos más de 4 meses intentando conseguir una cita por el canal oficial y NO hay CITAS" https://www.facebook.com/CSIFNacional/posts/1447249340764696/
- "British expats in Spain struggling to renew residency as bots stealing appointments and staff shortages cause 14-week wait for vital TIE cards" — Olive Press, 21 May 2026 https://www.theolivepress.es/spain-news/2026/05/21/brit-expats-in-spain-face-14-week-wait-for-tie-residency-cards/
- "our solicitor has said that we just need to keep trying but I'm starting to..." — Brexpats in Spain FB https://www.facebook.com/groups/brexpatsinspain/posts/3163347133826274/
- "The biggest issue is the simple administrative issues. water bill, can be highly frustrating." — r/GoingToSpain https://www.reddit.com/r/GoingToSpain/comments/1pd1u77/
- "Authorities are highly disfunctional." — r/GoingToSpain https://www.reddit.com/r/GoingToSpain/comments/1ssnrqv/
- "Spanish bureaucracy can be a total nightmare in reality, digital nomad visa." — r/visas https://www.reddit.com/r/visas/comments/1uf4mq4/

### 2.6 Airport car hire
- "the way the company handles deposits and customer communication is the reason I cannot recommend this rental company... The car I was given was significantly damaged across virtually every panel... So they have basically just stolen our deposit and made it impossible to get it back" — Trustpilot, Record Go https://www.trustpilot.com/review/www.recordrentacar.com
- "Had to wait for over 45 minutes at Malaga airport to pick up a car." — Trustpilot, Firefly (1.2/5) https://www.trustpilot.com/review/global.fireflycarrental.com?page=2
- "Delays at airport picking up car Paid extra insurance to cover damage Now..." — Trustpilot, Thrifty.es (1.3/5, 328 reviews) https://www.trustpilot.com/review/thrifty.es
- "SCAM Paid upfront Hire Charge €165.67 7 days for Citroen DS3 selected airport..." — Trustpilot, Delpaso Car Hire (1.9/5, 1,914 reviews) https://www.trustpilot.com/review/www.delpasocarhire.com?page=4
- "Sixt are scammers (along with every other car rental in Europe)." — r/travel https://www.reddit.com/r/travel/comments/1s4c5rf/

### 2.7 Hospitality staffing / small business
- "La hostelería malagueña lanza un SOS este verano: faltan unos 7.000 camareros y profesionales del sector" — Andalucía Directo https://www.facebook.com/AndaluciaDirecto/videos/1012376054756656/
- "Bares y chiringuitos que tienen que cerrar por falta de personal en Málaga capital 1450€ ..." — Andalucía Directo Instagram, 28 May 2026 (832 likes, 173 comments) https://www.instagram.com/reel/DY460h9kVFn/
- "Los hosteleros se quejan de que no encuentran camareros para el verano en Málaga. Sin embargo, allí hay 20.000 personas que demandan empleo en hostelería" — LaSexta, 3 Jul 2026 https://www.lasexta.com/noticias/sociedad/hosteleria-malaga-limite-empresarios-dicen-que-encuentran-trabajadores-camareros-denuncian-malas-condiciones_202607036a47f943dcb2092ca8c4b028.html
- "hay establecimientos que ya no pueden abrir todos los días" — Mahos via Málaga Hoy https://www.malagahoy.es/malaga/verano-sin-mano-obra-hosteleria-malaga_0_2006827184.html
- "Pedro, dueño de 9 chiringuitos en Marbella: 'No hay camareros'... necesita contratar a 300 empleados" — Noticias Trabajo https://www.noticiastrabajo.es/sociedad/pedro-dueno-de-9-chiringuitos-en-marbella...
- "precios altos, personal poco formado y pérdida de identidad" — Hosteleros de Málaga, El Español, 25 Sep 2025 https://www.elespanol.com/malaga/economia/20250925/hosteleria-malaga-alerta-situacion-actual-precios-altos-personal-formado-perdida-identidad/1003743939861_0.html

### 2.8 Traffic and AP-7 tolls
- "Horrific queues on the A7 heading into Fuengirola on the same day as the AP7 toll road hikes its prices to the much-loathed summer rates - a 68% price..." — Olive Press FB https://www.facebook.com/OlivePressNewspaper/posts/1467552305387114/
- "San Pedro barrier will see fees climb from €3.85 to €6.25" — Olive Press, 1 Jun 2026 https://www.theolivepress.es/spain-news/2026/06/01/ap7-toll-road-summer-rates-costa-del-sol/
- "para salir del Campo de Gibraltar hacia Málaga, esté el tramo de carretera más caro de España. 19,55€ los tres peajes" — FB https://www.facebook.com/Turismorunningcomunicacion/posts/1035309882341367/
- "Sin hospital, sin tren, sin agua y sufriendo grandes atascos." — PP Málaga via FB https://www.facebook.com/muyfansdeandalucia/posts/952614511210274/
- "Colapso en la A7 en el Este de Málaga: un accidente provoca ocho kilómetros de atascos" — Málaga Hoy, Sep 2026 https://www.malagahoy.es/tag/carreteras-malaga/

### 2.9 Public transport / Cercanías
- "CAOS EN EL CERCANÍAS: MARTES NEGRO PARA LOS PASAJEROS EN MÁLAGA" — Qué está pasando, 10 Feb 2026 https://www.facebook.com/queestapasandoQEP/posts/1477866077672379/
- "MEDIO AÑO SIN TREN DE CERCANÍAS. CORTE TOTAL DE LA LÍNEA. Está previsto por Adif entre el último trimestre de 2027 y el primero de 2028" — 101TV https://www.facebook.com/101tvmalaga/posts/1550072167118932/
- "Los retrasos y la saturación ponen al Cercanías de Málaga al límite ... sin tren (Marbella, Estepona, Vélez Málaga), la falta de personal en talleres" — Málaga Hoy https://www.facebook.com/PeriodicoMalagaHoy/posts/1721151073353540/
- "Sin tren, el futuro es claro: más embotellamientos, más costos absurdos para la industria, más emisiones, más muertes y un colapso asegurado." — commenter, La Opinión https://www.facebook.com/laopiniondemalaga/posts/1458677002973153/
- "avoid the coastal stopping services as these take for ever" — Tripadvisor Nerja forum (Alsa bus) https://www.tripadvisor.com/ShowTopic-g315917-i5571-k15503633-...

### 2.10 Noise
- "La Policía Local tramita 87 denuncias en materia de control de ruidos y convivencia en la última semana. Se han realizado 260 intervenciones" — Ayuntamiento de Málaga https://www.facebook.com/AyuntamientodeMalaga/posts/1453442116822851/
- "Fed up and angry Torremolinos residents take stand over years of hotel noise pollution" — Euro Weekly News, 11 Aug 2026 https://euroweeklynews.com/2026/08/11/fed-up-and-angry-torremolinos-residents-take-stand-over-years-of-hotel-noise-pollution/
- "23 abril (ayer) empezó ya el exceso de decibelios de Marenostrum..." — Vecinos Fuengirola FB group https://www.facebook.com/groups/779686375409386/posts/28565349843082999/
- "Un conflicto por ruidos acaba a puñetazos entre dos vecinos de Málaga: «Te voy a quemar la casa y buscar la ruina»" — Diario Sur, 7 Jul 2026 https://www.diariosur.es/economia/mibolsillo/conflicto-ruidos-acaba-punetazos-dos-vecinos-malaga-20260707234725-nt.html
- "El pasaje amanece lleno de orina y cristales tras cada verbena" — resident, El Español, 18 Jun 2026 https://www.elespanol.com/malaga/20260618/patrulla-barrio-malaga-frena-botellon-golpe-manguera-no-mea-nadie-dl/1003744289526_0.html

### 2.11 Trusted English-speaking tradespeople and gestores
- "Can anyone recommend a good, reliable and preferably English speaking plumber" — reply: "I can highly recommend Fontanero Costa del Sol. He doesn't speak much..." https://www.facebook.com/groups/507811220036834/posts/2164179647733308/
- "Who are reliable electricians in Costa del Sol?" / "Can anyone recommend a plumber in the Torremolinos area please?" https://www.facebook.com/groups/580086446811884/posts/1523766075777245/
- "BUILDER NEEDED: Anybody got names and numbers to recommend an English speaking builder on the Costa del Sol" https://www.facebook.com/groups/193177030191/posts/10173790342640192/
- "What is the name of the Costa Del Sol tradesmen company similar to [Checkatrade]..." (posted 3 days before 18 Sep 2026) https://www.facebook.com/groups/346826998670639/posts/28969815699278387/
- "Any recommendations for an English-speaking gestoria here on the Costa del Sol?" https://www.facebook.com/groups/ExpatsInMalaga/posts/27444353201890860/
- "Hi all I'm building a free English-language directory for local [businesses]" — La Cala Hangout https://www.facebook.com/groups/lacalahangout/posts/2870724929961711/

### 2.12 Nannies, housekeepers, pet-sitters
- "Looking for a long term Nanny & Housekeeper in Sotogrande... start in mid September 2026. I have a 8 month old boy" https://www.facebook.com/groups/sotogrande/posts/27346216371646243/
- "Family in Malaga / Marbella is looking for Live in housekeeper with papers" https://www.facebook.com/groups/257056239787703/posts/1528822095944438/
- "Looking for a nanny for my 16 month old son. Need them 3 days a week" https://www.facebook.com/groups/217378758273941/posts/26651648534420270/
- "We're looking for a dog sitter in Nueva Andalucia/ Marbella." (cross-posted to at least three groups) https://www.facebook.com/groups/346826998670639/posts/28251689157757715/
- "Dog sitter recommendations for dogs with back issues near Gibraltar and..." https://www.facebook.com/groups/2424208211192954/posts/4275608756052881/

### 2.13 Property-purchase fraud / fake professionals
- "hand over two cash deposits, of €80,000 and then €20,000, to reserve the home... once she had the cash, she disappeared" — Olive Press, 25 Aug 2026 https://www.theolivepress.es/spain-news/2026/08/25/fake-lawyer-marbella-property-scam/
- "El comprador, «confiando en que ese segundo correo provenía de su abogado..." — Marbella se queja (email-hijack in conveyancing) https://www.facebook.com/Marbellasequeja/posts/1617924326558380/
- "Un notario había aprobado un poder notarial que la mujer no había firmado. La casa fue posteriormente transferida a un tercero." — Diario Sur FB https://www.facebook.com/diariosur/posts/1498220912340862/
- "Cyber-fraudsters used sophisticated 'smishing' and 'vishing' to hijack a luxury Costa del Sol agency's bank accounts." (€2M) — Sur in English, 12 Mar 2026 https://www.surinenglish.com/malaga/marbella-san-pedro/the-complex-computer-fraud-that-swindled-two-20260312111923-nt.html
- "An elderly British expat has allegedly been defrauded of £86,000 by a couple running... disappeared without trace" — Olive Press FB https://www.facebook.com/OlivePressNewspaper/posts/1455170889958589/
- "Warning about fraudulent construction company in Fuengirola to Manilva" https://www.facebook.com/groups/931380393706802/posts/3534249200086562/

### 2.14 Málaga airport
- "Travelers frequently report facing massive, unorganized queues at passport control and security checkpoints, which lead to severe delays and missed flights." — Trustpilot summary, Airport Malaga 1.5/5 (180 reviews, Jul 2026) https://www.trustpilot.com/review/www.airport-malaga.com
- "People queuing for one and half hours for passport control. Five flights arrived in succession. Only three booths open" — La Cala Hangout https://www.facebook.com/groups/lacalahangout/posts/2771648616536010/
- "'It's a nightmare': Brits issue warnings as Malaga Airport suffers new passport queue delays... queue is around 1.5 hours long, people missing flights" — The Spanish Eye, 14 Nov 2025 https://www.thespanisheye.com/2025/11/14/its-a-nightmare-brits-issue-warnings-as-malaga-airport-suffers-new-passport-queue-delays/
- "EU Registration BEWARE!... Avoid travel through Malaga Airport! A totally disorganised airport" — Tripadvisor review 1/5, 17 May 2026 https://www.tripadvisor.com/ShowUserReviews-g187438-d32995976-r1060560581-Malaga_Airport-...
- "In the first half of 2026, 525,000 passengers met the criteria set out in European regulations to claim compensation" — Sur in English, 30 Jul 2026 https://www.surinenglish.com/malaga/malaga-city/million-passengers-face-20260730101157-nt.html

### 2.15 Water
- "La demanda de agua pone al límite la red de la Costa y fuerza una conexión urgente con Málaga. Acosol actúa con rapidez tras un repunte en julio del 15%" — Diario Sur FB https://www.facebook.com/diariosur/posts/1523404689822484/
- "No es de recibo que en pleno año 2026 tengamos vecinos sin agua potable" — Andalucía Directo (Collejares, Mijas) https://www.facebook.com/AndaluciaDirecto/posts/1444516784380158/
- "La falta de presión de agua en numerosas calles del barrio es constante, dejando a muchos vecinos directamente sin suministro o con un hilo de agua insuficiente" — Alcaldía Benalmádena FB https://www.facebook.com/alcaldiabna/posts/1502467525242308/
- "More than 4000 residents have suffered cuts and difficulties getting around between El Secadero and San Martín de Tesorillo" — Sur in English, 29 Jan 2026 (Casares floods) https://www.surinenglish.com/malaga/1500-people-cut-off-when-the-river-20260129140517-nt.html

### 2.16 Squatting (okupas) — note: heavily marketing-driven
- "Regional authorities confirmed in January 2026 that over 2,800 active squatting files have been processed" — healthplanspain.com [unverified] https://www.healthplanspain.com/blog/spain-news/2257-andalusia-squatting-crisis-2026-new-laws-property-owners.html
- "Warning after 'squatters' attempt to enter Brit's home on the Costa del Sol" — The Spanish Eye, 7 Oct 2025 https://www.thespanisheye.com/2025/10/07/...
- "The fear of unscrupulous potential squatters also dissuaded many expat owners... from renting out their second homes" — Euro Weekly, 27 Feb 2026 https://euroweeklynews.com/2026/02/27/spains-anti-eviction-of-squatters-voted-out...
- "Property squatting concerns on Costa del Sol are often exaggerated compared to actual statistics" — delsolprimehomes (agent) https://delsolprimehomes.com/en/blog/is-your-costa-del-sol-dream-home-at-risk...

### 2.17 International schools
- "Additional costs: €2,000 for a place on the waiting list and €3,000 deposit. Both are non-..." — abarzo.com (2026) https://abarzo.com/journal/the-marbella-lifestyle/international-schools-in-marbella-2026-a-complete-guide-for-families
- "Most schools maintain waiting lists, Aloha College (Marbella) charges €15,500-€18,200 annually... requires a €3,000 deposit upon acceptance" — expatpropertygroup.com
- "What are the best primary schools in Málaga, Andalusia for expat kids?... Our kids will be 6, 8, and..." https://www.facebook.com/groups/294388724750178/posts/2293129334876097/
- "Marbella has a lot of 'expats' with kids in english schools... more and more dutch and Scandinavians seem to be arriving" — r/GoingToSpain https://www.reddit.com/r/GoingToSpain/comments/1qr720p/

### 2.18 Resentment, language, expats leaving
- "Popular 'Marbella Se Queja' Instagram page rages at expats who've 'lived on the Costa del Sol for years and can't even say hola'" — Olive Press, 24 Apr 2026 https://www.theolivepress.es/spain-news/2026/04/24/marbellasequeja-expats-dont-speak-spanish/
- "Why do expats leave Spain and would they move back? Have the towns you moved to years ago become so overwhelmed by tourists that you're considering moving again?" — La Cala Hangout https://www.facebook.com/groups/lacalahangout/posts/2745157009185171/
- "Genuine pensioners who've made the full move are getting fed up." — Nerja Lovers / Costa del Sol for Expats https://www.facebook.com/groups/804813140071212/posts/2066626393889874/
- "We spent a week in Estepona thinking it was just what we were looking for - very disappointing. Over development and mostly Brits and other expats." https://www.facebook.com/groups/1691765441056300/posts/4266452246920927/
- "The Costa del Sol has a huge expat community which can be both a blessing and a trap." — r/expats https://www.reddit.com/r/expats/comments/1raztai/
- "Málaga is a beautiful place to live, but I didn't anticipate how difficult life would become for me here. lost my sense of identity." — r/expats https://www.reddit.com/r/expats/comments/1qwmp8r/

### 2.19 Elderly foreigners
- "My elderly aunt has lived in Spain for 50 years and is English. She's..." / "English-speaking care homes in San Pedro de Alcantara for dementia patients" / "UK citizens struggle to care for relatives in Spain post-Brexit" — Brexpats in Spain FB https://www.facebook.com/groups/brexpatsinspain/posts/3144770035683984/
- "Proyecto Faro... currently supporting around 240 people, mainly older residents who live alone without close family nearby" — Euro Weekly, 11 Sep 2026 https://euroweeklynews.com/2026/09/11/marbella-volunteers-are-checking-on-240-older-people-who-live-alone/
- "An ageing cohort of British expats, struggling to manage their health..." / "At 81 will my dad need..." — Leeds for Europe FB https://www.facebook.com/leedsforeurope/posts/1480545687450006/
- "Vetted Spanish care homes with real prices, English staff, waiting times, and dementia capability. No spin. Join the waitlist for the launch." — carehomesspain.com (pre-launch startup)
- "Private care homes in southern Spain typically run €2,200–€2,800 per month" — fb-answers [unverified]

### 2.20 Beach-bar rip-offs / tourist traps
- "Chiringuito is accused of 'mistaking the area for Marbella' over 'rip-off prices'" / "Marbella police announce sudden crackdown on beach bars with a week of inspections" — Olive Press FB https://www.facebook.com/OlivePressNewspaper/posts/1441054138036931/
- "Tourists horrified by Spain paella bill after mistaking €23 price" — Euro Weekly, 28 Aug 2026
- "Friendly warning for driving in Málaga, Spain: always keep coins in your car!" (gorrillas) https://www.facebook.com/groups/1691765441056300/posts/4569672169932265/
- "Please beware of the pickpockets at Malaga Airport train station." https://www.facebook.com/groups/1858109867825692/posts/3686825101620817/

---

## 3. UNDERSERVED SEGMENTS (evidence of unmet need + rough size signals)

1. **Foreign homeowners needing vetted, English-speaking tradespeople (plumber/electrician/builder/HVAC) and gestores.** Evidence: ~18 distinct "can anyone recommend" threads across at least eight FB groups in the last year, including a request for "the Costa del Sol tradesmen company similar to [Checkatrade]" (Sep 2026) and a member building "a free English-language directory". Fraud warnings about construction companies (Fuengirola–Manilva, Estepona/Marbella). Size signal: Málaga province foreigners' tax intake "nearly trebled" since pre-pandemic (Olive Press, Apr 2026); groups like La Cala Hangout, ExpatsInMalaga, Costa del Sol Constructions/Renovations group each have thousands of members [group sizes not retrieved].
2. **Elderly foreigners (75+) living alone, incl. dementia care and post-Brexit relatives.** Evidence: dementia/care-home threads, Proyecto Faro supporting 240 isolated elderly in Marbella alone, Age Concern/Age Care charities, pre-launch startup (Norry) validating a vetted care-home directory. Costs €2,200–2,800/month cited. Size: Daily Mail "Costa Geriatrica" framing; most popular British towns are Benalmádena, Mijas, Torremolinos, Fuengirola.
3. **Non-EU residents stuck in cita previa/TIE renewals (Brits on Withdrawal Agreement, Americans, Latin Americans, DNV holders).** Evidence: 14-week TIE waits, bots reselling appointments, 1.2M national applications, "4 months trying". Size: Olive Press "thousands of British expats" facing five-year renewals in 2026.
4. **Young/working locals priced out of housing (nurses, waiters, teachers).** Evidence: 64% of Málaga respondents name housing the main provincial problem; thousands marched in Málaga centre; commenter "nos quedamos en la calle"; hospitality wages €1,450 vs Marbella 2-bed rent €1,500–2,500. 20,000 registered hospitality job-seekers cannot afford to live where the jobs are.
5. **Small hospitality businesses (bars, chiringuitos) unable to staff.** Evidence: 7,000-worker shortfall, bars closing Mondays or reducing hours, a Marbella owner needing 300 hires; "personal poco formado". This is a labour-matching plus housing problem (staff accommodation offered by some).
6. **Relocating families (Nordic/Dutch/German/British) needing schools, nannies, paediatric/English healthcare.** Evidence: school waiting lists with €2k non-refundable waiting-list fee; dedicated nanny group with continuous demand posts (Marbella, Sotogrande, Fuengirola, Las Chapas); "multinational family... first grader" threads; "more and more dutch and Scandinavians seem to be arriving". Marbella fees €7–18k/year.
7. **People with reduced mobility / disabilities.** Evidence: Fuengirola's four accessible beach points served 7,798 users in ten weeks (demand proof); complaints in Torremolinos (Las Palmas) and Benalmádena (500 m wheelchair distances); Defensor del Pueblo notes delays in disability-grade assessment. Provision is municipal and patchy.
8. **Inland/urbanisation residents with poor connectivity and water pressure (Mijas, Coín, Alhaurín, Casares, Benalmádena hills).** Evidence: 47,000+ Málaga homes without adequate broadband; recurring "internet provider in La Cala?" posts; Collejares without potable water; Benalmádena "hilo de agua".
9. **Foreign property buyers exposed to impersonation/BEC fraud.** Evidence: €100k fake-lawyer case (Aug 2026), €2M smishing of a Marbella agency (Mar 2026), notary POA fraud, "second email from his lawyer". The supply side is crowded with lawyer marketing but escrow/verification tooling is absent from consumer discussion.
10. **Digital nomads / remote tech workers.** Evidence: "overrated, expensive and boring", €1,000 for 47 m², "banking and long-term lease stuff still takes local help", DNV "nightmare". Size: Málaga positioned as tech hub; 8,000+ new firms in 2025 (37% of Andalucía's).
11. **Ukrainian and other non-English/non-Spanish speakers, and undocumented migrants awaiting regularisation.** Evidence: "We feel helpless and so very angry" (Ukrainer); Cadena SER "somos invisibles, pero estamos aquí"; CEDRE alert on ethnic discrimination in housing access [national]. Weak local volume, high severity.
12. **Pet owners needing 24-hour English-speaking emergency vets (Estepona especially).** Evidence: two Costa clinics explicitly state they do not offer 24h emergency service; repeated "does anyone know of a vet in Estepona with emergency 24 hour care?".
13. **Commuters in towns without rail (Marbella, Estepona, Mijas, Vélez) facing the 2027–28 C1 closure.** Evidence: "MEDIO AÑO SIN TREN", "¿Tú sabías algo de esto?", PP "territorio de tercera".

Segments with weak complaint signal (searched, little found): LGBTQ+ residents (mostly positive safety sentiment), solo women (positive), gyms (not surfaced), removals (no Trustpilot signal).

---

## 4. WORST-RATED CATEGORIES (review distributions found)

Trustpilot coverage of Costa del Sol services is uneven: it is dense for car hire, thin for property management/removals/clinics (complaints for those live in Facebook groups and Google Maps, which I could not scrape).

| Category | Company / page | Rating (reviews) | Notes |
|---|---|---|---|
| Airport car hire (worst overall) | Goldcar España | 1.3/5 (54,455) | largest volume of 1-star reviews of any local-relevant category |
| | Thrifty.es | 1.3/5 (328) | "Paid extra insurance to cover damage" |
| | Budget España | 1.4/5 (334) | |
| | Firefly (global) | 1.2/5 (93) | "over 45 minutes at Malaga airport to pick up a car" |
| | cars.easyjet.com | 1.0/5 (537) | broker |
| | Wheego Mobility | 1.2/5 (2,209) | |
| | rentacarspain.com | 1.5/5 (91) | |
| | Delpaso Car Hire (Málaga) | 1.9–2.0/5 (1,914) | "SCAM Paid upfront" |
| | Record Go | not shown | deposit-retention narrative |
| | Clickrent | 3.5/5 (13,034) | mid |
| | Counter-examples: CarGest 4.7 (2.1k), MalagaCar.com 4.4 (1,165), Helle Hollis 4.0 (213), Allincarhire 4.0 (181), Marbella Rent a Car 3.9 (110) | | local independents rate far better than majors/brokers |
| Airport itself | "Airport Malaga" (airport-malaga.com) | 1.5/5 (180) | passport control/security queues, missed flights |
| Hotels (Tripadvisor) | Hotel Zen Airport Torremolinos 3.6 (660); Riviera Costa del Sol Benalmádena "Disappointing" (Apr 2026); Marbella destination page 3.9 (139) | | |
| Telecoms (Downdetector Málaga) | Vodafone 1.5 (49); Movistar 1.6 (86) | | outage-report ratings, not service ratings |
| Holiday rental / experiences (Marbella) | Vacation Marbella 4.1–4.3 (909); MarbsLifestyle 3.9 (57); Marbella Banús Suites 3.9 (6) | | generally OK |
| Property management / construction | Costa del Sol Home With a View 3.8 (3); Capital 1 Construction 3.4 (3) | | Trustpilot coverage negligible; complaints are in FB groups |
| Private health insurers | Adeslas, Asisa, Sanitas have Trustpilot pages | ratings not retrieved | FB threads: "Choosing health insurance in Malaga with bad reviews" |
| Consumer-body view | FACUA 2025: banking, energy, transport most complained; Junta Arbitral: telephony no.1 | | see Section 5 |

---

## 5. OFFICIAL COMPLAINT STATISTICS

- **Junta de Andalucía (Consumo):** processed **13,562 consumer complaints in 2025, +9%** vs 2024 (Día Mundial de los Derechos del Consumidor post, Mar 2026). Source: https://www.facebook.com/Saludandalucia/posts/1380207534147345/ . No Málaga-province breakdown found.
- **Junta Arbitral de Consumo de Andalucía:** resolved **21% more cases in 2025**; "La telefonía sigue siendo el sector que recibe mayor número de reclamaciones." Source: https://www.facebook.com/AndaluciaJunta/posts/1425054306313715/
- **Junta inspections 2026:** 2,200 establishments to be inspected; most complaints in "compra de ropa, zapatos, pantallas, electrodomésticos, alimentos, bebidas, accesorios". Source: https://www.facebook.com/Saludandalucia/posts/1514884197346344/
- **Hojas de reclamaciones:** Andalucía has moved to a digital system (HOJ@), physical books being phased out (Decreto 82/2022). Anecdote (Úbeda bar worker): most sheets filed in bars never reach Consumo [anecdotal].
- **FACUA (national, 2025):** **48,867 consultas y reclamaciones**; most-complained sectors: **banking, energy, transport**; FACUA criticises "inacción ante los fraudes masivos". Source: https://facua.org/noticias/banca-energia-y-transportes-los-sectores-mas-denunciados-por-los-consumidores-en-facua-en-2025/
- **Regional proxy (Granada OMIC, Ogíjares PIC):** telephony 21.96% of complaints, travel 15.12% [Granada, not Málaga].
- **Defensor del Pueblo Informe 2025:** 38,762 files nationally; **Andalucía 4,374 complaints** (2nd after Madrid 8,766); topic shares: social security & employment 8.1%, migration 6.4%, education 5.5%, housing 2.2%; explicitly notes delays/incorrect processing of foreign-qualification homologation and disability-grade assessments, and unaffordable rents (renters spending >40% of income). Source: https://www.defensordelpueblo.es/wp-content/uploads/2026/07/VOLUMEN-II-IA-2025.pdf
- **Málaga Policía Local (noise/coexistence):** weekly bulletins of **39–87 denuncias and 178–260 interventions per week** (Centro, Teatinos, Carretera de Cádiz), latest 56/178 in mid-Sep 2026. Source: https://www.facebook.com/AyuntamientodeMalaga/posts/1540321028134959/
- **OMAU terraces study (cited by AAVV Centro Antiguo):** **92% of Málaga-centre terraces breached the ordinance**, over half for excess occupation.
- **Málaga airport:** 2.1M passengers delayed in H1 2026; 525,000 eligible for compensation (Sur in English, 30 Jul 2026); punctuality 63% [malaga.is, unverified].
- **Healthcare:** 1 in 5 patients in Málaga cannot get a primary-care appointment when requesting one [FB post citing press]; average GP wait >8 days, up to 20 (SUR, Feb 2026); 5,700 Málaga doctors called to strike 16–20 Feb 2026 (Diario Sur).
- **Hospitality labour:** ~7,000 workers short in summer 2026 vs ~20,000 registered hospitality job-seekers in Málaga (LaSexta, Jul 2026); record 120,000 hospitality workers in Aug 2026 (La Opinión).
- **Broadband:** >47,000 Málaga homes lack adequate internet, worst in Mijas, Coín, Alhaurín el Grande (Málaga Hoy, 2026).
- **Housing:** 64% of Málaga respondents name housing the main provincial problem (RTV Alhaurín, Jun 2026, survey unidentified); rents +34% since 2020 [waypointsur, unverified]; Málaga third province by income effort to buy (La Opinión).
- **Squatting:** >2,800 active files in Andalucía, Jan 2026 [healthplanspain, unverified].
- **Crime:** Q1 2026 provincial crime -1.5%, cyber-scams +~11% [malaga.is, unverified].
- **Accessibility:** 7,798 users of Fuengirola accessible beaches 1 Jun–15 Aug 2026; 6,256 assisted bathing interventions (Sur in English).
- **Complaint-page reach:** "Marbella se queja" 193,237 likes / 18,825 talking about this (Sep 2026).

---

## 6. WHAT PEOPLE ASK FOR AND CAN'T FIND (ranked by observed request volume)

1. **Reliable, English-speaking plumber / electrician / builder / HVAC with a legal boletín** — the single most repeated request type (~18 threads); people explicitly ask for a Checkatrade-style vetted directory.
2. **A long-term rental they can actually get** — beyond price: landlords rejecting foreigners/freelancers/pet owners; safe way to rent remotely without being scammed.
3. **An English-speaking gestor/gestoría or solicitor who is "reasonably priced and reliable"** — recurring; trust is the issue, not supply.
4. **A cita previa (TIE/NIE/huellas)** — "no hay citas disponibles"; people pay for booking services and ask when to refresh.
5. **Nanny / live-in housekeeper "with papers" / holiday nanny** — dedicated group with constant demand (Marbella, Sotogrande, Fuengirola).
6. **Dog/pet sitter and boarding (Nueva Andalucía, Calahonda, Sotogrande), pet transport from the airport** — cross-posted requests.
7. **English-speaking dentist / GP / ENT after a bad experience; help translating at medical appointments** — plus fear of being "overcharged because you are a foreigner".
8. **A GP appointment in the public system** — 1 in 5 fail; up to 20-day waits.
9. **Internet/mobile provider that works in their urbanisation (La Cala, Marina de Casares, Mijas hills)**.
10. **English-speaking care home / dementia care / home help for an elderly relative** — with "real prices, waiting times".
11. **Private health insurance that covers pregnancy/pre-existing conditions and satisfies visa rules at affordable cost**.
12. **A non-resident bank account without high fees and with English-speaking branch staff** (especially Americans, FATCA).
13. **24-hour emergency vet with English (Estepona)**.
14. **Recommended property-management company in Marbella / trustworthy holiday-let manager with transparent fees**.
15. **Primary school choice for expat kids without a two-year waiting list and non-refundable fees**.
16. **A way to get a deposit back / dispute a 10% community-fee penalty / recover AVRA-held deposits**.
17. **English-speaking jobs in Málaga/Marbella** (SpainLINKED Jobs group) — persistent supply-side posts with few matches.
18. **Parking in Marbella centre and at Málaga hospitals at a sane price**.
19. **Information on the planned Cercanías closure and alternatives** ("¿Tú sabías algo de esto?").
20. **Reliable information on which beaches are open/clean** during sewage-related closures.

---

## 7. SOURCE LIST (by type; all consulted via search-index descriptions, 18 Sep 2026)

**Reddit**
- r/GoingToSpain: 1t3d51r (find apartment Málaga), 1uvvrff (2026 cost of living), 1s9brqd, 1np7222 (agency fee), 1pd1u77, 1ssnrqv, 1utkcfc, 1u11pgl, 1qressi, 1qgz8m1, 1qr720p (Madrid vs Marbella), 1q8zj09 (scammed), 1v649ru, 1rj4p1e
- r/Malaga: 1p3nnts (IT), 1um9bcf
- r/expats: 1qwmp8r, 1sb7ho4 (Danish expat), 1raztai, 1qsesw8, 1q7smue
- r/expat: 1utxpe3, 1orcvpr ; r/digitalnomad: 1pv5gjr, 1oylkhh, 1uhs0o2, 1v3ot8x, 1s784ak, 1ph7r51, 1nmixtr ; r/visas: 1uf4mq4 ; r/ESLegal: 1suaspv ; r/SpainAuxiliares: 1o56ajy ; r/howislivingthere: 1thwh3m, 1teut4h, 1pg1n9g, 1qxfed7 ; r/travel: 1s4c5rf ; r/MovedToSpain: 1uay9k0 ; r/artbusiness 1s1omn8 & r/ContemporaryArt 1s1gjtl (Marbella gallery scam) ; r/astrocartography 1svhgee

**Facebook groups/pages (IDs as indexed)**
- Groups: 507811220036834 (Estepona/Costa del Sol expats), 580086446811884 (Tradespeople Costa del Sol), lacalahangout, ExpatsInMalaga, malagaexpats, 1691765441056300 (Constructions/Renovations), 4833534236671708, 193177030191, 346826998670639, 1208485450770131, 3823708977862828, 1353415128870483, 217378758273941 & 257056239787703 (Nanny Marbella), 2424208211192954, sitiodecalahonda, sotogrande, 1812984208857478, 931380393706802, 210098326366137, 97904645004 (Nerja), 1858109867825692, 1556813121287509 (retirees/Brits), brexpatsinspain, 133217347273496 (WA TIE), remoteworkspain, guirisinspain, 2071774503081274 (news roundup), 793354344359351, 804813140071212 (Costa del Sol for Expats/Nerja Lovers), torrox.friends, 294388724750178, 957315298668782, 1037975736236105 (sanidad Málaga), 779686375409386 (Vecinos Fuengirola), 1832820176765576, cumbredelsol, 145898448930045 (Nerja), 7099977763373411, ExpatsClubGibraltar, 1699056880409820, 4684586171774051, 1252959488456128, 2454965321297341
- Pages: Marbellasequeja, Saludandalucia, AndaluciaJunta, antoniosanzcabello, AndaluciaDirecto, PTVMalaga, 101tvmalaga, SERMalaga, diariosur, laopiniondemalaga, PeriodicoMalagaHoy, surenglish, OlivePressNewspaper, AyuntamientodeMalaga, ayto.torremolinos, ayuntamientobenalmadena, alcaldiabna, areacostadelsol, AZCostadelSol, queestapasandoQEP, podemosmalaga, psoe.malaga, angelesmunozuriol, muyfansdeandalucia, VivaMalagaPeriodico, CSIFNacional, Rtvalhaurin, theipaper, leedsforeurope, ukrainer.eng, Turismorunningcomunicacion, esdecirdiario, everythingisboffo, GastronomiaJaen, NoticiasTrabajo2017, MarbellaVoz, lavozext, partidopopularmanilva, spainonfootheidi, targetpropertyspain, yana.sokosyuk, Osadolorvictoriavictoria
- Instagram/Threads: fuengirolasequeja, torremolinos.sequeja, benalmadenasequeja2023, andaluciadirecto reel DY460h9kVFn, SUR reel DSDDCW-kxef, alfredobloydawson DWl07_ygo6B, 101tv DZab_ZPDZMd

**Review sites**
- Trustpilot: goldcar.es, thrifty.es, www.budget.es, global.fireflycarrental.com, cars.easyjet.com, wheego-mobility.com, www.rentacarspain.com, www.delpasocarhire.com, www.recordrentacar.com, clickrent.es, www.malagacar.com, www.hellehollis.com, allincarhire.com, marbellarentacar.es, www.airport-malaga.com, vacationmarbella.com, marbellasungolf.com, swishmarbella.com, mymarbellaweekender.com, www.marbslifestyle.com, marbellabanussuites.com, costadelsolhomewithaview.net, capitaloneconstruction.es
- Tripadvisor: Costa del Sol forum g187435; Málaga forum g187438 (topics k15527867 airport queue, k15543093 EES, k15539387 reduced mobility, k15455699 airport); Nerja forum k15503633, k15505229; Torremolinos k15437571, k15477037; Malaga Airport review r1060560581; Riviera Costa del Sol r1055477364; Hotel Zen Airport d1084276; Marbella d4339698
- Downdetector: vodafone/malaga_204455, movistar/malaga_204455

**Consumer bodies / official**
- facua.org 2025 balance; Junta de Andalucía Consumo posts (13,562 complaints; Junta Arbitral +21%; 2,200 inspections; HOJ@); defensordelpueblo.es Informe 2025 Vol. II; Ayuntamiento de Málaga weekly noise bulletins; OMAU terraces study via centroantiguomalaga.com; Ogíjares PIC (Granada proxy); calidadtelecos.cnmc.gob.es; EU Home Affairs EES notice (10 Apr 2026)

**Press**
- Sur in English: 20260129140517 (Casares), 20260313113405 (drought end), 20260326104325 (Marbella parking zones), 20260511150619 (blackout compensation), 20260727143310 (fake landlord), 20260730101157 (airport delays), 20260728095753 (hotels record), 20260804101720 (Torremolinos beach bars), 20260825101242 (accessible beaches), 20260826105911 (fake lawyer), 20260312111923 (€2M fraud), 20260211122659 (new firms), 20251003173213 (AP-7 winter), 20260210112102 (tourism records)
- Diario Sur: balance-primer-dia-huelga-malaga-20260216140632; conflicto-ruidos-acaba-punetazos-20260707234725; comercios-negocios-hosteleros-cierran-alerta-roja-20260104164145
- La Opinión de Málaga: 2026/02/16 pacientes huelga; 2026/06/01 aire acondicionado multa; 2026/08/20 Fuengirola sin hogar; 2026/09/04 hostelería récord; 2026/08/24 Feria balance
- Málaga Hoy: hogares sin internet 0_2005113540; cita médico misión agotadora 0_2005440486; verano sin mano de obra 0_2006827184; ley propiedad horizontal ruido 0_2005955303; tag carreteras-malaga
- El Español Málaga: 20260618 botellón patrulla; 20250925 hosteleros alertan
- LaSexta 20260703 hostelería al límite; Cadena SER 2026/02/02 regularización; El Confidencial 2026-06-14 depuradora
- The Olive Press: 2026/08/21 beach closures; 2026/07/24 bacteria; 2026/08/25 fake lawyer; 2026/04/24 Marbella se queja; 2026/06/01 AP-7 summer rates; 2026/05/21 TIE 14 weeks; 2026/07/12 TIE renewals; 2026/03/16 Scam.org; 2026/04/01 fraudsters 2026; 2026/03/25 Hacienda scam; 2026/04/08 tax intake foreigners; 2026/02/04 flood risk; 2025/12/12 squatters; 2026/02/24 Costa Blanca agents arrested
- Euro Weekly News: 2026/08/29 Marbella parking; 2026/08/28 paella bill; 2026/08/11 Torremolinos noise; 2026/09/11 Marbella volunteers; 2026/05/31 tolls; 2026/03/27 Axarquía water; 2026/02/27 squatters law; 2026/07/05 short-term rentals; 2026/02/06 moving guide
- The Spanish Eye: 2025/11/14 airport nightmare; 2025/10/07 squatters Brit home
- Others: malaga.is (crime Q1 2026, airport delays, drought monitor, AP-7 prices) [aggregator]; healthplanspain.com (2,800 squatting files); Bloomberg 2026-02-25 (squatters); BBC (wildfire); Daily Mail (Costa Geriatrica); infobae 2025-09-29 (CaixaBank ruling Málaga); The Local FB (non-resident tax conflicts)

**Guides/marketing used only for price/size facts (flagged unverified)**
- guides.waypointsur.com (rents, schools, tolls, insurance), abarzo.com, expatpropertygroup.com, britishschoolmalaga.com (fees 26-27), delsolprimehomes.com, holidaysmalaga.com, spainexpat.com, expatica.com, fb-answers pages, carehomesspain.com, thecostacompass.com, tejadasolicitors.com, propertywire.com, costasure.com, beforeyougotravels.com, skipthefine.com, hihomes.es, ageconcernmarbella.com
