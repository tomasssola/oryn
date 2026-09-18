# 02 — Trades, Home Services, Construction & Maintenance on the Costa del Sol
*Research memo, September 2026. Domain: tradespeople reliability, construction labour, licensing, reforms, solar/aircon, pools & water, cleaning/holiday-let turnover, absentee-owner maintenance, marketplaces, insurer-backed home assistance, ITE/energy certificates, lifts, community maintenance.*

**Method & caveats.** 35 completed web searches (WebSearch + Firecrawl) in English and Spanish, plus ~10 attempts that failed on rate limits; the session's WebSearch quota was exhausted mid-task and Firecrawl returned 429s repeatedly, so fewer than the 45 target searches were completed. Direct page fetches (curl/WebFetch) were blocked by network policy, so every datum below comes from search-engine result snippets/summaries and page titles, not from reading full articles. Anything that came only from a search-engine summary without a directly attributable URL is marked **unverified**. Numbers are quoted as found; none are invented.

---

## 1. DATA TABLE

| # | Metric | Value | Date | Geography | Source |
|---|--------|-------|------|-----------|--------|
| 1 | Construction workers needed to meet housing demand | 8,000–12,000 professionals | Aug 2026 | Costa del Sol / Málaga | https://www.vidaeconomica.com/2026/08/empleo-construccion-costa-del-sol/ ; https://www.diariosur.es/costadelsol/construccion-avisa-costa-falta-12000-obreros-costadelsol-malaga-20260813152615-nt.html ; https://www.idealista.com/news/inmobiliario/construccion/2026/08/18/910126-los-constructores-alertan-de-la-falta-de-hasta-12-000-trabajadores-frente-la |
| 2 | Source of the 12,000 figure | José Andrés Mena, CEO Jamena Construcciones, Forbes Real Estate Forum Costa del Sol; "el principal freno" del mercado inmobiliario | Aug 2026 | Costa del Sol | https://www.eleconomista.es/vivienda-inmobiliario/noticias/14008043/08/26/la-costa-del-sol-necesita-hasta-12000-profesionales-para-afrontar-la-demanda-de-vivienda.html |
| 3 | Registered unemployed construction workers, Málaga province | 13,896 (Jun 2022) → 9,578 (Jun 2026), −31% | Jun 2026 | Málaga province | SEPE via https://www.que.es/2026/08/14/empleo-construccion-costa-del-sol/ (unverified secondary quoting) |
| 4 | Bricklayers urgently needed | ~10,000 albañiles | 2025 | Málaga province | La Opinión de Málaga (FB post) https://www.facebook.com/laopiniondemalaga/posts/1270693388438183/ |
| 5 | New construction employees needed over 10 years (Cedefop forecast) | ~37,000 | 2025 | Málaga | ACP Málaga https://acpmalaga.com/situacion-complicada-para-el-sector-de-la-construccion-en-malaga-falta-mano-de-obra-y-alta-demanda-de-perfiles/ |
| 6 | Salaries offered for jefes de obra / encargados | €45,000–55,000/yr | 2025 | Málaga | ACP Málaga (same URL as #5) |
| 7 | Workers needed to build required housing | 100,000 | 2025/26 | Andalucía | ABC de Sevilla (FB post) https://www.facebook.com/abcdesevilla/posts/1591434803024075/ |
| 8 | Construction employment | >272,000 workers, leads Spain; Málaga, Sevilla, Cádiz lead growth | 2025 | Andalucía | Instagram summary of press (unverified) https://www.instagram.com/reel/DcTVUTnAUYv/ |
| 9 | Additional construction workers needed nationally (CNC) | ~700,000 | 2025–26 | Spain | https://theobjective.com/economia/2026-02-26/construccion-alerta-falta-talento-buscan-albaniles-peones-electricistas/ ; https://www.infobae.com/espana/2026/09/07/la-falta-de-albaniles-y-mano-de-obra-amenaza-al-sector-de-la-construccion-y-pone-en-riesgo-la-produccion-de-viviendas/ |
| 10 | Construction vacancies hard to fill (SEPE "ajuste oferta y demanda 2026") | ~80% hard to fill; 18.6% permanently unfilled; only 2.1% filled without difficulty | 2026 | Spain | https://www.idealista.com/news/inmobiliario/vivienda/2026/09/07/911470-la-crisis-de-mano-de-obra-en-el-ladrillo-se-acelera-y-ya-es-una-de-las-grandes |
| 11 | Construction vacancies vs 2016 | ×4 | 2025 | Spain | https://www.rrhhdigital.com/secciones/actualidad/788074/la-construccion-cierra-2025-con-menos-de-la-mitad-de-ocupados-que-antes-de-la-crisis-de-2008/ |
| 12 | Share of employment in construction | 6.8% (vs 14% pre-2008); 1.56M employed end-2025 (+5.4% y/y) | 2025 | Spain | https://www.idealista.com/news/finanzas/laboral/2026/02/25/886041-la-construccion-ya-concentra-casi-el-7-del-empleo-en-espana |
| 13 | Workforce age structure | only 10% under 30; ~25% over 55 | 2026 | Spain | https://www.elconfidencialdigital.com/articulo/dinero/crisis-mano-obra-construccion-como-impacta-economia-espanola/202609031101161038673.html (unverified secondary) |
| 14 | Construction cost inflation | +5% (2025); +5.4% (2026 YTD) | 2025–26 | Spain | https://www.idealista.com/news/inmobiliario/vivienda/2026/02/26/886021-sin-trabajadores-no-hay-vivienda-barata-los-costes-de-construccion-suben-un-5-en |
| 15 | Fundación Laboral de la Construcción trainees | 124,435 people trained in 2025 (national); 28 young people via "Proyecto Aprendices" in Málaga | 2025 | Spain / Málaga | https://andalucia.fundacionlaboral.org/actualidad/noticias/territorial/proyecto-aprendices-cuenta-ya-con-28-jovenes-formados-en-malaga-para-impulsar-el-relevo-generacional-en-la-construccion |
| 16 | Legal deadline vs real average to grant a housing licence | 3 months legal; ~12 months national average; each year of delay adds ~€13,000 per home | 18 Sep 2026 | Spain | https://www.elespanol.com/invertia/observatorios/vivienda/20260918/espana-cuadruplica-plazo-legal-conceder-licencias-vivienda-espera-encarece-casa-euros/1003744387166_0.html |
| 17 | Average time to process a building licence, Málaga city (internal report) | 196 days; sample audit of 2022–23 licences: 186 days | Jul 2024 | Málaga city | https://www.elespanol.com/malaga/malaga-ciudad/20240709/meses-tarda-media-gerencia-urbanismo-malaga-tramitar-licencia-obras/869163178_0.html |
| 18 | Real waiting time for obra licences in Marbella | 3–5 months simple; up to 12 months complex; obra mayor 2–4 months; +2–6 weeks for gated-community works committee | 2025–26 | Marbella | https://costadelsolreformas.es/licencia-de-obra-en-marbella/ ; https://marbella.puntoreforma.es/blog/licencia-obra-marbella/ ; https://livener.es/licencia-obra-mayor-marbella-2025/ (industry blogs, not official) |
| 19 | Marbella new urban-planning instruction to cut licence times | approved by Junta de Gobierno Local 26 Jan 2026; single "requerimiento de subsanación", incomplete files not accepted, more declaración responsable | Jan 2026 | Marbella | https://www.marbella.es/actualidad/noticias/el-ayuntamiento-aprueba-una-nueva-instruccion-en-materia-de-urbanismo-para-reducir-plazos-y-simplificar-la-tramitacion-de-las-licencias-de-obra.html |
| 20 | Málaga city new licensing ordinance (OMLU) | approved by Pleno 25 Sep 2025 | Sep 2025 | Málaga city | https://urbanismo.malaga.eu/aprobacion-proyecto-nueva-omlu/ |
| 21 | Homes "visadas" (technical-architect stamped) | 9,033 units (+3.33% vs 2024); 6,839 completed with CFO (+6.16%) | 2025 | Málaga province | COAAT Málaga Memoria 2025 https://www.coaat.es/wp-content/uploads/pdf/MemoriaUltima.pdf |
| 22 | Direct jobs generated by subsidised rehabilitation works | ~800 | 2025 | Málaga | COAAT Málaga https://www.coaat.es/la-junta-de-andalucia-y-el-colegio-de-aparejadores-hacen-balance-de-las-ayudas-para-la-rehabilitacion/ |
| 23 | Swimming pools in Málaga province (Catastro) | 80,832 (25.8% of Andalucía); 544 covered | 2024/25 | Málaga province | https://www.andaluciainformacion.es/articulo/andalucia/casi-6500-piscinas-mas-en-un-ano-en-andalucia-que-registra-312599/202505161954212944305.html |
| 24 | Swimming pools in Málaga province (earlier Catastro cut) | 79,124 (78,606 outdoor, 518 covered) | 2024 | Málaga province | https://www.elespanol.com/malaga/20240508/torremolinos-nerja-municipios-piscinas-malaga/853415159_0.html |
| 25 | Pools in Andalucía | 312,599 (+~6,500 in one year); earlier 290,542, 80% residential | 2025 / 2022 | Andalucía | andaluciainformacion (as #23); IECA https://www.juntadeandalucia.es/institutodeestadisticaycartografia/dega/caracterizacion-y-distribucion-del-espacio-construido-en-andalucia-piscinas-garajes-y-aparcamientos/nota-divulgativa-datos-enero-2022 |
| 26 | Pools by municipality | Marbella 11,212 (2nd in Andalucía) / 10,850 (2024); Mijas 8,388 / 8,231; Málaga city 6,033; Alhaurín de la Torre 4,976 | 2024–25 | Málaga municipalities | El Español (as #24); andaluciainformacion (as #23) |
| 27 | Drought restrictions: pool filling banned for community pools | Bando Málaga city Mar 2024; whole Málaga coast (Colegio Administradores de Fincas note) | 2024 | Málaga litoral | https://www.elespanol.com/malaga/20240314/prohibido-llenar-piscinas-comunitarias-malaga-pueden-hacerlo-hoteles-gimnasios/839916469_0.html ; https://www.cafmalaga.es/prohibido-rellenar-piscinas-y-regar-jardines-en-todo-el-litoral-de-la-provincia-de-malaga/ |
| 28 | Málaga city drought bando renewed | Jan 2025 | Jan 2025 | Málaga city | https://www.malaga.eu/export/sites/malagaeu/el-ayuntamiento/el-alcalde/.galleries/Bandos/2025-01-Bando-por-la-sequia.pdf |
| 29 | Málaga lifted restrictions (Guadalhorce-Limonero system to "moderate scarcity") | May 2025; Axarquía stayed at 225 l/inhab/day, partial-fill limits in Rincón, Vélez, Algarrobo | Jun 2025 | Málaga | https://www.elespanol.com/malaga/20250601/municipios-no-podran-llenar-piscinas-malaga-verano/1003743783756_0.html |
| 30 | End of drought declared by Comité de Sequía Cuencas Mediterráneas | Apr 2026 (after ~5 years of restrictions); Axarquía cap had been 200 l/inhab/day | Apr 2026 | Málaga province | https://www.elespanol.com/malaga/20260424/embalses-secos-rozar-lleno-junta-entierra-sequia-malaga-pantanos/1003744218764_0.html ; Rincón de la Victoria bando May 2026 lifting restrictions https://rincondelavictoria.es/sites/default/files/2026-05/BANDO%20SEQU%C3%8DA%202026%20FIRMADO.pdf |
| 31 | Summer 2026 water status | "Pantanos llenos, sin restricciones" | Jul 2026 | Málaga | https://www.laopiniondemalaga.es/malaga/2026/07/01/pantanos-restricciones-duchas-abiertas-malaga-131988018.html |
| 32 | Residual local restrictions (aquifer municipalities, Antequera comarca) | 4 municipalities re-imposed bans on filling pools / garden irrigation | 2025–26 | N. Málaga | https://www.malagahoy.es/provincia/cuatro-municipios-malaga-prohiben-regar-lavar-vehiculos-llenar-piscinas-escasez_0_2006811893.html |
| 33 | Solar subsidy (NextGen autoconsumo) resolution/payment | official 4–6 months; in practice ≥1 year, often up to 2 years; direct subsidies ended 2024; funds exhausted, waiting list | 2025 | Andalucía | https://sotysolar.es/blog/como-saber-estado-de-tu-subvencion-andalucia ; https://sotysolar.es/blog/ayudas-placas-solares-andalucia ; https://www.elindependientedegranada.es/economia/iu-denuncia-que-retraso-junta-tramitar-ayudas-impiden-desarrollo-energia-renovable |
| 34 | Andalucía autoconsumo programme budget | +€75,191,133 top-up → €308,859,766 total | 2021–25 | Andalucía | https://www.juntadeandalucia.es/organismos/industriaenergiayminas/areas/energia/autoconsumo.html (via search summary; unverified figure) |
| 35 | Solar subsidy per kWp | €300–1,000/kWp depending on beneficiary | 2025 | Andalucía | https://tuexcedente.es/ayudas-autoconsumo-andalucia-2025/ |
| 36 | Plan Ecovivienda (rehabilitation) | up to 40% of PV cost, cap €3,000, open to Dec 2026; rehab aid up to 80% of works | 2025–26 | Andalucía | https://uborasolar.com/en/plan-ecovivienda-subsidy-solar-panels-andalucia/ ; https://ayudasrehabilitacionvivienda.com/andalucia/malaga/ |
| 37 | IRPF deduction for energy-efficiency works | up to 60% | 2025 | Spain | https://marblancsolar.com/three-tax-incentives-for-installing-solar-panels-in-andalusia-spain/ |
| 38 | Reparalia/HomeServe network | 2,600 professionals, 20 trades; Reparalia acquired by HomeServe 2007 | 2025 | Spain | https://mueblesporinternet.com/homeserve-opiniones-espana/ |
| 39 | HomeServe España Trustpilot | 3,407 reviews (page count 138–170 pages of reviews) | 2025 | Spain | https://www.trustpilot.com/review/homeserve.es |
| 40 | Habitissimo Trustpilot | 3.7/5 from 4,730 reviews | 2025 | Spain | https://es.trustpilot.com/review/habitissimo.es?page=2 |
| 41 | Habitissimo Pro app (Google Play) | 2.9/5 from 4,493 ratings | 2025 | Spain | https://play.google.com/store/apps/details?id=com.habitissimo.app.pro |
| 42 | Cronoshare self-reported satisfaction | 72,440 reviews, 9.1/10 | 2026 | Spain | https://www.cronoshare.com/opiniones/ |
| 43 | Costa Plumber (Riviera del Sol) Trustpilot | 4.6/5 from 19 reviews | Sep 2025 | Mijas Costa | https://www.trustpilot.com/review/costaplumber.com |
| 44 | CoastPlumber founder background | ran a 28-person plumbing firm; "20 years experience" | 2025 | Costa del Sol | https://www.coastplumber.com/about |
| 45 | Second homes in Málaga province | 170,438 (4.6% of Spain's total) | c.2024 | Málaga | CaixaBank Research https://www.caixabankresearch.com/en/sectoral-analysis/real-estate/second-homes-spain-seaside-or-sierra |
| 46 | Foreign owners of homes in Málaga (Catastro) | 41,953 foreigners | c.2024 | Málaga | https://www.winkworth.es/malagas-tax-revenue-from-foreign-property-owners-has-tripled-since-2019/ (unverified secondary) |
| 47 | Non-resident foreign buyers share of sales | 27.9% of Málaga sales in 2025 | 2025 | Málaga | https://www.guidetomalaga.com/need-to-know-malaga/buy-rent-property/malaga-property-report/ (unverified) |
| 48 | Foreign-resident homeowners | 19% of Costa del Sol homeowners | 2025 | Costa del Sol | https://rightcasa.com/foreign-residents-in-the-costa-del-sol-2025/ (estate-agent blog) |
| 49 | Keyholding price point | €89/yr incl. IVA (one provider) | 2025 | Costa del Sol | https://costa-del-sol-property-management.com/professional-key-holding-service/ |
| 50 | Cleaning job ads, Málaga province | ~1,460 "limpiadora" ads on Jooble; 75 "limpieza apartamento turístico"-type ads on Indeed | Jun 2026 | Málaga | https://es.jooble.org/trabajo-limpiadora/M%C3%A1laga ; https://es.indeed.com/q-limpieza-de-hoteles-l-m%C3%A1laga-provincia-empleos.html |
| 51 | Shadow economy | 24% of GDP (Spain, 3rd in EU); construction & reforms sector ~29% underground | 2025 | Spain | https://economia3.com/2025/05/28/697493-la-economia-sumergida-fuera-del-radar-del-fisco/ ; https://hoyeconomia.es/economia-sumergida-espana/ (29% figure unverified) |
| 52 | Reduced VAT on home renovation | 10% if owner is individual, home ≥2 yrs old, materials ≤40% of base | ongoing | Spain | https://sede.agenciatributaria.gob.es/Sede/iva/iva-operaciones-inmobiliarias/que-tipo-se-aplica-obras-viviendas.html |
| 53 | ITE Málaga 2025 campaign | buildings from 1974 (first ITE) and 1964 (10-yr renewal); deadline 31 Jan 2026; fee €30 favourable / €50 unfavourable; renew every 10 yrs | 2025 | Málaga city | https://coamalaga.es/noticias/campana-de-2025-relativa-la-inspeccion-tecnica-de-edificios-en-el-municipio-de-malaga/ ; https://www.coaat.es/ite-malaga-listado-de-titulares-obligados-en-la-campana-2025/ |
| 54 | Lifts: new ITC AEM 1 (RD 355/2024) | in force 1 Jul 2024; expired inspection = immediate lift stoppage; maintenance fees rose in some communities | 2024 | Spain / Málaga | https://www.boe.es/buscar/doc.php?id=BOE-A-2024-7258 ; https://upelevadores.es/nueva-normativa-itc-aem-1-ascensores-malaga/ |
| 55 | Energy certificate: fine for missing EPC | up to €6,000; from 1 Apr 2026 G-rated certificates valid only 5 yrs; EU target E by 2030, D by 2033; EPBD transposition due May 2026 | 2026 | Spain | https://icerti.es/certificado-energetico-en-2026-cuando-es-obligatorio-que-ha-cambiado-y-como-conseguirlo/ ; https://gbce.es/todas-las-viviendas-de-espana-deberan-tener-como-minimo-un-certificado-de-eficiencia-d-en-2033/ ; https://www.ocu.org/vivienda-y-energia/calefaccion/noticias/epbd-certificado-energetico |
| 56 | Tourist-rental registration | National single registry mandatory from 1 Jul 2025; new Andalucía requirements from 4 Mar 2025 | 2025 | Andalucía | https://www.checkinscan.net/registering-a-tourist-property-in-andalusia/ ; https://alquilerviviendavacacional.com/andalucia-si-quieres-que-tu-vivienda-de-uso-turistico-cumpla-con-la-normativa/ |
| 57 | Estepona: max period for certain municipal requests | 1 month from registry entry (ordinance) | ongoing | Estepona | https://ayuntamiento.estepona.es/docs/dee35afebe288af1ccbeea3f763bd6d5.pdf |
| 58 | Spanish grid saturation (relevant to PV/heat-pump connections) | 86.5% | Sep 2026 | Spain | https://www.idealista.com/news/inmobiliario/vivienda/2026/09/18/914901-la-red-electrica-espanola-alcanza-ya-una-saturacion-del-86-5-segun-el-foro |
| 59 | Tourist homes (INE, platform-listed) in Málaga province | 45,176 (May 2026) vs 48,412 (May 2025) = −6.6%; 48,176 in Nov 2025; #1 province in Spain (Alicante 32,148; Las Palmas 26,998) | Jun 2026 | Málaga province | https://www.elespanol.com/malaga/20260625/regulacion-empieza-tumbar-boom-vivienda-turistica-malaga-ano/1003744298178_0.html ; https://www.laopiniondemalaga.es/malaga/2026/06/24/malaga-lidera-espana-viviendas-turisticas-2026-municipios-barrios-centro-palo-131758477.html |
| 60 | Marbella tourist homes (INE) | 6,987 units, 36,435 places — 4th municipality nationally | Jun 2026 | Marbella | https://www.malagahoy.es/malaga/malaga-lidera-parque-vivienda-turistica_0_2007177410.html |
| 61 | Andalucía tourist homes (INE) | 90,649 (Málaga ≈ half of regional supply) | Jun 2026 | Andalucía | https://www.andaluciainformacion.es/articulo/malaga-economia/malaga-consolida-como-capital-piso-turistico-espana-pese-caida-sector/202606241840313412448.html |
| 62 | Registro de Turismo de Andalucía VUT stock | ~85,000 properties; Junta admits up to 30% not operative; "only half of registered tourist homes in Málaga are active" | Feb 2026 | Andalucía / Málaga | https://www.diariosur.es/malaga/solo-mitad-viviendas-turisticas-registradas-activas-tres-20260210000435-nt.html |
| 63 | Junta cancellations of VUT registrations | ~10,600 cancelled in Andalucía | 2025–26 | Andalucía | Málaga Hoy (FB post) https://www.facebook.com/PeriodicoMalagaHoy/posts/1646901017445213/ |
| 64 | Ministry of Housing request to delist tourist flats | 21,872 flats (national) | 2025 | Spain | FB (Mijas group) https://www.facebook.com/groups/mijas1/posts/2850872401787541/ (unverified) |
| 65 | Málaga city moratorium on new tourist flats/hotels on residential land | in force from 26 Jul 2025 | Jul 2025 | Málaga city | PTV Málaga (FB) https://www.facebook.com/PTVMalaga/posts/1905510010837116/ |
| 66 | Málaga has the census section with highest tourist-flat pressure in Spain | 9 of 10 dwellings are tourist flats | 2025 | Málaga city | https://www.datadista.com/mapas/conoce-la-presion-de-los-pisos-turisticos-en-tu-calle/ |
| 67 | National platform-listed tourist homes | 329,764 in Nov 2025, −46,699 y/y | Nov 2025 | Spain | https://www.eleconomista.es/vivienda-inmobiliario/noticias/13767370/02/26/espana-registra-casi-47000-anuncios-menos-de-viviendas-turisticas-en-el-ultimo-ano-en-plena-ofensiva-del-gobierno.html |
| 69 | Second-hand house price, Málaga province | €3,842/m² record (Aug 2025); Málaga €3,620/m² Sep 2025 (+17% y/y) | 2025 | Málaga | https://www.idealista.com/en/news/property-for-sale-in-spain/2025/10/03/862629-costa-del-sol-property-prices-reach-record-highs-in-2025 ; https://www.idealista.com/en/news/property-for-sale-in-spain/2025/10/20/863042-malaga-house-prices-soar-to-eu3-620-m2-up-17-in-a-year |
| 70 | Home sales, Málaga province | ~35,000/yr (−4% y/y); 8,714 in Q1 2026 | Q1 2026 | Málaga | https://www.guidetomalaga.com/need-to-know-malaga/buy-rent-property/malaga-property-report/ |
| 71 | Homes approved (licensed) in Málaga province | 9,475 in 2025; 3,195 in Q1 2026 | 2025–26 | Málaga | https://investropa.com/blogs/news/malaga-good-time (secondary, unverified) |
| 72 | New-build vs resale asking price, Costa del Sol | €6,167/m² vs €4,710/m² median (+31%) | 2026 | Costa del Sol | https://arevont.com/market-stats/new-build-vs-resale (agency data) |
| 73 | Málaga city VUT cap upheld by TSJA | 8% of dwellings per neighbourhood; moratorium on new VUT confirmed | Apr 2026 | Málaga city | https://www.elespanol.com/malaga/malaga-ciudad/20260410/golpe-judicial-pisos-turisticos-tsja-avala-estrategia-malaga-limitar-expansion/1003744199620_0.html |
| 74 | Tourist-flat cleaner pay (ad) | €800/month for 4h/day (≈€9/h) | 2026 | Málaga | Facebook ad (unverified employer) https://www.facebook.com/AyuntamientodeMalaga/posts/1507834984716897/ |
| 75 | Tourism-sector vacancies on InfoJobs | 30,364 (2025) vs 26,376 (2024), +15% | 2025 | Spain | https://recursos-humanos.infojobs.net/wp-content/uploads/2026/03/Informe_Mercado_Laboral_InfoJobs_Esade_2025_Digital.pdf |
| 76 | Andalucía autoconsumo/storage incentive programme closed to new applications | 23 Jan 2025 | Jan 2025 | Andalucía | Agencia Andaluza de la Energía https://www.agenciaandaluzadelaenergia.es/en/node/3063 |
| 77 | New national PV incentive framework | RD-ley 7/2026 (20 Mar 2026): IRPF deduction up to 40% for residential solar (per installer summary) | Mar 2026 | Spain | https://www.boe.es/buscar/act.php?id=BOE-A-2026-6544 ; https://solar-master-malaga.com/en/solar-grants-andalucia/ |
| 78 | Renewables added in Andalucía | record 2,888 MW in 2025 → 17,360 MW total (+20%) (mostly utility-scale) | 2025 | Andalucía | https://renewablesnow.com/news/spains-andalusia-region-adds-record-2-888-mw-of-renewables-in-2025-1290926/ |
| 79 | Home-reform delay caused by bricklayer shortage | up to 1 year wait to reform a home; home works +1.6% in 2025 | Dec 2025 | Spain | https://www.elperiodico.com/es/sociedad/20251201/obras-reforma-viviendas-retrasos-meses-falta-albaniles-construccion-124136474 |
| 80 | Residential construction cost increase (ACR) | +5.5% in 2025 | Feb 2026 | Spain | https://www.diarioenpositivo.com/economia/economia-costes-construccion-subieron-55-2025-escasez-mano-obra-acr/20260226100105074595.amp.html |
| 81 | Construction-project disputes (industry survey) | 61% had a recent dispute over delays; 66% expect one | 2025 | global/Spain | https://www.constructionbriefing.com/es/news/encuesta-revela-los-mayores-riesgos-y-disputas-en-proyectos-de-construccion/8044912.article |
| 68 | VUT community rule | 3/5 majority of community can restrict tourist use (LO 1/2025); max fine €150,000 very serious | 2025 | Andalucía | https://property.sleepaways.com/blog/normativa-alojamientos-turisticos-andalucia (secondary) |

---

## 2. PAIN POINTS
(Frequency/intensity estimates are the researcher's judgement from snippet density, not measured.)

### 2.1 Tradesperson reliability: no-shows, not returning, work left unfinished
Snippets:
- "After being let down before, this felt much easier. Found a painter in Fuengirola who gave a fair quote, arrived on time…" — customer testimonial used by CostaTrades as its core proposition. https://www.costatrades.com/
- "Do not use his services. Goes by different names so we can't find him, don't use him unless you want to lose your money and be left with unfinished work!" — Facebook group post, "Warning about home improvement fraud in Estepona and Marbella". https://www.facebook.com/groups/7747601335259646/posts/27090392323887258/
- "Communication is poor, accountability is almost nonexistent, and there is virtually no concept of customer service or warranty follow-through." — expat Facebook post (Spain-wide group), with related threads "Beware of builders who don't honor quotes in Estepona". https://www.facebook.com/groups/barcelonaexpatsgroup/posts/25711401805145219/
- "Electrician let us down – anyone else had this experience?" … paid in full, no CIE certificate delivered (Costa Blanca forum, same operator as costadelsolforum). https://www.costablancaforum.com/area/pinar-de-campoverde-spain-107/recommended-tradesmen-companies-in-pinar-de-campoverde-22/can-anyone-recommend-electrician-let-us-down-anyone-else-had-this-experience-184419/
- r/askspain thread: "I bought an apartment three months ago and had to do some renovations. So I needed bricklayers, electricians, plumbers, and air conditioning…" titled "Is this lack of professionalism/organization normal?" https://www.reddit.com/r/askspain/comments/1kc90r2/es_normal_esta_poca_profesionalidadorganizaci%C3%B3n/?tl=en
- Facebook group "Local TRUSTED Tradesman…Costa Del Sol": "Looking for trusted tradesman or looking to avoid COWBOYS with bad reputations…" https://www.facebook.com/groups/117985475548280/
- "Is there any group 'blacklist of contractors' on the Costa del Sol?" — related Facebook thread. https://www.facebook.com/groups/barcelonaexpatsgroup/posts/7322131114498901/
Frequency: **very high** (recurrent "can anyone recommend…" threads on costadelsolforum for every town, multiple dedicated FB groups). Intensity: medium for small jobs, high for renovations.

### 2.2 Deposit-and-vanish renovation fraud, no contract / no guarantee
- "A group-recommended builder takes a large upfront deposit, starts demolition, then disappears." — Waypoint Sur safety guide on Costa del Sol scams. https://guides.waypointsur.com/safety-crime-costa-del-sol/
- "…a trail of broken promises and unfinished homes across the Costa del Sol serves as a warning to expats looking to buy off-plan." — Olive Press, Jul 2026. https://www.theolivepress.es/spain-news/2026/07/06/off-plan-property-profitable-spain/
- Guardia Civil warning on "reformas fantasma": scammers keep the advance, "normalmente el 50% del presupuesto". https://canalferretero.com/noticia/14370-reformas-fantasma-la-nueva-estafa-sobre-la-que-alerta-la-guardia-civil/
- "Decenas de afectados y cientos de miles de euros estafados por una empresa fraudulenta de reformas en Almería y Granada" (ALTIA brand, multiple shell companies, near-100% advance payments). https://www.elplural.com/sociedad/decenas-afectados-cientos-miles-euros-estafados-empresa-fraudulenta-reformas-almeria-granada_341888102
- "This is a warning about FAKE BUILDERS in Spain… If a builder is advertising to expats and claims to have many years…" https://www.facebook.com/groups/barcelonaexpatsgroup/posts/7322131114498901/
Frequency: medium. Intensity: **very high** (losses of €10k–100k+).

### 2.3 Black-economy pricing, no invoices, no VAT — and the resulting lack of recourse
- Shadow economy 24% of GDP; construction/reforms among the most affected sectors (~29%, unverified). https://economia3.com/2025/05/28/697493-la-economia-sumergida-fuera-del-radar-del-fisco/
- Hacienda's list of the 10 professions with most tax fraud includes building trades. https://www.euribor.com.es/2026/04/28/las-10-profesiones-con-mas-fraude-fiscal-en-espana-segun-hacienda/
- Your Overseas Home advises expats to "avoid casual labour" and compare estimates. https://www.youroverseashome.com/spain/advice/spain-tradespeople/
Frequency: **very high** (structural). Intensity: medium (creates the enabling condition for 2.1 and 2.2; also blocks 10% VAT and IRPF deductions that require invoices).

### 2.4 English-speaking scarcity / language & trust gap
- "Can anyone recommend an English speaking plumber in the Velez area?" https://www.costadelsolforum.com/area/v%C3%A9lez-m%C3%A1laga-spain-231/recommended-tradesmen-companies-in-v%C3%A9lez-m%C3%A1laga-22/can-anyone-recommend-an-english-speaking-plumber-in-the-velez-area-406/
- "Reliable English-speaking plumber needed ・ work will include general plumbing and maintenance, such as leaks, taps, toilets…" (Mijas FB group). https://www.facebook.com/groups/910170433053214/posts/2313820096021567/
- "What websites list trusted English speaking tradespeople in Costa del Sol?" (Constructions/Renovations Costa del Sol FB group, "I'm new to this group… is there an online app or website that I can use to search for all kinds of reviewed and trusted…"). https://www.facebook.com/groups/constructionsrenovationscostadelsol/posts/1206419630581987/
- Some expats prefer Spanish tradesmen "because they're willing to return if work hasn't been satisfactory" (expatforum thread). https://www.expatforum.com/threads/homeowners-on-the-costa-del-sol.9329/
Frequency: **high** among the ~42k foreign owners + 170k second homes. Intensity: medium.

### 2.5 Construction labour shortage → long waits, rising prices, refused jobs
- "Todas las empresas del sector reportan problemas para encontrar mano de obra, tanto para cubrir trabajos actuales como para aspirar a nuevos contratos." — ACP Málaga. https://acpmalaga.com/situacion-complicada-para-el-sector-de-la-construccion-en-malaga-falta-mano-de-obra-y-alta-demanda-de-perfiles/
- "el problema ya no es solo encontrar profesionales cualificados, sino garantizar el relevo generacional" — J.A. Mena, Jamena. https://www.eleconomista.es/vivienda-inmobiliario/noticias/14008043/08/26/la-costa-del-sol-necesita-hasta-12000-profesionales-para-afrontar-la-demanda-de-vivienda.html
- "Muchos trabajadores prefieren quedarse en sus lugares de origen incluso con menores salarios… debido a las dificultades para encontrar vivienda asequible en Málaga." — ACP Málaga (same URL).
- "En España, hay mucho trabajo [en construcción y] poca mano de obra" — Argentine bricklayer content creator, COPE Málaga. https://www.cope.es/emisoras/andalucia/malaga-provincia/noticias/matias-armani-albanil-argentino-espana-hay-trabajo-construccion-poca-mano-obra-falta-gente-trabajo-20260227_3317228.html
- Idealista: shortage "ha dejado de ser un problema coyuntural"; impact = "costes más altos, plazos más largos y, en ciertos casos, renuncia directa a nuevos proyectos". https://www.idealista.com/news/inmobiliario/vivienda/2026/09/07/911470-la-crisis-de-mano-de-obra-en-el-ladrillo-se-acelera-y-ya-es-una-de-las-grandes
- **Home-reform waits**: "La falta de albañiles provoca retrasos de hasta un año para reformar una vivienda… Las obras en casas se disparan un 1,6% en 2025 pese a que el sector adolece de al menos 700.000 trabajadores cualificados." — El Periódico, 1 Dec 2025. https://www.elperiodico.com/es/sociedad/20251201/obras-reforma-viviendas-retrasos-meses-falta-albaniles-construccion-124136474
- "Los albañiles coinciden: 'Obras que antes podían durar seis o siete meses ahora van…'" — "La escasez de trabajadores afecta a toda la cadena de construcción, provocando retrasos y complicaciones en presupuestos y entregas." — El Español, 4 Aug 2026. https://www.elespanol.com/ciencia/20260804/albaniles-coinciden-obras-podian-durar-meses-ahora-van/1003744339742_0.html
- Residential construction costs +5.5% in 2025 attributed to labour scarcity (ACR). https://www.diarioenpositivo.com/economia/economia-costes-construccion-subieron-55-2025-escasez-mano-obra-acr/20260226100105074595.amp.html
Frequency: **very high** (every industry body). Intensity: high and rising.

### 2.6 Building-licence delays
- "El plazo legal para conceder una licencia de obra es de tres meses… pero la media en el país alcanza ya los 12 meses" (+€13,000/home/yr). https://www.elespanol.com/invertia/observatorios/vivienda/20260918/espana-cuadruplica-plazo-legal-conceder-licencias-vivienda-espera-encarece-casa-euros/1003744387166_0.html
- Málaga city average 196 days (internal report, 2024). https://www.elespanol.com/malaga/malaga-ciudad/20240709/meses-tarda-media-gerencia-urbanismo-malaga-tramitar-licencia-obras/869163178_0.html
- Marbella: "entre 3 y 5 meses para las sencillas y hasta 12 para las complejas"; gated communities add "2 a 6 semanas adicionales para la aprobación del comité de obras". https://costadelsolreformas.es/licencia-de-obra-en-marbella/
- Marbella and Mijas both announced simplification instructions (Marbella Jan 2026; Mijas "simplifica la tramitación de licencias urbanísticas"). https://www.mijas.es/portal/mijas-simplifica-la-tramitacion-de-licencias-urbanisticas/
Frequency: high for any obra mayor. Intensity: high (capital tied up, contractors lost to other jobs while waiting).

### 2.7 Solar / PV: subsidy delays, funds exhausted, installer follow-up
- "Many homeowners in the region waited 2–3 years for grant money, and thousands were refused without a clear explanation." (search summary of Andalucía PV subsidy coverage — **unverified**, source not pinned)
- "en la práctica el pago suele tardar un mínimo de un año desde la solicitud, y en muchos casos se demora hasta dos años" — SotySolar. https://sotysolar.es/blog/como-saber-estado-de-tu-subvencion-andalucia
- "IU denuncia que el retraso de la Junta en tramitar las ayudas impiden el desarrollo de la energía renovable de autoconsumo". https://www.elindependientedegranada.es/economia/iu-denuncia-que-retraso-junta-tramitar-ayudas-impiden-desarrollo-energia-renovable
- OCU public complaints vs HomeServe about "Mantenimiento de placas solares y batería" (11/04/2025) and "Problema servicio placas solares" (11/07/2025). https://www.ocu.org/reclamar/lista-reclamaciones-publicas/mantenimiento-de-placas-solare/b15584fecbd90b04f2 ; https://www.ocu.org/reclamar/lista-reclamaciones-publicas/problema-servicio-placas-solar/f8b3e86bf0ba9efea9
Frequency: high among the 2021–24 subsidy cohort. Intensity: medium-high (€1–3k per household outstanding).

### 2.8 Pools, gardens and water
- "Prohibido llenar las piscinas comunitarias en Málaga; sí pueden hacerlo los hoteles y los gimnasios" (Mar 2024). https://www.elespanol.com/malaga/20240314/prohibido-llenar-piscinas-comunitarias-malaga-pueden-hacerlo-hoteles-gimnasios/839916469_0.html
- "Prohibido rellenar piscinas y regar jardines en todo el litoral de la provincia de Málaga" — Colegio de Administradores de Fincas. https://www.cafmalaga.es/prohibido-rellenar-piscinas-y-regar-jardines-en-todo-el-litoral-de-la-provincia-de-malaga/
- 2026: "la Junta entierra la sequía en Málaga" after 5 years; "Pantanos llenos, sin restricciones". https://www.elespanol.com/malaga/20260424/embalses-secos-rozar-lleno-junta-entierra-sequia-malaga-pantanos/1003744218764_0.html
- Expat villa owners "torn apart by excessive water bills which threaten some property owners with ruin" (Olive Press, 2023). https://www.theolivepress.es/spain-news/2023/12/17/dispatch-the-idyllic-andalucian-retreat-favoured-by-expats-that-finds-itself-being-torn-apart-by-excessive-water-bills-which-threaten-some-property-owners-with-ruin/
Frequency: cyclical — acute 2022–25, dormant 2026 but structural (5-year drought just ended; ~80k pools). Intensity: high during restrictions (communities unable to refill; pool firms' cash flow).

### 2.9 Insurer-backed home assistance (HomeServe/Reparalia) — slow, hard to reach, opaque billing
- "una semana para que me llamase el fontanero"; waiting "desde enero para reparar un enchufe quemado"; "alrededor de 20 minutos antes de contestar el teléfono o no responden" (Trustpilot). https://www.trustpilot.com/review/homeserve.es
- "más de 15 días esperando para recibir la factura de una reparación pagada al contado". (Trustpilot, same URL)
- "reparadora cara y mala que cobra desplazamientos inflados por cambios de cisterna". (Trustpilot, same URL)
- OCU 2025 complaints: "FALTA DE SERVICIO" (06/05/2025), "Contratan en mi nombre" (04/11/2025, suspected auto-inclusion via Banco Santander home insurance), "Problema con la baja del seguro" (21/10/2025). https://www.ocu.org/reclamar/empresas/homeserve/500000297
Frequency: high (3,400+ Trustpilot reviews, steady OCU stream). Intensity: medium.

### 2.10 Lead-gen marketplaces (Habitissimo/Cronoshare) — pros pay for unverified leads; reviews gamed
- Habitissimo Pro app: "El servicio al cliente es pésimo… Los usuarios no están verificados, compras contactos que después no…" (2.9★, 4,493 ratings). https://play.google.com/store/apps/details?id=com.habitissimo.app.pro
- OCU: "He intentado poner una reseña negativa a una empresa de reformas que encontré en su web… y no me dejan publicarla". https://www.ocu.org/reclamar/lista-reclamaciones-publicas/no-publican-mi-rese-C3-B1a-negativa/d4e5bdbe5dc1550bc2
- Pro Facebook group: "CronoShare es una plataforma… que opera fraudulentamente por todo el país" (pro complaint about paying for leads). https://www.facebook.com/groups/245844466162628/posts/924364904977244/
- Xataka on "pagar por aspirar a trabajar" (Upwork/Cronoshare model). https://www.xataka.com/pro/pagar-aspirar-a-trabajar-como-portales-internet-como-upwork-cronoshare-pueden-cambiar-relacion-trabajador-empresa-cliente
Frequency: high among pros. Intensity: medium.

### 2.11 Absentee owners / second homes need someone on the ground
- "Keyholding is a legal requirement for non-residents who own a home" (industry claim, **unverified** legally). https://spainpropertymanagement.com/key-holding-services/riviera-del-sol/
- Typical packages: "secure keyholding, a 24/7 emergency contact number, and monthly or bi-monthly property inspections with a status report". https://www.calistoco.com/costadelsol-property-management
- 170,438 second homes in Málaga; 41,953 foreign owners (Catastro). See data table.
Frequency: high. Intensity: medium (peaks at leaks/break-ins/storm damage).

### 2.12 Regulatory-driven maintenance obligations (ITE, lifts, EPC)
- "una inspección caducada supone la paralización inmediata del ascensor" (ITC AEM 1, in force 1 Jul 2024). https://upelevadores.es/nueva-normativa-itc-aem-1-ascensores-malaga/
- ITE Málaga 2025 campaign: 1974 buildings first inspection, 1964 buildings renewal, deadline 31 Jan 2026. https://coamalaga.es/noticias/campana-de-2025-relativa-la-inspeccion-tecnica-de-edificios-en-el-municipio-de-malaga/
- EPC: G-rated certificates only 5-yr validity from 1 Apr 2026; fines up to €6,000. https://icerti.es/certificado-energetico-en-2026-cuando-es-obligatorio-que-ha-cambiado-y-como-conseguirlo/
Frequency: medium (campaign-driven). Intensity: medium-high for affected communities (lift stoppage, ITE unfavourable → forced works).

### 2.13 Holiday-let turnover cleaning — labour-intensive, high churn, sub-minimum pay
- UGT housing report (Mar 2026): "las trabajadoras de limpieza en pisos turísticos suelen cobrar por debajo del SMI y en condiciones de explotación". https://www.ugt.es/sites/default/files/informes/2026-03-18-INFORME_VIVIENDA.pdf
- Job ad circulating on Facebook (Málaga): "Tareas: Limpieza, planchado y apoyo general en apartamentos turísticos… Pago: 800 €/mes (media jornada, 4 horas diarias)" — i.e. ≈€9.1/h, roughly at/below SMI hourly. https://www.facebook.com/AyuntamientodeMalaga/posts/1507834984716897/ (comment thread; unverified employer)
- "Málaga Hideaway busca una limpiadora confiable y motivada para nuestros apartamentos de vacaciones en la región de Málaga, Benalmádena y Fuengirola" (open vacancy page). https://malagahideaway.com/es/vacante-de-empleada-de-limpieza/
- Housing cost drives the labour gap: "La crisis de vivienda golpea fuerte a los trabajadores… forzándolos a tener varios empleos" (RTS, tourism towns). https://www.facebook.com/rtsfuerteventura/posts/1078064821287003/
- Regulatory overhang: TSJA (Apr 2026) upheld Málaga's PGOU change, 8% cap per neighbourhood and moratorium on new VUT. https://www.elespanol.com/malaga/malaga-ciudad/20260410/golpe-judicial-pisos-turisticos-tsja-avala-estrategia-malaga-limitar-expansion/1003744199620_0.html
- Ads: "Se necesita urgente: Limpieza apartamento turístico en Málaga" (Jooble, 2026); ~1,460 cleaner job ads in Málaga. https://es.jooble.org/trabajo-limpieza-apartamento-turistico/M%C3%A1laga
- Community administrators note buildings with many tourist flats "suelen pagar más porque la carga de gestión —incidencias, comunicaciones, vigilancia de normativa turística— es significativamente mayor". https://www.presidentedelacomunidad.es/articulos/administradores-fincas-malaga
- Spain "faces summer staff shortage as 2026 tourist season accelerates" (EWN, Jun 2026). https://euroweeklynews.com/2026/06/04/spain-faces-summer-staff-shortage-as-2026-tourist-season-accelerates/
Frequency: high (proxy: job-ad volume). Intensity: medium. **Evidence: weak/indirect** — no article found quantifying cleaner shortage specific to holiday lets in Málaga.

---

## 3. COMPETITOR LANDSCAPE

| Pain served | Player | What they do | Traction / ratings found | Weaknesses observed |
|---|---|---|---|---|
| Finding a vetted English-speaking trade | **CostaTrades** (costatrades.com) | Directory of "verified English-speaking tradespeople"; town pages (Mijas, Fuengirola…) | Self-described "leading directory"; testimonials on site; no third-party rating found | Directory model (listing, not accountability); no visible guarantee/escrow; unknown volume |
| Same | **Trust A Trade / SpainMadeSimple recommended tradespeople** | Review-based directory | Listed as "review based website" | Thin, static listings; SEO-content site rather than operator |
| Same | **Solares Energies "Find a local tradesperson"** | Solar installer cross-selling a "#1 Costa del Sol" trade finder | Claims to have "collected information, including reviews on thousands of tradespeople" (unverified) | Conflict of interest (installer running a directory) |
| Same | **Facebook groups**: "Local TRUSTED Tradesman…Costa Del Sol", "Trust a trader Costa Del Sol", "Costa del Sol Constructions, Renovations, Home…", town groups (Mijas, Fuengirola) | Free recommendation threads | Very high engagement; recurring "can anyone recommend" posts; also where scam warnings surface | Zero verification; recommendations gamed by traders; "group-recommended builder takes a large upfront deposit… then disappears" |
| Same | **costadelsolforum.com** "Recommended Tradesmen and Companies" boards per town | Forum threads | Long-running, town-by-town | Old, unstructured, no ratings |
| Emergency plumbing | **CoastPlumber** (coastplumber.com) | Lead-router: "connects English-speaking homeowners with vetted plumbers"; photo-first quoting | New (2025); founder ex-28-person firm | Single trade; capacity depends on a small vetted pool |
| Emergency plumbing | **Costa Plumber / Marbella Plumber** (costaplumber.com, marbellaplumber.com) | Owner-operator plumbers with SEO sites | Trustpilot 4.6/5 (19 reviews) | Capacity-limited sole traders |
| Multi-trade | **Costa Sol Services**, **Repairs & Construction**, **The Costa Fixers**, **Promas Building**, **Gerards Buildmasters**, **LT Construction** | Small builders / handymen with English marketing | Anecdotal reputations | Same fragmentation; each covers 1–2 towns |
| Lead-gen marketplace (ES) | **Habitissimo** (HomeServe-owned) | Pros buy leads; reviews | Trustpilot 3.7 (4,730); Pro app 2.9 (4,493) | Unverified leads, review-suppression complaints, pros hostile |
| Lead-gen marketplace (ES) | **Cronoshare** | Pay-per-contact | Self-reported 9.1/10 on 72k reviews; Confianza Online seal | Pro backlash ("opera fraudulentamente"), SEO-black-hat accusations on YouTube |
| Lead-gen (ES) | **ProntoPro, Plan Reforma, Trustlocal, Hogarconfort, Wallapop Servicios** | Directories / lead-gen | Present in Málaga searches | Generic, Spanish-only UX, no local ops |
| Insurer-backed repairs | **HomeServe España / Reparalia** | 2,600 pros, 20 trades; assistance for insurers + subscriptions | 3,407 Trustpilot reviews; steady OCU complaint stream | Slow dispatch (days–months), call-centre friction, billing delays, alleged unsolicited enrolment via bank-sold insurance |
| Insurer-backed repairs | Insurer assistance networks (Mapfre, Allianz, Santander-Mapfre, etc.) | Included in hogar policies | — | Not researched in depth (search budget) |
| Property management for absentees | **Costa Home Management, Calisto, cu-inspain, Passion4Property, SolRentSpain, Costa del Sol Habitat, Estate Stockholm, ServiceHero** | Keyholding €89/yr up to full management; inspections, cleaning, pool/garden | Fragmented; dozens of micro-firms | No standard, no tech, no SLA; reputational risk when they subcontract trades |
| Community maintenance | **Administradores de fincas** (Colegio Málaga & Melilla) | Coordinate suppliers, incidents, ITE, lifts | Málaga city created "administrador de oficio" for communities without resources (with IMV) | Overloaded, esp. buildings with many tourist flats; procurement is informal |
| Lifts | Otis/Schindler/Kone/Orona + locals (UPelevadores…) | Maintenance contracts | RD 355/2024 raised obligations and fees | Price rises; inspection-lapse risk |
| Solar | SotySolar, Solfy, Autosolar, Marblanc Solar, Ubora, RAD Energy, Aficlima, Solares Energies | Install + subsidy paperwork | Marketing-heavy | Subsidy paperwork and after-sales are the friction points; HomeServe entered PV maintenance and already draws OCU complaints |

**UK/US/DE analogs for reference:** Checkatrade/TrustATrader (UK vetting + reviews; Reddit: "All they really do is act as a directory. They increase prices for customers as the trades have to pay"), Pimlico Plumbers (UK employed-workforce premium operator), Angi/Thumbtack (US lead-gen), Frontdoor/American Home Shield (US home warranty), MyHammer (DE), Dubai FM firms (bundled facility management for absentee investors).

---

## 4. REGULATORY FACTS (with dates and sources)

1. **Licence deadline**: legal maximum 3 months to resolve a licencia de obra (Ley 7/2021 LISTA, Andalucía); national real average ~12 months (El Español, 18 Sep 2026). https://www.elespanol.com/invertia/observatorios/vivienda/20260918/espana-cuadruplica-plazo-legal-conceder-licencias-vivienda-espera-encarece-casa-euros/1003744387166_0.html
2. **Marbella**: new urbanism instruction approved 26 Jan 2026 (single subsanación, incomplete files rejected, wider declaración responsable). https://www.marbella.es/actualidad/noticias/el-ayuntamiento-aprueba-una-nueva-instruccion-en-materia-de-urbanismo-para-reducir-plazos-y-simplificar-la-tramitacion-de-las-licencias-de-obra.html
3. **Málaga city**: new OMLU (Ordenanza Municipal de Licencias Urbanísticas) approved by Pleno 25 Sep 2025. https://urbanismo.malaga.eu/aprobacion-proyecto-nueva-omlu/
4. **Mijas**: streamlined procedures for obra menor, first-occupation and opening licences; "tramitación prioritaria" designations by Junta de Gobierno. https://www.mijas.es/portal/mijas-simplifica-la-tramitacion-de-licencias-urbanisticas/
5. **ITE Málaga city**: campaign 2025 covers buildings built 1974 (first) and 1964 (renewal); deadline 31 Jan 2026; 10-year renewal; fees €30/€50. https://coamalaga.es/noticias/campana-de-2025-relativa-la-inspeccion-tecnica-de-edificios-en-el-municipio-de-malaga/
6. **Lifts**: RD 355/2024 (ITC AEM 1) in force 1 Jul 2024; lapsed inspection = immediate stoppage; new maintainer duties. https://www.boe.es/buscar/doc.php?id=BOE-A-2024-7258
7. **Energy certificates**: mandatory for sale/rent; fines to €6,000; from 1 Apr 2026 stricter criteria and 5-year validity for G; EPBD (Directive 2024/1275) transposition due May 2026; EU trajectory E by 2030 / D by 2033 (OCU notes the directive does not itself ban selling E/F/G homes). https://www.ocu.org/vivienda-y-energia/calefaccion/noticias/epbd-certificado-energetico ; https://gbce.es/todas-las-viviendas-de-espana-deberan-tener-como-minimo-un-certificado-de-eficiencia-d-en-2033/
8. **Drought decrees**: Málaga city bando Mar 2024 banning community-pool filling; renewed Jan 2025; restrictions lifted May 2025 (Guadalhorce) and drought formally ended Apr 2026 (Cuencas Mediterráneas). Sources in data table rows 27–31.
9. **Tourist rentals**: national single registry (Colegio de Registradores) mandatory from 1 Jul 2025; Andalucía extra requirements from 4 Mar 2025. https://www.checkinscan.net/registering-a-tourist-property-in-andalusia/
10. **Reduced VAT**: 10% on renovation/repair for private homes ≥2 years old when materials ≤40% of the taxable base (AEAT). https://sede.agenciatributaria.gob.es/Sede/iva/iva-operaciones-inmobiliarias/que-tipo-se-aplica-obras-viviendas.html
11. **Solar subsidies**: NextGen autoconsumo direct grants closed 2024 in Andalucía; Plan Ecovivienda (rehab, up to 40% PV cap €3,000) open to Dec 2026; IRPF deductions up to 60%. https://sotysolar.es/blog/ayudas-placas-solares-andalucia ; https://uborasolar.com/en/plan-ecovivienda-subsidy-solar-panels-andalucia/
12. **Estepona** ordinance: one-month maximum for certain municipal requests (not obra mayor). https://ayuntamiento.estepona.es/docs/dee35afebe288af1ccbeea3f763bd6d5.pdf
13. **Marbella PGOM (new General Plan)**: Junta regional approval 22 Feb 2026, transmitted to the town hall for definitive approval; replaces the annulled 2010 plan / reverted 1986 rules — expected to unlock licences and reduce legal uncertainty. https://www.mpdunne.com/blog/marbella-general-plan-pgom-pou ; https://www.mak-1.com/news/marbella-town-hall-reaches-final-stages-for-the-definitive-approval-of-the-pgom ; RTV Marbella notes "tendencia al alza en la concesión de nuevas licencias" https://www.facebook.com/RTVMarbella/posts/1564270939035001/
14. **Marbella** new regulation on abandoned developments, deteriorated buildings and unused plots (forced maintenance/ejecución subsidiaria potential). https://www.maspropertymarbella.com/marbella-approves-new-regulation-to-tackle-abandoned-developments/
15. **Benchmark**: Sevilla claims licences "en menos de siete días" under its new Ordenanza de Obras y Actividades (declaración responsable model) — shows what Costa municipalities could adopt. https://www.facebook.com/abcdesevilla/posts/1321280383372853/
16. **Solar**: Andalucía autoconsumo incentive line closed to new applications 23 Jan 2025 (Agencia Andaluza de la Energía); RD-ley 7/2026 of 20 Mar 2026 sets a new national framework (installer blogs cite IRPF deduction up to 40%). https://www.agenciaandaluzadelaenergia.es/en/node/3063 ; https://www.boe.es/buscar/act.php?id=BOE-A-2026-6544
17. **Tourist flats, Málaga city**: moratorium on new VUT/hotels on residential land from 26 Jul 2025; TSJA upheld PGOU change and 8%-per-neighbourhood cap (Apr 2026); national single registry mandatory since 1 Jul 2025. Sources in data table rows 59–68, 73.

---

## 5. CANDIDATE OPPORTUNITIES

### O1. "Pimlico-style" employed multi-trade emergency & small-works operator for the expat coast (Marbella–Fuengirola–Benalmádena)
- **Pain**: 2.1, 2.3, 2.4 (no-shows, no invoice, no English). **Evidence: strong** (forum/FB density; CostaTrades and CoastPlumber both exist because of it; no employed-workforce operator found).
- **Who pays**: foreign homeowners (41,953 foreign owners; 170k second homes; 27.9% of 2025 sales to non-residents) at premium fixed rates; property managers as B2B.
- **Size logic**: if 10% of foreign-owned homes buy one €150 call-out/yr → ~€630k; add small works (avg €1,500) at 3% penetration → ~€1.9M; plausible €2–5M revenue at scale in one operator on the western coast.
- **Existing players & edge**: sole traders (Costa Plumber 4.6★/19 reviews), lead routers (CoastPlumber), directories (CostaTrades). Edge = uniformed employed techs, invoiced 10% VAT, fixed price book published online, 2-hour arrival windows, written guarantee, English/Spanish/Nordic support.
- **Analogs**: Pimlico Plumbers (UK), HomeServe's own direct-labour hubs, Dubai FM firms.
- **Risks**: labour shortage (12,000 gap) makes hiring hardest part; housing costs deter workers relocating (ACP); seasonality; convenio construcción costs.

### O2. Escrow-backed renovation manager ("milestone payments + independent QS") for expat reforms
- **Pain**: 2.2, 2.6 (deposit fraud, unfinished works, licence delays). **Evidence: strong** for fraud pattern (Guardia Civil, El Plural ALTIA case, FB warnings), medium for Costa-specific frequency.
- **Who pays**: renovating owners (typical reform €30k–150k) paying 5–8% PM fee; contractors accept because escrow guarantees payment.
- **Size logic**: 9,033 homes visadas in 2025 in Málaga (new build); reform volume not found (gap) — proxy: Habitissimo/Cronoshare lead volume. Even 300 projects/yr × €60k × 6% = €1.1M fees.
- **Existing players & edge**: architects/aparejadores do dirección de obra but not escrow; Cronoshare "Garantía" is limited. Edge = staged-payment escrow, licence tracking (Marbella instruction Jan 2026), bilingual reporting, blacklist-checked contractors.
- **Analogs**: Buildpass/Fixflo-style, Portugal's expat build-management firms, US Angi Guarantee; UK "Buildstore" staged payments.
- **Risks**: handling client money (payment-institution rules); PM liability; contractor scarcity.

### O3. Pool & garden "drought-resilient" maintenance subscription with water compliance
- **Pain**: 2.8 (80,832 pools; 5-year drought just ended; bans on filling/irrigation 2024–25; expat water-bill shocks). **Evidence: strong** on pool count and restrictions; medium on willingness to pay premium.
- **Who pays**: villa owners (Marbella 11,212 pools; Mijas 8,388; Alhaurín 4,976) and communities (administradores).
- **Size logic**: 80k pools × ~€100/month typical maintenance → ~€96M/yr addressable in the province; capturing 2% = €1.9M.
- **Existing players & edge**: fragmented "pool guys"; no one bundles leak detection, cover/evaporation control, water-usage reporting, and legal compliance with bandos. Edge = IoT monitoring + water-audit + bulk-water/recycled-water logistics ready for the next drought cycle.
- **Analogs**: US Pool Scouts / Pinch A Penny franchise, Australia's drought-era pool services.
- **Risks**: 2026 is a wet year (demand for drought features drops); price competition from informal operators.

### O4. Absentee-owner "home care" platform with SLA (inspection + emergency response + trades marketplace)
- **Pain**: 2.11, 2.1, 2.9 (insurer assistance slow). **Evidence: medium-strong** (170k second homes; dozens of micro keyholders at €89/yr; HomeServe complaints).
- **Who pays**: non-resident owners €30–80/month; upsell repairs.
- **Size logic**: 170,438 second homes; 5% at €50/month = €5.1M ARR.
- **Existing players & edge**: Costa Home Management, Calisto, etc. — no tech, no SLA. Edge = app with photo-verified inspections, 24/7 bilingual dispatch, transparent trade pricing, insurance-claim handling against slow HomeServe-type networks.
- **Analogs**: Frontdoor/American Home Shield (home warranty), Hostmaker-style ops, Dubai/Algarve concierge FM.
- **Risks**: acquiring owners cheaply (channel = estate agents, lawyers, community administrators); liability.

### O5. Turnover-cleaning & linen ops for holiday lets (workforce-as-a-service)
- **Pain**: 2.13 — labour churn, "se necesita urgente" ads; community friction with tourist flats. **Evidence: weak-medium** (job-ad volume only; no numbers on shortage found; registry counts not retrieved).
- **Who pays**: STR managers/hosts €40–90 per turnover.
- **Size logic**: registry counts for Málaga not retrieved (gap; Junta registry needed). If 40k VUT × 40 turnovers/yr × €50 = €80M gross market (illustrative, unverified base).
- **Existing players & edge**: Riviera Clean, Limpiplus, Guadaluz, Coast Cleaners. Edge = scheduling software + guaranteed cover + employed (not cash) cleaners, compliance with 2025 registry rules.
- **Analogs**: Properly, TurnoverBnB, Doinn (Portugal).
- **Risks**: thin margins; regulatory squeeze on STRs (Andalucía 2025 rules) could shrink demand.

### O6. Subsidy & compliance concierge for owners/communities (PV grants, Ecovivienda rehab, ITE, EPC, lift ITC)
- **Pain**: 2.7, 2.12 (grants take 1–2 years; ITE campaigns; lift-stoppage risk; EPC changes Apr 2026). **Evidence: medium** (delays documented; volume of pending PV files not retrieved).
- **Who pays**: communities via administradores; installers (white-label); owners (success fee on grants, 10–15%).
- **Size logic**: Andalucía autoconsumo pot €308.9M; Ecovivienda up to 80% of rehab cost; ITE fees trivial but consequent works are large.
- **Existing players & edge**: installers do paperwork ad hoc; ayudasrehabilitacionvivienda.com-type sites. Edge = tracking dashboard, appeals for refusals, bundling ITE→rehab→grant.
- **Analogs**: US solar-incentive processors (EnergySage), UK ECO-scheme brokers.
- **Risks**: grant policy volatility (NextGen funds exhausted 2024); dependence on Junta processing.

### O7. Vetted-trades marketplace with accountability (reviews + insurance + invoice guarantee), English/Spanish, Costa-only
- **Pain**: 2.1, 2.4, 2.10 (Habitissimo/Cronoshare distrusted by pros and users). **Evidence: strong** for demand ("What websites list trusted English speaking tradespeople…"), medium for monetisation.
- **Who pays**: trades (membership €50–150/month) + homeowner job fee; possibly insurers.
- **Size logic**: Málaga construction employed ≈ share of Andalucía's 272k; if 3,000 small firms/autónomos in trades on the coast and 10% subscribe at €100/mo → €3.6M ARR.
- **Existing players & edge**: CostaTrades (directory), Habitissimo/Cronoshare (lead-gen, unverified). Edge = document-verified pros (alta autónomo, RC insurance, TC2), mandatory invoice, dispute mediation, Checkatrade-style vetting with local ops staff.
- **Analogs**: Checkatrade/TrustATrader (UK), MyHammer (DE), Thumbtack (US).
- **Risks**: chicken-and-egg; FB groups are free; Checkatrade critique ("increase prices for customers as the trades have to pay").

### O8. Skilled-labour supply: bilingual training-and-placement / staffing for coastal contractors
- **Pain**: 2.5 (8–12k worker gap; 18.6% vacancies permanently unfilled; workers won't relocate without housing). **Evidence: strong**.
- **Who pays**: contractors (placement fees 10–20% of salary; temp-staffing margin); Fundación Laboral/Junta programmes.
- **Size logic**: 12,000 vacancies × €30k salary = €360M wage pool; 1% placement share × 15% fee ≈ €540k; staffing margin model larger.
- **Existing players & edge**: Fundación Laboral (28 trainees in Málaga "Proyecto Aprendices"), Fundación Jamena, Proycen, ETTs. Edge = recruit Latin-American/EU tradespeople (COPE story), housing partnerships, English-language training for expat-facing work.
- **Analogs**: US trade-school partnerships (Home Depot Path to Pro), Germany's Handwerk migration programmes.
- **Risks**: regulation of ETTs, worker housing costs in Málaga, convenio.

### O9. Community (comunidad de propietarios) maintenance-contract aggregator for administradores
- **Pain**: 2.12, 2.8, 2.9 — administrators juggling lifts (ITC), ITE, pools, gardens, insurance claims; buildings with tourist flats cost more to run. **Evidence: medium**.
- **Who pays**: communities via administrator (bundled contract), 5–10% aggregator margin.
- **Size logic**: not sized (no count of communities retrieved); Málaga city created an "administrador de oficio" scheme, signalling strain.
- **Edge**: single bilingual contract + SLA + compliance calendar (ITE, lift inspection, pool sanitary rules, EPC) + emergency desk.
- **Analogs**: UK block-management FM (FirstPort), Dubai owners-association FM.
- **Risks**: procurement inertia; administrators' existing supplier relationships/kickbacks.

---

## 5b. EVIDENCE GAPS (not retrieved because of search-quota exhaustion; flag for follow-up)
- Count of registered viviendas de uso turístico in Málaga province / Marbella / Málaga city (Junta RTA registry, 2025–26).
- Number of pending / refused PV-subsidy files in Andalucía (Agencia Andaluza de la Energía figures).
- Marbella's own count of pending licence files and average resolution time after the Jan 2026 instruction.
- Reform/renovation volume for Málaga (Andimac, Habitissimo/Cronoshare lead counts, obra menor declaraciones responsables per municipality).
- Aircon/heat-pump (aerotermia) installation volumes and summer waiting times in Málaga.
- Locksmith and pest-control complaint data (FACUA/OCU) for Málaga.
- Holiday-let cleaner pay/conditions and shortage articles specific to Málaga.
- Hourly rates for plumbers/electricians on the Costa (only generic guides seen).

## 6. SOURCE LIST
(All accessed via search snippets 18 Sep 2026; full text not fetched.)

Labour / construction
- https://www.vidaeconomica.com/2026/08/empleo-construccion-costa-del-sol/
- https://www.diariosur.es/costadelsol/construccion-avisa-costa-falta-12000-obreros-costadelsol-malaga-20260813152615-nt.html
- https://www.idealista.com/news/inmobiliario/construccion/2026/08/18/910126-los-constructores-alertan-de-la-falta-de-hasta-12-000-trabajadores-frente-la
- https://www.eleconomista.es/vivienda-inmobiliario/noticias/14008043/08/26/la-costa-del-sol-necesita-hasta-12000-profesionales-para-afrontar-la-demanda-de-vivienda.html
- https://www.que.es/2026/08/14/empleo-construccion-costa-del-sol/
- https://www.lavozdelsur.es/ediciones/malaga/la-costa-del-sol-en-malaga-busca-desesperadamente-hasta-12000-trabajadores-para-el-sector-de-la-construccion.html
- https://acpmalaga.com/situacion-complicada-para-el-sector-de-la-construccion-en-malaga-falta-mano-de-obra-y-alta-demanda-de-perfiles/
- https://www.infobae.com/espana/2026/09/07/la-falta-de-albaniles-y-mano-de-obra-amenaza-al-sector-de-la-construccion-y-pone-en-riesgo-la-produccion-de-viviendas/
- https://www.idealista.com/news/inmobiliario/vivienda/2026/09/07/911470-la-crisis-de-mano-de-obra-en-el-ladrillo-se-acelera-y-ya-es-una-de-las-grandes
- https://www.idealista.com/news/inmobiliario/vivienda/2026/02/26/886021-sin-trabajadores-no-hay-vivienda-barata-los-costes-de-construccion-suben-un-5-en
- https://www.idealista.com/news/finanzas/laboral/2026/02/25/886041-la-construccion-ya-concentra-casi-el-7-del-empleo-en-espana
- https://theobjective.com/economia/2026-02-26/construccion-alerta-falta-talento-buscan-albaniles-peones-electricistas/
- https://www.rrhhdigital.com/secciones/actualidad/788074/la-construccion-cierra-2025-con-menos-de-la-mitad-de-ocupados-que-antes-de-la-crisis-de-2008/
- https://www.elconfidencialdigital.com/articulo/dinero/crisis-mano-obra-construccion-como-impacta-economia-espanola/202609031101161038673.html
- https://www.aisla.org/construccion-espana-2026-empleo-mano-obra-cualificada/
- https://www.sepe.es/HomeSepe/en/que-es-el-sepe/comunicacion-institucional/noticias/detalle-noticia?folder=%2FSEPE%2F2025%2FFebrero%2F&detail=catalogo-ocupaciones-dificil-cobertura-primer-trimestre-2025
- https://andalucia.fundacionlaboral.org/actualidad/noticias/territorial/proyecto-aprendices-cuenta-ya-con-28-jovenes-formados-en-malaga-para-impulsar-el-relevo-generacional-en-la-construccion
- https://www.facebook.com/laopiniondemalaga/posts/1270693388438183/
- https://www.facebook.com/abcdesevilla/posts/1591434803024075/
- https://www.cope.es/emisoras/andalucia/malaga-provincia/noticias/matias-armani-albanil-argentino-espana-hay-trabajo-construccion-poca-mano-obra-falta-gente-trabajo-20260227_3317228.html
- https://www.coaat.es/wp-content/uploads/pdf/MemoriaUltima.pdf
- https://www.coaat.es/la-junta-de-andalucia-y-el-colegio-de-aparejadores-hacen-balance-de-las-ayudas-para-la-rehabilitacion/

Licensing
- https://www.elespanol.com/invertia/observatorios/vivienda/20260918/espana-cuadruplica-plazo-legal-conceder-licencias-vivienda-espera-encarece-casa-euros/1003744387166_0.html
- https://www.elespanol.com/malaga/malaga-ciudad/20240709/meses-tarda-media-gerencia-urbanismo-malaga-tramitar-licencia-obras/869163178_0.html
- https://www.marbella.es/actualidad/noticias/el-ayuntamiento-aprueba-una-nueva-instruccion-en-materia-de-urbanismo-para-reducir-plazos-y-simplificar-la-tramitacion-de-las-licencias-de-obra.html
- https://www.panoramamarbella.com/news/marbella-building-licences
- https://costadelsolreformas.es/licencia-de-obra-en-marbella/
- https://marbella.puntoreforma.es/blog/licencia-obra-marbella/
- https://livener.es/licencia-obra-mayor-marbella-2025/
- https://urbanismo.malaga.eu/aprobacion-proyecto-nueva-omlu/
- https://www.mijas.es/portal/mijas-simplifica-la-tramitacion-de-licencias-urbanisticas/
- https://mijascomunicacion.com/actualidad/30328/el-ayuntamiento-de-mijas-simplifica-y-agiliza-los-tramites-para-las-licencias-urbanisticas/
- https://ayuntamiento.estepona.es/docs/dee35afebe288af1ccbeea3f763bd6d5.pdf

Tradesperson reliability / fraud / marketplaces
- https://www.costatrades.com/
- https://www.coastplumber.com/ ; https://www.coastplumber.com/about
- https://www.trustpilot.com/review/costaplumber.com
- https://www.spainmadesimple.com/costa-del-sol/recommended-tradespeople/
- https://solaresenergies.com/services/find-a-local-tradesperson/
- https://www.costadelsolforum.com/area/all/recommended-tradesmen-companies-in-costa-del-sol-22/
- https://www.costadelsolforum.com/area/v%C3%A9lez-m%C3%A1laga-spain-231/recommended-tradesmen-companies-in-v%C3%A9lez-m%C3%A1laga-22/can-anyone-recommend-an-english-speaking-plumber-in-the-velez-area-406/
- https://www.costablancaforum.com/area/pinar-de-campoverde-spain-107/recommended-tradesmen-companies-in-pinar-de-campoverde-22/can-anyone-recommend-electrician-let-us-down-anyone-else-had-this-experience-184419/
- https://www.facebook.com/groups/7747601335259646/posts/27090392323887258/
- https://www.facebook.com/groups/barcelonaexpatsgroup/posts/25711401805145219/
- https://www.facebook.com/groups/barcelonaexpatsgroup/posts/7322131114498901/
- https://www.facebook.com/groups/constructionsrenovationscostadelsol/posts/1206419630581987/
- https://www.facebook.com/groups/117985475548280/
- https://www.facebook.com/groups/2414709035442962/
- https://www.facebook.com/groups/910170433053214/posts/2313820096021567/
- https://www.reddit.com/r/askspain/comments/1kc90r2/es_normal_esta_poca_profesionalidadorganizaci%C3%B3n/?tl=en
- https://www.expatforum.com/threads/homeowners-on-the-costa-del-sol.9329/
- https://guides.waypointsur.com/safety-crime-costa-del-sol/
- https://www.theolivepress.es/spain-news/2026/07/06/off-plan-property-profitable-spain/
- https://canalferretero.com/noticia/14370-reformas-fantasma-la-nueva-estafa-sobre-la-que-alerta-la-guardia-civil/
- https://www.elplural.com/sociedad/decenas-afectados-cientos-miles-euros-estafados-empresa-fraudulenta-reformas-almeria-granada_341888102
- https://www.youroverseashome.com/spain/advice/spain-tradespeople/
- https://es.trustpilot.com/review/habitissimo.es?page=2
- https://play.google.com/store/apps/details?id=com.habitissimo.app.pro
- https://www.cronoshare.com/opiniones/
- https://www.facebook.com/groups/245844466162628/posts/924364904977244/
- https://www.ocu.org/reclamar/lista-reclamaciones-publicas/no-publican-mi-rese-C3-B1a-negativa/d4e5bdbe5dc1550bc2
- https://www.xataka.com/pro/pagar-aspirar-a-trabajar-como-portales-internet-como-upwork-cronoshare-pueden-cambiar-relacion-trabajador-empresa-cliente
- https://www.reddit.com/r/DIYUK/comments/13dmgdk/is_checkatrade_and_other_similar_sites_actually/

Insurer-backed assistance
- https://www.trustpilot.com/review/homeserve.es
- https://es.trustpilot.com/review/reparalia.es
- https://www.ocu.org/reclamar/empresas/homeserve/500000297
- https://www.ocu.org/reclamar/lista-reclamaciones-publicas/mantenimiento-de-placas-solare/b15584fecbd90b04f2
- https://www.ocu.org/reclamar/lista-reclamaciones-publicas/falta-de-servicio/fbb01ba0167288b88d
- https://www.ocu.org/reclamar/lista-reclamaciones-publicas/contratan-en-mi-nombre/7483b9df28d9e3ff38
- https://mueblesporinternet.com/homeserve-opiniones-espana/

Pools / water
- https://www.andaluciainformacion.es/articulo/andalucia/casi-6500-piscinas-mas-en-un-ano-en-andalucia-que-registra-312599/202505161954212944305.html
- https://www.elespanol.com/malaga/20240508/torremolinos-nerja-municipios-piscinas-malaga/853415159_0.html
- https://www.juntadeandalucia.es/institutodeestadisticaycartografia/dega/caracterizacion-y-distribucion-del-espacio-construido-en-andalucia-piscinas-garajes-y-aparcamientos/nota-divulgativa-datos-enero-2022
- https://www.elespanol.com/malaga/20240314/prohibido-llenar-piscinas-comunitarias-malaga-pueden-hacerlo-hoteles-gimnasios/839916469_0.html
- https://www.cafmalaga.es/prohibido-rellenar-piscinas-y-regar-jardines-en-todo-el-litoral-de-la-provincia-de-malaga/
- https://www.malaga.eu/export/sites/malagaeu/el-ayuntamiento/el-alcalde/.galleries/Bandos/2025-01-Bando-por-la-sequia.pdf
- https://www.elespanol.com/malaga/20250601/municipios-no-podran-llenar-piscinas-malaga-verano/1003743783756_0.html
- https://www.elespanol.com/malaga/20260424/embalses-secos-rozar-lleno-junta-entierra-sequia-malaga-pantanos/1003744218764_0.html
- https://www.laopiniondemalaga.es/malaga/2026/07/01/pantanos-restricciones-duchas-abiertas-malaga-131988018.html
- https://www.malagahoy.es/provincia/cuatro-municipios-malaga-prohiben-regar-lavar-vehiculos-llenar-piscinas-escasez_0_2006811893.html
- https://rincondelavictoria.es/sites/default/files/2026-05/BANDO%20SEQU%C3%8DA%202026%20FIRMADO.pdf
- https://www.theolivepress.es/spain-news/2023/12/17/dispatch-the-idyllic-andalucian-retreat-favoured-by-expats-that-finds-itself-being-torn-apart-by-excessive-water-bills-which-threaten-some-property-owners-with-ruin/

Solar / energy / regulation
- https://sotysolar.es/blog/como-saber-estado-de-tu-subvencion-andalucia
- https://sotysolar.es/blog/ayudas-placas-solares-andalucia
- https://www.elindependientedegranada.es/economia/iu-denuncia-que-retraso-junta-tramitar-ayudas-impiden-desarrollo-energia-renovable
- https://www.juntadeandalucia.es/organismos/industriaenergiayminas/areas/energia/autoconsumo.html
- https://tuexcedente.es/ayudas-autoconsumo-andalucia-2025/
- https://uborasolar.com/en/plan-ecovivienda-subsidy-solar-panels-andalucia/
- https://marblancsolar.com/three-tax-incentives-for-installing-solar-panels-in-andalusia-spain/
- https://ayudasrehabilitacionvivienda.com/andalucia/malaga/
- https://icerti.es/certificado-energetico-en-2026-cuando-es-obligatorio-que-ha-cambiado-y-como-conseguirlo/
- https://gbce.es/todas-las-viviendas-de-espana-deberan-tener-como-minimo-un-certificado-de-eficiencia-d-en-2033/
- https://www.ocu.org/vivienda-y-energia/calefaccion/noticias/epbd-certificado-energetico
- https://www.idealista.com/news/inmobiliario/vivienda/2026/09/18/914901-la-red-electrica-espanola-alcanza-ya-una-saturacion-del-86-5-segun-el-foro
- https://coamalaga.es/noticias/campana-de-2025-relativa-la-inspeccion-tecnica-de-edificios-en-el-municipio-de-malaga/
- https://www.coaat.es/ite-malaga-listado-de-titulares-obligados-en-la-campana-2025/
- https://www.elespanol.com/malaga/malaga-ciudad/20250321/nueva-inspeccion-tecnica-edificios-ite-malaga-cambios-requisitos/932906920_0.html
- https://www.boe.es/buscar/doc.php?id=BOE-A-2024-7258
- https://upelevadores.es/nueva-normativa-itc-aem-1-ascensores-malaga/
- https://feeda.es/nuevas-medidas-obligatorias-que-los-administradores-de-fincas-deberan-tener-en-cuenta-sobre-la-futura-normativa-itc/

Shadow economy / VAT
- https://economia3.com/2025/05/28/697493-la-economia-sumergida-fuera-del-radar-del-fisco/
- https://hoyeconomia.es/economia-sumergida-espana/
- https://www.euribor.com.es/2026/04/28/las-10-profesiones-con-mas-fraude-fiscal-en-espana-segun-hacienda/
- https://sede.agenciatributaria.gob.es/Sede/iva/iva-operaciones-inmobiliarias/que-tipo-se-aplica-obras-viviendas.html

Second homes / property management / cleaning / communities
- https://www.caixabankresearch.com/en/sectoral-analysis/real-estate/second-homes-spain-seaside-or-sierra
- https://www.winkworth.es/malagas-tax-revenue-from-foreign-property-owners-has-tripled-since-2019/
- https://www.guidetomalaga.com/need-to-know-malaga/buy-rent-property/malaga-property-report/
- https://rightcasa.com/foreign-residents-in-the-costa-del-sol-2025/
- https://www.thespanisheye.com/2026/04/24/more-than-half-of-malaga-landlords-own-multiple-properties-new-report-shows/
- https://costa-del-sol-property-management.com/professional-key-holding-service/
- https://www.calistoco.com/costadelsol-property-management
- https://www.costahomemanagement.com/
- https://servicehero.es/en/property-management-costa-del-sol/
- https://spainpropertymanagement.com/key-holding-services/riviera-del-sol/
- https://es.jooble.org/trabajo-limpiadora/M%C3%A1laga
- https://es.jooble.org/trabajo-limpieza-apartamento-turistico/M%C3%A1laga
- https://es.indeed.com/q-limpieza-de-hoteles-l-m%C3%A1laga-provincia-empleos.html
- https://rivieraclean.es/limpieza-pisos-vacacionales-malaga/ ; https://limpiplusmalaga.com/ ; https://coastcleaners.es/services/
- https://www.presidentedelacomunidad.es/articulos/administradores-fincas-malaga
- https://amfincas.com/administradores-de-fincas-de-oficio-para-comunidades-sin-recursos/
- https://euroweeklynews.com/2026/06/04/spain-faces-summer-staff-shortage-as-2026-tourist-season-accelerates/
- https://www.checkinscan.net/registering-a-tourist-property-in-andalusia/
- https://alquilerviviendavacacional.com/andalucia-si-quieres-que-tu-vivienda-de-uso-turistico-cumpla-con-la-normativa/
- https://www.elespanol.com/malaga/20260625/regulacion-empieza-tumbar-boom-vivienda-turistica-malaga-ano/1003744298178_0.html
- https://www.laopiniondemalaga.es/malaga/2026/06/24/malaga-lidera-espana-viviendas-turisticas-2026-municipios-barrios-centro-palo-131758477.html
- https://www.malagahoy.es/malaga/malaga-lidera-parque-vivienda-turistica_0_2007177410.html
- https://www.diariosur.es/malaga/solo-mitad-viviendas-turisticas-registradas-activas-tres-20260210000435-nt.html
- https://www.andaluciainformacion.es/articulo/malaga-economia/malaga-consolida-como-capital-piso-turistico-espana-pese-caida-sector/202606241840313412448.html
- https://www.elespanol.com/malaga/malaga-ciudad/20260410/golpe-judicial-pisos-turisticos-tsja-avala-estrategia-malaga-limitar-expansion/1003744199620_0.html
- https://www.datadista.com/mapas/conoce-la-presion-de-los-pisos-turisticos-en-tu-calle/
- https://www.eleconomista.es/vivienda-inmobiliario/noticias/13767370/02/26/espana-registra-casi-47000-anuncios-menos-de-viviendas-turisticas-en-el-ultimo-ano-en-plena-ofensiva-del-gobierno.html
- https://www.ugt.es/sites/default/files/informes/2026-03-18-INFORME_VIVIENDA.pdf
- https://malagahideaway.com/es/vacante-de-empleada-de-limpieza/
- https://recursos-humanos.infojobs.net/wp-content/uploads/2026/03/Informe_Mercado_Laboral_InfoJobs_Esade_2025_Digital.pdf

Reform delays / costs / licensing extras
- https://www.elperiodico.com/es/sociedad/20251201/obras-reforma-viviendas-retrasos-meses-falta-albaniles-construccion-124136474
- https://www.elespanol.com/ciencia/20260804/albaniles-coinciden-obras-podian-durar-meses-ahora-van/1003744339742_0.html
- https://www.diarioenpositivo.com/economia/economia-costes-construccion-subieron-55-2025-escasez-mano-obra-acr/20260226100105074595.amp.html
- https://www.constructionbriefing.com/es/news/encuesta-revela-los-mayores-riesgos-y-disputas-en-proyectos-de-construccion/8044912.article
- https://www.mpdunne.com/blog/marbella-general-plan-pgom-pou
- https://www.mak-1.com/news/marbella-town-hall-reaches-final-stages-for-the-definitive-approval-of-the-pgom
- https://www.maspropertymarbella.com/marbella-approves-new-regulation-to-tackle-abandoned-developments/
- https://www.facebook.com/RTVMarbella/posts/1564270939035001/
- https://www.facebook.com/abcdesevilla/posts/1321280383372853/
- https://www.agenciaandaluzadelaenergia.es/en/node/3063
- https://www.boe.es/buscar/act.php?id=BOE-A-2026-6544
- https://solar-master-malaga.com/en/solar-grants-andalucia/
- https://renewablesnow.com/news/spains-andalusia-region-adds-record-2-888-mw-of-renewables-in-2025-1290926/
- https://www.idealista.com/en/news/property-for-sale-in-spain/2025/10/03/862629-costa-del-sol-property-prices-reach-record-highs-in-2025
- https://www.idealista.com/en/news/property-for-sale-in-spain/2025/10/20/863042-malaga-house-prices-soar-to-eu3-620-m2-up-17-in-a-year
- https://investropa.com/blogs/news/malaga-good-time
- https://arevont.com/market-stats/new-build-vs-resale
