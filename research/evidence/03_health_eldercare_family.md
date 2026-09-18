# 03 — Health, Eldercare, Wellbeing, Pets & Family Services on the Costa del Sol
Research date: 18 September 2026. Geography: Málaga province (Málaga city, Torremolinos, Benalmádena, Fuengirola, Mijas, Marbella, Estepona, Nerja, Vélez-Málaga).

Method note: 45 distinct search queries were issued in English and Spanish (32 via WebSearch before the session budget was exhausted; 13 successful via Firecrawl, with ~20 further attempts refused by rate limiting). Direct page fetching (WebFetch/curl) was blocked by network policy for every domain tried, and the search tools hit budget/rate limits before all planned queries could run. Numbers below come from search-result summaries and snippets that cite a named source URL; where the number could not be traced to a page I could see, it is marked **unverified**. Nothing has been invented; gaps are stated as gaps.

---

## 1. DATA TABLE

| # | Metric | Value | Date | Geography | Source |
|---|--------|-------|------|-----------|--------|
| 1 | Average wait for a primary-care (GP) appointment | 8.7 days (only 19% of appointments within 48h; 48h standard missed in 80.7% of cases) | Mar 2026 | Málaga province | https://www.elespanol.com/malaga/vivir/salud/20260319/malaga-registra-espera-media-dias-cita-medico-cabecera-solo-dan-horas/1003744175435_0.html |
| 2 | Worst GP waits by basic health zone | Coín 12.8 days; Alhaurín el Grande 11.67; Rincón de la Victoria 11.66 | Mar 2026 | Málaga province | same as #1 |
| 3 | Patients unable to get a health-centre appointment when requested | 1 in 5; 21% no face-to-face slot, 32% no phone slot | Jun 2026 | Málaga | https://www.elespanol.com/malaga/vivir/salud/20260619/pacientes-no-consigue-cita-centro-salud-malaga-solicita/1003744292713_0.html |
| 4 | Health centres in Málaga-capital district with uncovered family-doctor absences | 13 of 26 | 2026 | Málaga city district | same as #3 |
| 5 | Average wait, first specialist consultation (public) | 136 days | 31 Dec 2025 (Ministry of Health data) | Andalucía | https://www.seguromedicoya.es/seguro-de-salud/malaga (cites Ministerio de Sanidad) — **secondary source, unverified against ministry table** |
| 6 | Average wait, non-urgent surgery (public) | 173 days | 31 Dec 2025 | Andalucía | same as #5 — **unverified** |
| 7 | Legal maximum surgical wait guarantee | 180 days for ~700 procedures; 120 days for the 11 most common processes; if breached patient may go private at SAS cost | current | Andalucía (SAS) | https://www.sspa.juntadeandalucia.es/servicioandaluzdesalud/ciudadania/derechos-y-garantias/tiempos-de-respuesta-asistencial-listas-de-espera |
| 8 | People waiting for dependency (Ley de Dependencia) in Málaga province | 8,600 (PSOE figure); alt. breakdown 6,900 pending assessment + 5,000 pending service | Sep 2026 | Málaga province | https://www.teleprensa.com/andalucia/malaga/psoe-exige-moreno-atender-8600-personas-que-esperan-dependencia-malaga-reforma-ley/202609171452312510174.html ; https://www.psoemalaga.es/actualidad/ver-nota-prensa/id/12061/... |
| 9 | Málaga ranking in dependency waiting list | Highest of all Andalusian provinces | 2026 | Málaga | PSOE Málaga (political source, treat as partisan) |
| 10 | Andalusians waiting for dependency recognition | ~20,000; average processing time 435 days | 30 Jun 2026 | Andalucía | https://www.sevillaactualidad.com/andalucia/596223-casi-20-000-andaluces-esperan-que-se-les-reconozca-la-dependencia-durante-una-media-de-435-dias/ |
| 11 | Andalucía total dependency waiting list (Observatorio Estatal) | 49,513 people (2nd largest in Spain after Cataluña 80,827) | Mar 2026 (XXVI Dictamen) | Andalucía | https://directoressociales.com/wp-content/uploads/2026/03/NdP-XXVI-Dictamen-13-03-26.pdf |
| 12 | Alternative figure: Andalucía waiting list | >54,000; 477 days processing delay (2nd worst in Spain) | 2026 | Andalucía | https://www.malagactualidad.es/teletipos/72183-... (PSOE denunciation) |
| 13 | People who died on the dependency waiting list, Andalucía | 6,995 in 2025; >800 in first months of 2026 | 2025/2026 | Andalucía | Observatorio Estatal Dependencia via https://www.lawandtrends.com/... and Sevilla Actualidad |
| 14 | People who died waiting, Spain | 32,704 in 2025 (one every 16 minutes); national avg resolution 341 days | 2025 | Spain | https://directoressociales.com/wp-content/uploads/2026/03/NdP-XXVI-Dictamen-13-03-26.pdf |
| 15 | "Limbo de la dependencia" (recognised but no service), Spain | 148,907 (2025) vs 142,446 (2024) | 2025 | Spain | same as #14 |
| 16 | National dependency waiting list growth | 265,503 people; +7,293 during 2026 | 2026 | Spain | https://www.lawandtrends.com/noticias/administrativo/la-lista-de-espera-de-la-dependencia-ya-se-situa-en-265-503-afectados... |
| 17 | Public home-help cap under dependency law | 94 hours/month max for "total loss of autonomy" (~3h/day) | Jun 2026 | Spain | Reuters via https://www.usnews.com/news/world/articles/2026-06-19/in-spain-elderly-uk-expats-struggle-for-care-post-brexit |
| 18 | Residential care places, Málaga province | 7,512 places for 294,907 people aged 65+ (≈2.5 per 100); 84% private | IMSERSO data (2020) reported 2023 | Málaga province | https://www.elespanol.com/malaga/vivir/salud/20231001/envejecer-malaga-plazas-residencias-mayores-publicas-estancan-privadas-disparan/797920566_0.html |
| 19 | Places added in Málaga since 2007 | 2,849, of which only 68 public | 2007–2020 | Málaga province | same as #18 |
| 20 | Residential ratio, Andalucía | ~3 places per 100 over-65s vs 5 recommended; 1,659,589 people 65+; deficit 36,327 places | 2024/25 | Andalucía | https://www.publico.es/sociedad/deficit-plazas-residencias-dispara-faltan-50-000.html ; https://directoressociales.com/wp-content/uploads/2026/01/NdP-residencias-2024.pdf |
| 21 | National residential place deficit vs 5% ratio | 96,916 (up from 53,103 in 2014); occupancy 82.4% | Jan 2026 | Spain | https://directoressociales.com/wp-content/uploads/2026/01/NdP-residencias-2024.pdf |
| 22 | Care-home closures Andalucía | 24 residencias closed 2019–2022 | 2023 report | Andalucía | https://www.eldiario.es/andalucia/falta-plazas-cierre-24-residencias-2022-informe-pide-junta-andalucia-plan-choque_1_13247431.html |
| 23 | Average private care-home price, Málaga | €2,324.27/month (IVA incl.); mid-range example Residencia Girasol €2,183; luxury >€3,000 | 2026 | Málaga | https://miresi.es/precios-residencias-ancianos/malaga/ ; https://residenciadeancianosmalaga.es/precios-residencias-ancianos-malaga/ |
| 24 | Number of care homes listed, Málaga province | 118 (miResi directory) | 2026 | Málaga province | https://miresi.es/residencias-ancianos/andalucia/malaga/ |
| 25 | Staff ratio in Málaga care homes | ~6 FTE employees per 10 residents | 2026 | Málaga | https://residenciasysalud.es/residencias-de-ancianos/malaga — **unverified** |
| 26 | Live-in carer (cuidadora interna) price | from €1,399/month (Edades); families set pay ≥ SMI (Cuidum) | 2026 | Málaga | https://edades.eu/malaga/ ; https://www.cuidum.com/interna-24h/malaga/ |
| 27 | Population aged 80+ Málaga province | 90,733 (vs 87,100 prior year, +~4%) | Nov 2025 padrón | Málaga province | https://www.elespanol.com/malaga/20251112/vecinos-anos-extranjeros-malaga-envejece-gana-diversidad-cultural/1003744008915_0.html |
| 28 | Foreign-nationality residents, Málaga province | 347,578 (+9,302 y/y) | Nov 2025 | Málaga province | same as #27 |
| 29 | Total population Málaga province | ~1.79–1.8 million | 2025 | Málaga province | https://www.elespanol.com/malaga/20250807/malaga-roza-millones-habitantes-crece-gracias-poblacion-extranjera/1003743878232_0.html |
| 30 | Foreign-born share of Málaga population | 23.25% (9th of Spanish provinces) | Apr 2024 | Málaga province | https://www.theolivepress.es/spain-news/2025/05/05/census-reveals-over-20-of-people-living-in-malaga-are-foreign/ |
| 31 | New residents that are foreign (10-yr) | 7 of 10; British the largest group of new arrivals, then Moroccans, Argentinians | 2025 | Málaga province | https://www.eyeonspain.com/blogs/a-view-from-the-mountains/23385/... |
| 32 | British registered (empadronados), Málaga province | 53,413 (Mijas 15%, Fuengirola 10%, Marbella 8%); other count 56,019 | 2025 (El Español) / padron.com.es | Málaga province | https://www.elespanol.com/malaga/20250310/extranjeros-viven-malaga-prefieren-hacerlo-costa-mayoria-britanicos/930157593_0.html ; https://padron.com.es/brit%C3%A1nicos-en-m%C3%A1laga/ |
| 33 | British by municipality (padrón 2022) | Mijas 8,610; Fuengirola 5,508; Benalmádena 3,420 | 2022 | municipalities | https://epa.com.es/padron/britanicos-en-malaga/ |
| 34 | Share of British residents in Málaga aged 55+ | 60% (CCOO report); British = 70% of non-EU Europeans | ~2023 | Málaga province | https://andalucia.ccoo.es/ff25bef2e57ed4203611e1ee0b2c7aa0000057.pdf |
| 35 | Share of British in Spain aged 65+ | ~21.5% (national); "about a third are pensioners" (Reuters) | 2025/26 | Spain | Olive Press / Reuters (see #17) |
| 36 | British resident population in Spain | ~266,000 (largest in EU) | Jun 2026 | Spain | Reuters via US News (#17) |
| 37 | Mijas foreign share | >35% of ~90,000 registered residents non-Spanish (British, Scandinavian, German majority) | 2024 | Mijas | https://euroweeklynews.com/2024/12/27/malaga-town-mostly-foreign-residents/ |
| 38 | Over-65s living alone, Spain | 36.8%; loneliness/isolation prevalence 20–40% | 2025/26 | Spain | https://pmc.ncbi.nlm.nih.gov/articles/PMC12555246/ |
| 39 | Health-insurance premium rises, individual renewals | +13% average in 2025; 10–20% real renewals; up to +30% for seniors | 2025/26 | Spain | https://www.65ymas.com/economia/seguros-salud-subidas-mayores-hasta-30-renovar-sus-polizas_78834_102.html ; https://www.polizamedica.es/seguros/salud/por-que-tu-seguro-medico-aumenta-de-precio |
| 40 | Medical inflation Spain 2026 | 8.4% (WTW Global Medical Trends 2026); corporate health policies +9% | 2026 | Spain | https://mediadoresseguros.madrid/los-seguros-de-salud-para-empresas-se-encareceran-un-9-en-2026-por-la-inflacion-medica/ |
| 41 | Health-insurance premium volume Q1 2026 | €3,629m (+7.3% y/y) | Q1 2026 | Spain | https://roams.es/actualidad/seguros/seguro-medico-sube-precio-recauda-mas-demanda-no-cede-3629-millones-primer-trimestre/ |
| 42 | Price jump at age 65 | +10% to +40% depending on insurer; seniors pay up to 3x | 2025 | Spain | https://solidaridadintergeneracional.es/wp/edadismo-en-los-seguros-de-salud-los-mayores-pagan-hasta-tres-veces-mas-solo-por-su-edad/ |
| 43 | Sanitas Health Plan Classic max entry age | 75 (surcharge from 76); Sanitas Único: no age limit, min age 60, no questionnaire | 2026 | Spain | https://www.sanitasexpat.com/... ; https://www.healthplanspain.com/sanitas/sanitas-health-plans/sanitas-unico.html |
| 44 | Entry-level premiums | Adeslas from €20/month; DKV visa-compliant from ~€50/month | 2026 | Spain | https://www.eleconomista.es/... ; https://healthinsuranceforspanishvisas.com/adeslas-vs-sanitas-vs-dkv/ |
| 45 | Private vs public diagnostic waits (anecdotal guide) | MRI 4 months public vs 4 days private; dermatology 6 months vs 1 week | 2026 | Málaga | https://www.letsgomalaga.com/relocation/malaga/healthcare/ — **unverified guide claim** |
| 46 | Therapy session price | €80–120/hour typical; premium for English | 2025/26 | Spain | https://myexpatmind.com/how-much-does-therapy-cost-in-spain-in-2025/ |
| 47 | Cudeca fundraising need | €125,000 to serve 211 more patients in 2025 (raised €100,312 by Feb 2025); Dec 2025 deadline to secure €268,000 for inpatient unit | 2025 | Benalmádena / Málaga province | https://www.cudeca.org/en/actualidad/extending_becudecaheart/ ; https://euroweeklynews.com/2025/12/29/cudeca-hospice-faces-deadline-to-secure-e268000-for-inpatient-care/ |
| 48 | Benalmádena council grant to Cudeca home care | €25,000 (2024) | 2024 | Benalmádena | https://www.cudeca.org/en/actualidad/benalmadena-grant-2025/ |
| 49 | Hospital de Alta Resolución Estepona planned capacity | 85,000 consultations, 91,000 emergencies, 4,000 surgeries/yr; €15m paid by town hall; >117,000 medical acts since opening | plan / 2025 | Estepona | https://ayuntamiento.estepona.es/noticia/12926-... ; https://ayuntamiento.estepona.es/noticia/17274-... |
| 50 | HAR Estepona actual operation | Observation unit locked; X-ray/bloods only 08–22h; serious cases transferred to Costa del Sol; Digestive endoscopy unit started Feb 2026 (87 endoscopies by 20 Mar) | 2025–2026 | Estepona | https://www.azcostadelsol.com/estepona/quirofanos-cerrados-urgencias-a-medio-gas-... ; https://esteponainfo.substack.com/p/estepona-hospital-anatomy-of-a-healthcare-infraetructure-in-coma |
| 51 | Costa del Sol Hospital protest | >300 people protested staff deficit; SATSE/USO denounce A&E collapse each winter | 2025/26 | Marbella | https://andalucia.satse.es/es/notas-prensa/-/v/735825/colapso-urgencias-marbella ; https://facuso.es/noticias/sanidad/... |
| 52 | EU cohesion funding for Marbella hospital expansion | €86 million | Aug 2023 | Marbella | https://ec.europa.eu/regional_policy/whats-new/newsroom/30-08-2023-eu-cohesion-policy-eur86-million-... |
| 53 | International schools, Málaga–Costa del Sol | 44 (International Schools Database); 29 (Micole) | Sep 2026 | Málaga province | https://www.international-schools-database.com/in/malaga-costa-del-sol ; https://www.micole.net/buscador/colegios-internacionales-malaga |
| 54 | International school fees | Primary €6,000–12,000/yr; Secondary €9,000–18,000; top IB sixth form >€18,000; extras €3,200–7,800 | Q1 2026 | Costa del Sol | https://www.ischooladvisor.com/articles/.../international-school-fees-marbella-costa-del-sol-2026 |
| 55 | Waiting-list practice | Apply 12–18 months ahead; Aloha College €2,000 non-refundable waiting-list fee + €3,000 deposit | 2026 | Marbella | same as #54 |
| 56 | Municipal nursery (0–3) places, Málaga city | 481 places across 4 municipal escuelas infantiles (e.g., "Colores de Málaga" 61 places) | Apr 2025 | Málaga city | https://www.malaga.eu/la-ciudad/instalaciones-y-espacios/detalle-de-la-instalacion/?id=234 |
| 57 | 0–3 gratuity | Ages 1 and 2 free in Junta and adhered centres from 2026; age 0 keeps bonus scheme | 2026 | Andalucía | https://www.juntadeandalucia.es/temas/estudiar/infantil/admision-primer-ciclo.html |
| 58 | Vet consultation prices | general €25–50 (avg €30–45); emergency exam €60–200; emergency surgery €600–3,000 | 2026 | Spain | https://petplan.es/en/real-cost-vet-spain-2026/ |
| 59 | UK→Spain pet move cost | Vet (chip, rabies, AHC) £150–300; AHC £100–200 per trip; total £500–2,000 | 2025/26 | UK/Spain | https://blog.advancemoves.com/... ; https://www.crystaltravel.co.uk/news/eu-pet-travel-rules-uk-costs-animal-health-certificate |
| 60 | Repatriation of remains Spain→UK | £2,700 (Madrid) – £4,800 (Canaries); Avalon repat burial plan €8,950; joint decesos cover ~€55–70/month for couple aged 69/71 | 2026 | Spain | https://comparafune.es/repatriation-cost-spain-to-uk/ ; https://avalonfuneralplans.com/... ; https://247expatinsurance.com/guides/funeral-insurance-spain-expat-guide/ |
| 61 | Luana Senior Living (Eurofund) | 129 apartments at El Paraíso, Estepona + Miraflores, Mijas site | 2025/26 launch | Estepona / Mijas | https://www.luanaseniorliving.com/en ; https://eurofundgroup.com/projects/luana-senior-living/ |
| 62 | Dependency law reform | Approved by Congress 16 Sep 2026; +€6,200m 2026–27; state funding to 50%; resolution deadline 6→3 months; ends service incompatibilities | Sep 2026 | Spain | https://www.dsca.gob.es/en/comunicacion/notas-prensa/congreso-aprueba-reforma-ley-discapacidad-refundacion-sistema-dependencia |

| 63 | People who died waiting for dependency, Andalucía, Jan–May 2026 | 2,204; Andalusian list growing while national list falls; avg resolution 446 days (>2x legal limit) | May 2026 | Andalucía | https://www.elplural.com/autonomias/andalucia/fallecen-2204-personas-andalucia-esperando-dependencia-primeros-cinco-meses-2026_392528102 |
| 64 | Dependency applicants, Málaga province (cumulative) | >77,000 people have applied; 441 died waiting (period unspecified) | 2026 | Málaga province | PSOE Málaga Facebook post https://www.facebook.com/psoe.malaga/posts/... — **partisan, unverified** |
| 65 | Junta-financed care-home place price | +4.5% rise retroactive to 1 Jan 2025; cumulative +26% (period unspecified); 544 new concerted places (Cádiz example) | 2025 | Andalucía | https://www.facebook.com/canalsierradecadiz/posts/... — **unverified secondary** |
| 66 | Cudeca patients served | >1,900 palliative patients in 2025 (incl. 25 paediatric); forecast 2,100 for 2025 (+10%); Torremolinos alone 125 patients/yr | 2025 | Málaga province | https://www.laopiniondemalaga.es/malaga/2026/04/10/cudeca-cuidados-paliativos-malaga-cancer-pediatricos-128953822.html ; https://www.malaga.es/delegacioncooperacion/1485/com1_md3_cd-51046/... |
| 67 | Bogaris Costa del Sol (WATG master plan) | 86-hectare integrated resort community with senior-living component, Estepona | planning | Estepona | https://www.watg.com/project/senior-living-at-bogaris-costa-del-sol/ |
| 68 | Santa Margarita Senior Living (La Línea, Cádiz, edge of Costa del Sol) | luxury seaside senior complex; crowdfunding bridge loan €2.4m at 10.5% (Letsinvest) | 2026 | La Línea | https://letsinvest.eu/project/178 |
| 69 | CBRE view on Spanish senior living | "Málaga and the Costa del Sol are the main development hubs"; market "yet to mature" | 2025/26 | Costa del Sol | https://www.cbre.es/en-gb/insights/articles/senior-living-oportunidad-estrategica-... |
| 70 | Press framing | "La Costa del Sol acelera su carrera para convertirse en referente europeo del senior living" | 5 Jun 2026 | Costa del Sol | https://www.eleconomista.es/vivienda-inmobiliario/noticias/13956809/06/26/... |
| 71 | Torremolinos population / foreign share | 71,329 (INE 2025); 27.38% foreign; 130 nationalities | 2025 | Torremolinos | https://es.wikipedia.org/wiki/Torremolinos |
| 72 | Nerja population | 22,132 (padrón 1 Jan 2025) | 2025 | Nerja | https://costadelsoloutdoors.com/es/cesped-artificial/nerja/ (cites INE) |
| 73 | Surgical waiting list, Hospital Regional + Clínico (Málaga city) | 35,189 patients; ~5,000 beyond legal deadline; rising vs six months earlier | Mar 2025 | Málaga city hospitals | https://cadenaser.com/andalucia/2025/03/12/lista-de-espera-en-malaga-sube-en-los-principales-hospitales-con-casi-5000-pacientes-fuera-de-plazo-ser-malaga/ |
| 74 | Specialist first-appointment list, Málaga province | ~200,000 patients waiting; 64–144 days depending on hospital | Jul 2024 | Málaga province | https://www.elespanol.com/malaga/20240710/lista-espera-especialistas-baja-malaga-pacientes-aguardan-cita/869163484_0.html |
| 75 | Longest first-consultation delay by hospital | Hospital Costa del Sol (Marbella) has the longest first-appointment delay in the province; Clínico has the longest list | Sep 2025 | Málaga province | https://www.laopiniondemalaga.es/malaga/2025/09/17/especialidades-medicas-mayor-tiempo-lista-espera-121639053.html |
| 76 | Hospital Costa del Sol trend | Outpatient list down, surgical list up | Sep 2025 | Marbella | https://cadenaser.com/andalucia/2025/09/16/baja-la-lista-de-espera-de-consultas-externas-en-el-hospital-de-marbella-mientras-sube-la-quirurgica-ser-marbella-costa-del-sol/ |
| 77 | Most-waited surgeries, Málaga | Cataracts, skin-lesion excision, knee arthroplasty | Apr 2024 | Málaga | https://www.malagahoy.es/malaga/Operaciones-mas-lista-espera-Malaga-cataratas-piel_0_1896111962.html |
| 78 | Mental-health waiting list | Málaga 5,129 patients (highest province); Andalucía 18,989 | Aug 2024 | Málaga / Andalucía | https://espacioandaluz.com/sociedad/malaga-es-la-provincia-andaluza-con-mas-pacientes-en-lista-de-espera-para-salud-mental-5-129/ |
| 79 | Teleasistencia (Junta) call-centre collapse, Málaga | up to 130 users queued simultaneously; ~20-minute waits for operator | Aug 2025 | Málaga | https://cadenaser.com/andalucia/2025/08/27/denuncian-el-colapso-en-malaga-de-la-teleasistencia-de-la-junta-hasta-130-usuarios-a-la-vez-que-esperan-20-minutos-para-ser-atendidos-ser-malaga/ |
| 80 | Teleasistencia software failures | "software que se cae a diario" (opinion piece) | Apr 2026 | Andalucía | https://www.elplural.com/opinion/moreno-bonilla-apaga-boton-rojo-abandono-mayores-caos-teleasistencia-andalucia_386066102 — **opinion** |
| 81 | Care costs quoted by Age in Spain | €1,500–€3,500+/month for care; "services and language availability vary" | 2025/26 | Spain | https://ageinspain.org/care-and-support-in-spain-guide/ |
| 82 | Care homes in Spain | >1,100 facilities; "specialist care such as advanced dementia harder to find" | 2026 | Spain | https://www.youroverseashome.com/spain/articles/spain-healthcare-options-for-retirees/ — **figure unverified** |
| 83 | Andalucía school admissions window | 1–31 March for 2026/27 (public/concertado) | 2026 | Andalucía | https://guides.waypointsur.com/school-admissions-spain/ |
| 84 | British over-65s in Spain (INE census) | ~121,000; number fell by ~2,500 (period per Instagram/EWN summary of INE census; exact years not visible) — more UK-born over-65s now leaving Spain than arriving | Aug 2026 | Spain | https://euroweeklynews.com/2026/08/04/older-britons-in-spain-face-a-painful-choice-as-the-retirement-dream-becomes-harder-to-live/ ; https://www.instagram.com/p/DbqtGGTiiJG/ — **secondary, unverified against INE table** |
| 85 | Convenio especial (pay-in to public health) | €157/month for over-65s; €60/month under 65 | 2026 | Spain | https://pccwealth.com/retire-to-spain-from-the-uk/ |
| 86 | English/international nursery fees | €500–900/month; evening babysitting €8–15/h (English-speaking sitters at the top of range) | 2026 | Costa del Sol | https://guides.waypointsur.com/childcare-nurseries-costa-del-sol/ |
| 87 | Nanny average rate | ~€11/hour; €810–1,920/month | 2026 | Spain | https://www.expatica.com/es/living/family/childcare-spain-101464/ |
| 88 | Age Concern branches on the coast | Age Concern Marbella & San Pedro; Age Concern Fuengirola-Mijas-Benalmádena (ageconcernfym.com); Age Concern Costa del Sol (worked with British Benevolent Fund on homeless 80-year-old case) | 2025/26 | Costa del Sol | https://ageconcernfym.com/ ; https://www.facebook.com/ageconcernmarbella/ ; https://www.instagram.com/p/DbqlTYnjPoD/ |
| 89 | The Patio Marbella (Estepona) capacity | Only 14 independent homes for couples 65+ (10 villas + 2-storey building); "exclusive" luxury CCRC-style | 2026 | Estepona | https://www.thepatiomarbella.com/es/ ; https://huetearquitectos.com/residencia-seniors-the-patio/ |
| 90 | Cocoon Senior Living Estepona (apartments for seniors) | Rated 3.5/5 from 23 reviews on miResi; price tier €€€€ | 2026 | Estepona | https://miresi.es/apartamentos-para-mayores/andalucia/malaga/malaga/vivienda-para-mayores-coccon-estepona/ |
| 91 | Senior apartments with services, Spain | €800–1,800/month typical | 2026 | Spain | https://mundomayor.com/informacion/apartamentos-senior |
| 92 | Luana Senior Living model | Rental 1–2 bedroom homes for retirees 65+ (not for sale) | 2026 | Estepona / Mijas | https://www.luanaseniorliving.com/es |
| 93 | Pet insurance entry price | Petplan from €23.17/month; €45 copay per claim; €3,100 annual limit | 2026 | Spain | https://selectra.es/seguros/aseguradoras/petplan |

---

## 2. PAIN POINTS

Frequency/intensity scale: High = appears in multiple independent 2025–26 sources with numbers; Medium = several sources, mostly qualitative; Low = single source or anecdotal.

### P1. Public health access delays (GP, specialist, surgery) — Frequency HIGH / Intensity HIGH
- "Málaga registra una espera media de 8,7 días para una cita con el médico de cabecera: solo el 19% se dan en 48 horas" — El Español, 19 Mar 2026. https://www.elespanol.com/malaga/vivir/salud/20260319/malaga-registra-espera-media-dias-cita-medico-cabecera-solo-dan-horas/1003744175435_0.html
- "Uno de cada cinco pacientes no consigue cita en un centro de salud de Málaga cuando la solicita… en 13 de los 26 centros de salud del distrito Málaga hay médicos de familia con ausencias" — El Español, 19 Jun 2026. https://www.elespanol.com/malaga/vivir/salud/20260619/pacientes-no-consigue-cita-centro-salud-malaga-solicita/1003744292713_0.html
- "Un total de 35.189 enfermos engrosan las esperas para una intervención en el Regional y el Clínico… casi 5.000 pacientes fuera de plazo" — Cadena SER, 12 Mar 2025. https://cadenaser.com/andalucia/2025/03/12/lista-de-espera-en-malaga-sube-en-los-principales-hospitales-con-casi-5000-pacientes-fuera-de-plazo-ser-malaga/
- "el Hospital Costa del Sol es el que tiene mayor demora para una primera [cita]" — La Opinión de Málaga, 17 Sep 2025. https://www.laopiniondemalaga.es/malaga/2025/09/17/especialidades-medicas-mayor-tiempo-lista-espera-121639053.html
- "A public MRI might take four months; a private one takes four days. A public dermatologist referral can take six months; privately… within a week." — LetsGoMalaga expat guide 2026 (unverified marketing claim). https://www.letsgomalaga.com/relocation/malaga/healthcare/

### P2. Western Costa del Sol hospital capacity (Marbella A&E collapse, Estepona HAR half-open) — Frequency HIGH / Intensity HIGH
- "Colapsadas las Urgencias del Hospital Costa del Sol… las ausencias del personal no se cubren… ratio enfermera-paciente ya excesivamente alta" — SATSE Andalucía. https://andalucia.satse.es/es/notas-prensa/-/v/735825/colapso-urgencias-marbella
- "Más de 300 personas se concentran en el Hospital Costa del Sol de Marbella por el déficit de personal" — SATSE. https://andalucia.satse.es/es/notas-prensa/-/v/735825/protesta-deficits-costa-sol
- "Los médicos del Hospital Costa del Sol denuncian continuas caídas informáticas que comprometen la asistencia sanitaria" — Telecinco, 23 Jun 2026. https://www.telecinco.es/noticias/andalucia/20260623/hospital-costa-sol-caidas-informaticas-comprometen-asistencia-sanitaria_18_019492072.html
- "La zona de observación de Urgencias está cerrada con candado… radiografías o analíticas solo entre las 8 y las 22 h; cualquier urgencia grave que llega a Estepona necesita ser trasladada al Hospital Costa del Sol" — AZ Costa del Sol on HAR Estepona. https://www.azcostadelsol.com/estepona/quirofanos-cerrados-urgencias-a-medio-gas-los-motivos-de-la-protesta-por-el-hospital-de-estepona/
- "Estepona Hospital: Anatomy of a healthcare infrastructure in a coma" — Estepona Info (Substack). https://esteponainfo.substack.com/p/estepona-hospital-anatomy-of-a-healthcare-infraetructure-in-coma

### P3. Dependency-law (Ley de Dependencia) backlog: care arrives too late or never — Frequency HIGH / Intensity VERY HIGH
- "8.600 personas que esperan la dependencia en Málaga" — Teleprensa/PSOE, 17 Sep 2026. https://www.teleprensa.com/andalucia/malaga/psoe-exige-moreno-atender-8600-personas-que-esperan-dependencia-malaga-reforma-ley/202609171452312510174.html
- "Fallecen 2.204 personas en Andalucía esperando la dependencia en los primeros cinco meses de 2026… el tiempo medio de resolución alcanza los 446 días, más del doble del límite legal" — El Plural. https://www.elplural.com/autonomias/andalucia/fallecen-2204-personas-andalucia-esperando-dependencia-primeros-cinco-meses-2026_392528102
- "Casi 20.000 andaluces esperan que se les reconozca la dependencia durante una media de 435 días" — Sevilla Actualidad, Jun 2026. https://www.sevillaactualidad.com/andalucia/596223-casi-20-000-andaluces-esperan-que-se-les-reconozca-la-dependencia-durante-una-media-de-435-dias/
- "Cada hora fallece en Andalucía una persona dependiente en lista de espera" — El Independiente de Granada. https://www.elindependientedegranada.es/politica/cada-hora-fallece-andalucia-persona-dependiente-lista-espera
- "#CCOOMálaga exige a la Junta un plan de choque para rescatar el sistema de dependencia en Andalucía" — CCOO Málaga (Instagram), 2026. https://www.instagram.com/p/DXHGxlNlq8l/
- Counterpoint (Junta): "Andalucía registra el menor tiempo de espera en dependencia de los últimos 15 años" — Junta de Andalucía Facebook. https://www.facebook.com/AndaluciaJunta/posts/... (partisan; numbers conflict with Observatorio data)

### P4. Care-home (residencia) shortage and cost — Frequency HIGH / Intensity HIGH
- "Málaga dispone de 7.512 plazas… a disposición de 294.907 mayores de sesenta y cinco años… el 84% privadas… Desde 2007 se han sumado 2.849 plazas, pero solo 68 pertenecen a la oferta pública" — El Español, Oct 2023. https://www.elespanol.com/malaga/vivir/salud/20231001/envejecer-malaga-plazas-residencias-mayores-publicas-estancan-privadas-disparan/797920566_0.html
- "Andalucía… solo 3 [plazas] por cada 100 ancianos… 36.327 plazas menos de las necesarias" — Público. https://www.publico.es/sociedad/deficit-plazas-residencias-dispara-faltan-50-000.html
- "Falta de plazas y cierre de 24 residencias entre 2019 y 2022: un informe pide a la Junta de Andalucía un 'plan de choque'" — elDiario.es. https://www.eldiario.es/andalucia/falta-plazas-cierre-24-residencias-2022-informe-pide-junta-andalucia-plan-choque_1_13247431.html
- "Una plaza en una residencia de ancianos en Málaga cuesta, de media, 2.324,27€ al mes" — miResi 2026. https://miresi.es/precios-residencias-ancianos/malaga/
- "El acceso a una plaza pública o concertada no es inmediato. Las listas de espera pueden ser largas" — A Cargo guide 2026. https://acargo.org/guias/residencia-mayores-quien-paga-cuanto-cuesta.html

### P5. Elderly foreign residents: no family nearby, post-Brexit 90-day rule blocks relatives from caring — Frequency HIGH / Intensity VERY HIGH (for the affected)
- "Daniel Northover left his home in Liverpool to move in with his 80-year-old mother in Turre… With non-EU residents only allowed to remain in the bloc for 90 days in every 180 without a visa… it had become unsustainable. Visas to care for a dependent family member are only available if it is the UK citizen needing the care." — Reuters, 19 Jun 2026. https://www.usnews.com/news/world/articles/2026-06-19/in-spain-elderly-uk-expats-struggle-for-care-post-brexit
- "Sally Myburgh, a British resident of Malaga who runs a Facebook group… said this is a recurring problem, and she regularly encounters families in Northover's situation." — Reuters, same article.
- "Returning to the UK is a daunting and unrealistic prospect for those who have spent decades in Spain and have no community or property to return to" — Neal Anderson, Help at Home Costa Blanca, Reuters.
- "The Spanish social care system provides home care… capped at 94 hours a month for those classified as suffering from a 'total loss of autonomy', about three hours a day." — Reuters.
- "Hi. My elderly aunt has lived in Spain for 50 years and is English…" / "I am looking for care and advise for my Brother who is English but has lived in Spain for about 20 years. He has suffered a bad Stroke…" / "Nursing homes in Spain for expats with English speakers?" / "Family care for elderly or ill parents in Spain after Brexit" — Brexpats in Spain Facebook group threads. https://www.facebook.com/groups/brexpatsinspain/posts/3144770035683984/
- "Isolation among British retirees on this coast is already well documented… Older neighbours need the same kindness we showed family this summer" — Euro Weekly News, 31 Aug 2026. https://euroweeklynews.com/2026/08/31/costa-del-sol-expat-steve-older-neighbours-need-the-same-kindness-we-showed-family-this-summer/
- "Older Britons in Spain face a painful choice as the retirement dream becomes harder to live… Official data show more UK-born over-65s are leaving Spain than arriving as heat, care and later-life planning face fresh scrutiny" — Euro Weekly News, 4 Aug 2026. https://euroweeklynews.com/2026/08/04/older-britons-in-spain-face-a-painful-choice-as-the-retirement-dream-becomes-harder-to-live/
- "Brits in Costa del Sol struggling with visa issues for elderly care" / "Which are the most proactive charities in Spain that support elderly expats…" — Brexpats in Spain group threads, 2026. https://www.facebook.com/groups/brexpatsinspain/posts/3393378777489774/
- "Costa del Sol Loneliness and Isolation means more people need more help… we are here to provide help to the over 50's English speaking community" — Marbella volunteer network via Costa News, Sep 2026. https://www.facebook.com/CostaNewsSpain/posts/...
- "Brexit has caused a care crisis for elderly Britons living in Spain" — Leeds for Europe post summarising press coverage, 2026. https://www.facebook.com/leedsforeurope/posts/...
- Academic: "For this population, returning or relocating near family has long been viewed as taboo, associated with failure, dependency… Brexit and COVID-19… prompting British retirees to consider return as a legitimate strategy" — Journal of Ethnic and Migration Studies, 2025 (Costa del Sol + Costa Brava ethnography). https://www.tandfonline.com/doi/abs/10.1080/1369183X.2025.2573761
- "Study finds Spaniards and expats face gaps in loneliness support" — Euro Weekly News, 27 Dec 2025. https://euroweeklynews.com/2025/12/27/study-finds-spaniards-and-expats-face-gaps-in-loneliness-support/

### P6. Private health insurance: steep age-related premium rises, entry caps at 75, exclusions — Frequency HIGH / Intensity HIGH
- "Seguros de salud: subidas a los mayores de hasta el 30% al renovar sus pólizas… las pólizas sanitarias han disparado sus tarifas un 13,1% en tan solo un año" — 65ymás. https://www.65ymas.com/economia/seguros-salud-subidas-mayores-hasta-30-renovar-sus-polizas_78834_102.html
- "Sablazo de mi seguro de salud por cumplir años" — 65ymás reader story. https://www.65ymas.com/economia/sablazo-mi-seguro-salud-por-cumplir-anos_79685_102.html
- "La cara B de los seguros de salud específicos para sénior: caros, con letra pequeña y exclusiones" — 65ymás. https://www.65ymas.com/economia/cara-seguros-salud-especificos-senior-caros-con-letra-pequena-exclusiones_79456_102.html
- "Los mayores pagan hasta tres veces más solo por su edad… límites de contratación, trabas y precios inasumibles" — Solidaridad Intergeneracional. https://solidaridadintergeneracional.es/wp/edadismo-en-los-seguros-de-salud-los-mayores-pagan-hasta-tres-veces-mas-solo-por-su-edad/
- "Que suban las pólizas por edad es discriminación" — Plataforma de Mayores y Pensionistas. https://www.pmp.org.es/actualidad/noticias/los-mayores-cargan-contra-los-seguros-medicos-que-suban-las-polizas-por-edad-es
- "Sanitas cuts off at 75 for standard full-coverage plans" / "Health Insurance in Spain for Over 75: Which Providers Still Accept You in 2026" — Coming to Spain. https://www.comingtospain.com/blog/best-health-insurance-in-spain-for-over
- Trustpilot (sanitas.es): complaints about "cancelled policies continuing to run with charges, and refusal to accept cancellation letters", app booking failures. https://www.trustpilot.com/review/sanitas.es

### P7. Teleassistance / remote monitoring failure for people living alone — Frequency MEDIUM / Intensity HIGH
- "Hasta 130 usuarios a la vez que esperan 20 minutos para ser atendidos" — Cadena SER Málaga, 27 Aug 2025. https://cadenaser.com/andalucia/2025/08/27/denuncian-el-colapso-en-malaga-de-la-teleasistencia-de-la-junta-...
- "un software que se cae a diario" — El Plural opinion, 5 Apr 2026. https://www.elplural.com/opinion/moreno-bonilla-apaga-boton-rojo-abandono-mayores-caos-teleasistencia-andalucia_386066102
- Context: 36.8% of Spanish over-65s live alone (PMC 2025). https://pmc.ncbi.nlm.nih.gov/articles/PMC12555246/

### P8. Palliative / end-of-life care relies on a charity that is chronically underfunded — Frequency MEDIUM / Intensity HIGH
- "Cudeca Hospice faces deadline to secure €268,000 for inpatient care" — Euro Weekly News, 29 Dec 2025. https://euroweeklynews.com/2025/12/29/cudeca-hospice-faces-deadline-to-secure-e268000-for-inpatient-care/
- "Cudeca prevé ofrecer cuidados paliativos a 2.100 enfermos en 2025, un 10% más, y hace un llamamiento solidario" — Diputación de Málaga / Europa Press. https://www.europapress.es/andalucia/malaga-00356/noticia-cudeca-preve-ofrecer-cuidados-paliativos-2100-enfermos-2025-10-mas-hace-llamamiento-solidario-malaga-20241106142451.html
- "Cudeca ofreció cuidados paliativos a más de 1.900 personas en Málaga en 2025" — La Opinión de Málaga, 10 Apr 2026. https://www.laopiniondemalaga.es/malaga/2026/04/10/cudeca-cuidados-paliativos-malaga-cancer-pediatricos-128953822.html

### P9. Funeral-plan scams and repatriation cost uncertainty — Frequency MEDIUM / Intensity HIGH
- "Expats who've lost thousands demand tighter regulation of Spain's funeral plan sector after collapse of Iberian" — Olive Press, 28 Mar 2025. https://www.theolivepress.es/spain-news/2025/03/28/expats-demand-urgent-regulation-of-the-funeral-plan-sector-in-spain-after-collapse-of-iberian/
- "Repatriation Cost Spain to UK 2026: £2,700–£4,800 by Region" — Comparafune. https://comparafune.es/repatriation-cost-spain-to-uk/

### P10. International school places and fees for relocating (tech / remote-work) families — Frequency HIGH / Intensity MEDIUM
- "Waiting lists are real, with the Marbella corridor in particular seeing high demand… applications recommended at least 12–18 months in advance… Aloha College's €2,000 waiting-list fee and €3,000 deposit" — ischooladvisor 2026. https://www.ischooladvisor.com/articles/schooling-and-school-choice/costs-and-fees-understanding-funding/international-school-fees-marbella-costa-del-sol-2026
- "Market insights Q1 2026: Marbella and Benahavís remain high-demand with waiting lists in popular year groups." — Del Sol Prime Homes. https://delsolprimehomes.com/en/blog/comparison-guide-best-schools-for-expat-families-in-costa-del-sol
- "Málaga's growing tech scene has increased demand for international school places, with Google, Vodafone, and dozens of tech companies opening offices" — Waypoint Sur guide 2026. https://guides.waypointsur.com/international-schools-malaga/
- "Miss this window [1–31 March] and you go to the back of the queue" — Waypoint Sur on public admissions. https://guides.waypointsur.com/school-admissions-spain/
- "Can I enroll my kid in school in Spain by September?" — recurring Facebook expat-group question. https://www.facebook.com/groups/957315298668782/posts/1543580400042266/

### P11. Mental health: long public waits, English-language therapy at a premium — Frequency MEDIUM / Intensity MEDIUM
- "Málaga, la provincia andaluza con más pacientes en lista de espera para salud mental, con 5.129" — Espacio Andaluz, Aug 2024. https://espacioandaluz.com/sociedad/malaga-es-la-provincia-andaluza-con-mas-pacientes-en-lista-de-espera-para-salud-mental-5-129/
- "Professional associations warn that this combination of long waits and limited sessions is pushing many residents, including expats, toward private care" — 247expatinsurance guide. https://247expatinsurance.com/guides/mental-health-support-spain-english-speaking-psicologos/
- "English-speaking psychologists… frequently charge a premium for sessions conducted in English" — My Expat Mind 2026. https://myexpatmind.com/how-much-does-therapy-cost-in-spain-in-2025/

### P12. Dementia care in English is scarce — Frequency MEDIUM / Intensity HIGH
- "specialist care for conditions such as advanced dementia can be harder to find" — Your Overseas Home 2026. https://www.youroverseashome.com/spain/articles/spain-healthcare-options-for-retirees/
- "British expat with dementia in Spain" — Alzheimer's Society (UK) forum thread. https://forum.alzheimers.org.uk/threads/british-expat-with-dementia-in-spain.83053/
- Dutch-language dementia home care already exists ("Dementiezorg Costa del Sol… in de eigen taal") — Miraflores Home Care. https://mirafloreshomecare.org/en/dementiezorg/

### P13. Pets: post-Brexit paperwork cost and vet-bill anxiety — Frequency MEDIUM / Intensity LOW-MEDIUM
- "An Animal Health Certificate… £100–£200 for each journey… most expats spend £500–£2,000 moving a pet to Spain" — Advance Moves / Crystal Travel 2025–26. https://www.crystaltravel.co.uk/news/eu-pet-travel-rules-uk-costs-animal-health-certificate
- "Emergency services range between 60 and 200€ just for the examination… An emergency surgery can cost between 600 and 3,000€" — Petplan Spain 2026. https://petplan.es/en/real-cost-vet-spain-2026/
- (No Costa-del-Sol-specific vet complaint data found — gap.)

### P14. Childcare for relocating families: English nurseries €500–900/month, sitters scarce — Frequency MEDIUM / Intensity LOW-MEDIUM
- "Nanny and babysitting rates in Costa del Sol?" / "Afternoon childcare needed in Teatinos, Malaga for 20-month-old" — recurring Facebook expat-group posts. https://www.facebook.com/groups/294388724750178/posts/2044326423089724/
- "International/English nurseries cost EUR 500–900/month. Evening babysitting rates… EUR 8–15/hour, with English-speaking sitters at the [top]" — Waypoint Sur 2026. https://guides.waypointsur.com/childcare-nurseries-costa-del-sol/
- "Childcare Costa Del Sol offers fast, reliable multilingual sitters, with a similar honest caveat around fee transparency" — Luxo Estates 2026. https://luxoestates.com/activities/nannies-babysitting-services-marbella-2026/

---

## 3. COMPETITOR LANDSCAPE

| Pain | Who serves it today | What was found about them (ratings / complaints / weaknesses) |
|------|--------------------|-------------------------------------------------------------|
| Public-system delays | SAS (Hospital Regional, Clínico, Costa del Sol Marbella, HAR Estepona, HAR Benalmádena; Distrito Costa del Sol primary care) | 8.7-day GP waits; 35k+ surgical list in Málaga city; Costa del Sol worst first-appointment delay; A&E "colapso" protests (SATSE/USO); Estepona HAR observation unit locked; IT outages June 2026. SAS guarantee lets patients go private at SAS cost after 120/180 days — a rarely-exploited lever. |
| Private hospitals | Quirónsalud Málaga & Marbella, Vithas Xanit Internacional (Benalmádena; 16-language international dept, 24/7), Vithas Málaga, HC Marbella International Hospital, Hospital Ochoa (Marbella), Helicópteros Sanitarios (Marbella; 30+ yrs home-GP membership, no age limit, 24/7) | English-speaking; commercial focus on medical tourism; pricing not found; membership prices for Helicópteros not published (must call). Position: strong for acute/elective care, weak for ongoing social care. Sources: https://www.quironsalud.com/marbella ; https://citmarbella.es/socios/hospital-vithas-xanit-internacional/ ; https://helicopterossanitarios.com/ |
| Health insurance | Sanitas (rated 9.3/10 by Selectra), Adeslas (9.1), DKV (8.8), ASISA, AXA; expat brokers: Health Plan Spain, Sanitas Estepona, sanitasexpat.com, C1 Brokers, 247expatinsurance | Entry cap 75 (Sanitas Classic), Sanitas Único (60+, no questionnaire) as fallback; renewal rises 10–30% for seniors; Trustpilot complaints on cancellations/app; brokers compete on English service, not on price. Sources: https://selectra.es/seguros/seguros-salud/mejor-seguro-medico ; https://www.trustpilot.com/review/sanitas.es |
| Home care (English-speaking) | Senior Home Care (seniorhomecare.es; Marbella–Torremolinos), Costa Angels (Marbella; 24h live-in, respite, palliative), British Care Services (Costa del Sol + Murcia), We Care for You (Costa), Your Care, Miraflores Home Care (Dutch/German-language, dementia), Spanish platforms Cuideo, Cuidum, Wayalia, Interdomicilio, Edades (live-in from €1,399/mo), Cronoshare marketplace | Fragmented, small, owner-operated; no public review data surfaced; Euro Weekly "10 best care services in Marbella" list (2022) shows no dominant brand. Public SAD (ayuda a domicilio) capped at 94h/month and gated by dependency assessment (435–446 days). Sources: https://seniorhomecare.es/ ; https://www.wegodoit.com/care-agency-costa-del-sol/ ; http://www.britishcareservices.com/ ; https://mirafloreshomecare.org/en/dementiezorg/ ; https://edades.eu/malaga/ |
| Care homes | 118 residencias listed for Málaga province (miResi); big groups present nationally (DomusVi, Vitalia, Orpea/Emeis, Ballesol, Amavir — presence on coast not verified in this research); directories miResi, Inforesidencias, Residencias y Salud, Un Lugar para Mamá, holaretire.com (English-speaking residences finder), EuropeanSeniorCare | Avg €2,324/mo private; 84% private; public places static (68 added since 2007); English-speaking specialist dementia units scarce; 24 closures 2019–22 in Andalucía. Sources: https://miresi.es/residencias-ancianos/andalucia/malaga/ ; https://holaretire.com/en/services/senior-residences |
| Senior living / retirement villages | The Patio Marbella (Estepona; only 14 homes, CCRC-style, luxury), Cocoon Senior Living Estepona (3.5/5, 23 reviews), Luana Senior Living (Eurofund; 129 apts El Paraíso Estepona + Miraflores Mijas), Bogaris Costa del Sol (WATG 86-ha Estepona master plan), Santa Margarita Senior Living (La Línea; crowdfunded), Sensara-type Dutch resorts (not verified on Costa del Sol); UK/US analogs absent | All new/launching; luxury-priced; none operating at scale yet; CBRE calls the market "yet to mature" with Málaga/Costa del Sol as the main hub. Sources: https://www.thepatiomarbella.com/ ; https://www.luanaseniorliving.com/en ; https://www.watg.com/project/senior-living-at-bogaris-costa-del-sol/ ; https://www.cbre.es/en-gb/insights/articles/senior-living-... |
| Palliative | Cudeca (Benalmádena hospice; >1,900 patients 2025; home teams in Torremolinos etc.); SAS palliative units | Charity dependent on campaigns (€125k, €268k appeals); demand +10%/yr. https://www.cudeca.org/ |
| Charity / welfare for older foreigners | Age in Spain (guides, helpline), Age Concern España (local branches), Help at Home Costa Blanca (analog), ADSI Alzheimer's charity shop Sabinillas, AFA (Alzheimer family assoc., English-speaking group), Facebook groups (Brexpats in Spain; Sally Myburgh's post-Brexit group) | Volunteer-run, patchy coverage; Reuters shows welfare officers overwhelmed. https://ageinspain.org/care-and-support-in-spain-guide/ |
| Teleassistance | Junta de Andalucía teleasistencia (via Agencia de Servicios Sociales y Dependencia); private alarms (Cruz Roja, Securitas Direct, Tunstall) | Public service: 130-user queues, 20-min waits, daily software failures (2025–26). |
| Mental health (English) | Private psychologists: Apricity Expat Therapy, My Expat Mind, Therapy in Barcelona (online), spainmadesimple directory | €80–120/session; premium for English; public list 5,129 in Málaga (2024). |
| Dentists | Chains (Vitaldent, Dentix legacy), expat clinics (Smile24h Marbella, Semedi Málaga, Clínica Dental Costa del Sol Fuengirola), dental-tourism platforms (Dental Departures) | FACUA history of chain collapses (Dental Line, Funnydent, iDental); dental tourism from UK "taking off" (EWN Nov 2025). https://euroweeklynews.com/2025/11/02/dental-tourism-taking-off-in-costa-del-sol-particularly-with-uk-patients/ |
| Funerals / repatriation | Avalon (FCA-regulated; €8,950 repat plan), Golden Leaves, Costa Funeral Plans, Costa Funeral Services, Comparafune, Funecon; Spanish seguro de decesos (Ocaso, Santa Lucía, Mapfre) | Iberian Funeral Plans collapse 2025 destroyed trust in unregulated plans. https://www.theolivepress.es/spain-news/2025/03/28/... |
| Pets | Vets: Hospital Veterinario Costa del Sol (Málaga), Vets plus Pets (Mijas Costa, founded 2023, English), Tu Veterinario en Casa (home visits); pet transport: Pet Taxi Express, BMC European, Advance Moves; Petplan Spain insurance | Prices €25–50 consult; no local complaint data found (gap). |
| International schools | 44 schools (ISDB) incl. Aloha College, Swans, EIC La Cala, British School of Málaga, Sotogrande International, Laude, Benalmádena International College, Sunny View, St Anthony's; ISP Schools group | Waiting lists in Marbella/Benahavís year groups; €2,000 waiting-list fee at Aloha; fees €6k–18k+. |
| Nurseries 0–3 | Junta escuelas infantiles (1–2 yr free from 2026), municipal (481 places Málaga city), private chains (Don Pablito), English nurseries | Admissions window 1–30 April; no waiting-list numbers found (gap). |
| Childcare / nannies | Costa del Sol Babysitting (vetted sitters, 24/7), Childcare Costa del Sol, Facebook groups, au-pair sites; English nurseries (€500–900/mo) | Fee opacity noted; informal market dominates; no regulated nanny agency brand. https://costadelsolbabysitting.com/ |
| Home doctor / concierge | Helicópteros Sanitarios (Marbella), private GP clinics, hospital international depts | Legacy brand 30+ yrs; pricing opaque. |

---

## 4. REGULATORY FACTS (with dates and sources)

1. **Ley de Dependencia reform approved by Congress, 16 Sep 2026** (pending BOE publication): maximum resolution period cut from 6 to 3 months; ends incompatibility between services (e.g., home help + day centre + cash benefit can be combined); recognises "cuidador principal" and flexibilises "cuidador no profesional" (must still be validated in the PIA); state financing to reach 50% of the system; extra €6,200m for regions 2026–27; expands home-based services. Copago unchanged. Sources: https://www.dsca.gob.es/en/comunicacion/notas-prensa/congreso-aprueba-reforma-ley-discapacidad-refundacion-sistema-dependencia ; https://www.elindependiente.com/sociedad/2026/09/17/esto-cambia-nueva-ley-dependencia-quien-tiene-derecho-cobrarla/ ; https://acargo.org/guias/reforma-ley-dependencia-2026-novedades.html ; https://www.cuidum.com/blog/reforma-de-la-ley-de-dependencia-cuidadores-2026/
2. **Public home-help cap**: dependency-law home care capped at 94 hours/month for Grade III ("total loss of autonomy") — Reuters, Jun 2026. Grade I/II get fewer hours. https://www.usnews.com/news/world/articles/2026-06-19/in-spain-elderly-uk-expats-struggle-for-care-post-brexit
3. **SAS response-time guarantees (Decreto 209/2001 & 96/2004, still in force)**: 180 days max for ~700 surgical procedures, 120 days for 11 common processes; 60 days for first specialist consultation and 30 days for diagnostic tests in the guaranteed list; if breached the patient may be treated privately at SAS expense. https://www.sspa.juntadeandalucia.es/servicioandaluzdesalud/ciudadania/derechos-y-garantias/tiempos-de-respuesta-asistencial-listas-de-espera ; https://www.juntadeandalucia.es/temas/salud/derechos/listas-espera.html
4. **Primary-care 48h standard**: Andalucía's quality criterion is a GP appointment within 48 hours; met in only 19.3% of Málaga cases (Mar 2026). https://www.elespanol.com/malaga/vivir/salud/20260319/...
5. **Insurance renewal self-regulation (UNESPA)**: insurers commit not to refuse renewal for policyholders over 65 or with serious illness who have been with the company 5+ years — but may raise premiums individually; entry age caps (e.g., 75 for Sanitas Classic) remain legal. https://www.65ymas.com/actualidad/seguros-salud-65-anos-puede-aseguradora-echarte-edad_46062_102.html
6. **Post-Brexit mobility**: UK nationals may stay 90 days in any 180 in the Schengen area; no visa exists for a UK relative to come and care for a dependent UK-citizen parent in Spain unless the relative themselves qualifies (Reuters). EU Entry/Exit System (EES) enforcement from late 2025 makes overstays traceable (general knowledge; not verified in this research).
7. **Pet travel**: since 1 Jan 2021 UK-issued pet passports invalid; Animal Health Certificate (AHC) needed within 10 days of travel, valid 4 months for onward EU travel; ISO microchip + rabies vaccine ≥21 days before. https://www.idealista.com/en/news/lifestyle-in-spain/2026/04/20/848628-moving-to-spain-with-pets-complete-guide-for-2026
8. **Andalucía 0–3 education**: from 2026 attention for 1- and 2-year-olds is free in Junta and adhered centres; age 0 keeps bonus scheme; application window 1–30 April. https://www.juntadeandalucia.es/temas/estudiar/infantil/admision-primer-ciclo.html ; https://fsieandalucia.es/noticias/ed-infantil-calendario-procedimiento-admision-26-27
9. **School admissions (public/concertado)**: Andalucía window 1–31 March for 2026/27; late applications lose priority. https://guides.waypointsur.com/school-admissions-spain/
10. **Care-home discipline regime**: BOJA 143 (27 Jul 2026) regulates disciplinary regime for users of publicly financed places in centres for older people. https://www.juntadeandalucia.es/boja/2026/143/36
11. **Junta concerted-place price**: +4.5% retroactive to 1 Jan 2025 (secondary source; unverified). 
12. **Funeral plans**: Spanish pre-paid funeral plans are not FCA-regulated; UK FCA regulation of funeral plans since July 2022 covers UK-based providers (Avalon, Golden Leaves) — Olive Press, Mar 2025. https://www.theolivepress.es/spain-news/2025/03/28/expats-demand-urgent-regulation-of-the-funeral-plan-sector-in-spain-after-collapse-of-iberian/
13. **Empadronamiento**: consulates repeatedly campaign for foreigners to register; official British counts (53–56k in Málaga) understate real residents. https://www.elespanol.com/malaga/20250310/extranjeros-viven-malaga-prefieren-hacerlo-costa-mayoria-britanicos/930157593_0.html
14. **Pharmacy home delivery**: Spanish law (Ley 29/2006 / RDL 1/2015, art. 2.5 and RD 870/2013) restricts dispensing of prescription medicines to the pharmacy premises; online sale is allowed only for non-prescription medicines via authorised pharmacy websites; home delivery must be done by the pharmacy itself to a specific patient (not by third-party marketplaces). **Not re-verified in this session (search budget exhausted) — treat as background knowledge to confirm.**

---

## 5. CANDIDATE OPPORTUNITIES

Market-size anchors used below (all from Section 1): Málaga province ≈1.8m people; ≈295k aged 65+ (2020 IMSERSO base; likely >320k by 2025 given 90,733 aged 80+ in Nov 2025); ≈53–56k registered British (60% aged 55+) plus other N-European retirees; 347,578 foreign nationals; 8,600 people in dependency limbo in Málaga; 7,512 care-home places (≈2.5 per 100 over-65s vs 5 recommended → ≈7,000-place structural gap); private residencia ≈€2,324/mo; live-in carer ≈€1,400–2,000/mo; 44 international schools with waiting lists; private specialist consult delays 64–144 days; health-insurance renewals +13%/yr.

### O1. English-first managed home-care agency ("Home Instead Costa del Sol")
- **Pain**: P3, P5, P12 — dependency care arrives after 435–446 days and is capped at 94h/month; elderly foreigners lack nearby family (90-day rule); English/Dutch/German-speaking carers are scarce; current agencies are tiny and fragmented.
- **Evidence strength**: STRONG (Reuters 2026, Observatorio data, Facebook demand threads, agency landscape).
- **Who pays**: self-funding retirees/families abroad (private pay, €18–28/h hourly; €2,000–3,200/mo live-in), UK adult children paying remotely; partial Junta cash benefits (prestación vinculada al servicio) once dependency is recognised — reform of Sep 2026 makes services combinable and speeds recognition to 3 months (on paper).
- **Market-size logic**: ~55k British + ~50k other N-European residents in Málaga province, ≥40% over 65 → ~40k foreign over-65s; at 10–15% needing regular paid help = 4–6k households; at €1,500/mo average spend → €70–110m/yr addressable in the foreign segment alone; Spanish market several times larger.
- **Existing players & how to outcompete**: Senior Home Care, Costa Angels, British Care Services, We Care for You, Miraflores Home Care (Dutch), Cuideo/Cuidum/Wayalia (Spanish platforms). None has scale, vetted-carer branding, nurse-led care plans, family app, or transparent pricing. Compete via franchise-grade systems (recruitment/DBS-equivalent vetting, CQC-style quality), bilingual care coordinators, remote family portal, integration with Helicópteros/private GPs, and help navigating the dependency application (turn 435-day wait into revenue).
- **Analog models**: Home Instead (UK/US franchise, 1,200+ offices), Helping Hands & Elder (UK live-in), Buurtzorg (NL nurse-led self-managed teams), Germany's 24-Stunden-Betreuung (Eastern European live-in via agencies), Japan's kaigo franchise operators.
- **Key risks**: carer recruitment in a low-unemployment tourist economy; labour law (domestic-worker regime vs company employment, 2022 reform); price sensitivity of pensioners; competition from informal cash market; liability.

### O2. English-speaking dementia & assisted-living units (bolt-on wings or a 40–60-bed specialist home)
- **Pain**: P4, P12 — 84% private places, ratio 2.5/100, no English-language dementia specialism; families forced to choose between Spanish-only homes or a traumatic return to the UK.
- **Evidence strength**: MEDIUM-STRONG (ratio data strong; English-language demand qualitative).
- **Who pays**: private pay (€2,500–4,000/mo), UK/NL/DE pensions and property equity; some Junta concerted places if licensed.
- **Market-size logic**: 7,000-place provincial gap; if 10% of new demand is English-preferring → 700 places; a 60-bed unit at €3,000/mo = €2.2m/yr revenue.
- **Existing players**: 118 residencias (Spanish-language); holaretire/EuropeanSeniorCare directories show scarcity of English-speaking homes. Outcompete via staff language, UK-style dementia design (Stirling DSDC), family video access, GP partnerships.
- **Analogs**: UK Care UK/Barchester dementia wings; Dutch Hogeweyk dementia village; Germany's Pflege-WG shared flats; Sensara Living (Dutch senior resort concept in Spain).
- **Risks**: capex and licensing (Junta accreditation, staff ratios ~0.6 FTE/resident), nursing recruitment, slow fill-up, currency/pension risk for UK residents.

### O3. Senior-living / "retirement village lite" operator or service layer for existing urbanisations
- **Pain**: P4, P5, P7 — loneliness, no care ladder between own home and residencia; new projects (Luana, The Patio, Bogaris) are luxury and years away.
- **Evidence strength**: MEDIUM (strong investor interest — CBRE, elEconomista Jun 2026 — but no operating data).
- **Who pays**: residents (service fee €300–800/mo on top of rent/purchase), developers (management contracts).
- **Market-size logic**: CBRE names Málaga/Costa del Sol Spain's main senior-living hub; Luana 129 units + Bogaris 86 ha pipeline; thousands of existing expat urbanisations in Mijas/Benalmádena/Estepona with 60%+ over-60 occupants could host a "virtual retirement village" (concierge, nurse visits, transport, activities, emergency response).
- **Existing players**: Luana (Eurofund), The Patio Marbella, Santa Margarita (La Línea). Outcompete by asset-light service layer rather than new build; partner with community administrators (administradores de fincas).
- **Analogs**: US The Villages & CCRCs, UK McCarthy Stone / Audley retirement villages, "Village-to-Village" naturally-occurring retirement communities (NORC) in the US, Dutch Knarrenhof, Japan's CCRC push.
- **Risks**: Spanish horizontal-property law limits communal services; residents' unwillingness to pay recurring fees; developer dependence.

### O4. "Care-navigator" + dependency/health advocacy service for foreigners (subscription)
- **Pain**: P1, P3, P5, P6 — 435-day dependency process, SAS guarantee rights unknown, insurance renewals at 75, empadronamiento, family abroad; Sally Myburgh-style Facebook groups do this for free and are overwhelmed.
- **Evidence strength**: STRONG on pain; MEDIUM on willingness to pay.
- **Who pays**: families (UK adult children) €50–150/mo or per-case fees €300–900; insurers/hospitals as referral channel.
- **Market-size logic**: 8,600 people waiting in Málaga + 200k on specialist lists; if 3,000 foreign households/yr buy a €600 case package → €1.8m; recurring "guardian" subscription for 5k households at €80/mo → €4.8m/yr.
- **Existing players**: Age in Spain (charity), gestorías, relocation firms, hospital international desks — none combine clinical + administrative advocacy. Compete via bilingual nurses + social workers, SLA-based tracking, exploiting the SAS 120/180-day guarantee to get private surgery at SAS expense.
- **Analogs**: US patient-advocate / geriatric care managers (Aging Life Care Association), UK "care concierge" services (e.g., Lottie, Elder), Germany's Pflegeberatung (statutory care advisors), Japan's care managers (kea maneja) under LTCI.
- **Risks**: charities offering free help; regulatory grey zone (not legal/medical advice); customer acquisition cost.

### O5. Private 24/7 telecare + falls/loneliness monitoring for expats living alone
- **Pain**: P7, P5 — Junta teleasistencia queues of 130 users/20-min waits, daily software crashes; 36.8% of over-65s live alone; family abroad.
- **Evidence strength**: MEDIUM-STRONG.
- **Who pays**: users €25–45/mo; adult children; insurers as add-on.
- **Market-size logic**: ~40k foreign over-65s + Spanish market; 15% take-up = 6k subscribers × €35 × 12 = €2.5m/yr; upsell to O1 visits.
- **Existing players**: Junta service (free/low-cost but failing), Cruz Roja, Securitas Direct, Tunstall (Spain), Helicópteros Sanitarios (medical response). Compete on English-language response centre, GPS/wearable, integration with home-care and GP, family app.
- **Analogs**: UK Taking Care/Careline365, US Lively/Life Alert, Netherlands' Zorgcentrale, Japan's Secom/ALSOK senior watch.
- **Risks**: thin margins; competition from free public service after reform funding; device logistics.

### O6. Fixed-fee membership primary care & "GP at home" for over-60s (with insurance-gap cover)
- **Pain**: P1, P6 — 8.7-day GP waits; insurers refuse or reprice at 65–75; Helicópteros is the only legacy home-GP membership and its pricing is opaque.
- **Evidence strength**: STRONG on pain; MEDIUM on model.
- **Who pays**: members €60–120/mo (individual), families.
- **Market-size logic**: 40k foreign over-65s + affluent Spanish; 5% penetration = 2,000 members × €90 × 12 = €2.2m; Helicópteros has run for 30+ years on this model.
- **Existing players**: Helicópteros Sanitarios, hospital international departments, Sanitas Único (no-questionnaire product). Compete via transparent pricing, chronic-disease nursing, English GP telemedicine, pharmacy coordination, negotiated diagnostics with Vithas/Quirón.
- **Analogs**: US direct-primary-care (DPC) and One Medical; UK Babylon/GP-at-Hand and private GP memberships; Germany's Hausarzt-Modell.
- **Risks**: doctor recruitment (SAS shortages), regulatory need for medical-centre licence, adverse selection.

### O7. International-school placement & "arrival-year" education concierge (plus English tutoring/after-school)
- **Pain**: P10 — 44 schools, waiting lists 12–18 months, €2,000 waiting-list fees, March/April public windows; tech-company inflow (Google, Vodafone).
- **Evidence strength**: MEDIUM (waiting-list claims come from property/advisor sites; no official numbers).
- **Who pays**: relocating families (€500–2,000 packages), employers (Google, Vodafone, TDK, Dekra, etc.) as relocation benefit, schools (placement commissions), tutoring €25–45/h.
- **Market-size logic**: Málaga adds ~9,300 foreign nationals/yr; if 1,500 families/yr with school-age kids and 20% buy a €1,000 package → €300k + tutoring/aftercare recurring; B2B contracts with 20 tech employers.
- **Existing players**: ischooladvisor, Malaga Schools, property agents (free lead-gen guides), relocation firms (LA Relocation Group). Compete via verified live seat availability, application-window alerts, bridging tuition (Spanish for kids), after-school English/IB tutoring hubs.
- **Analogs**: UK school placement consultants (Gabbitas), Singapore/Hong Kong relocation education consultants, US Bright Horizons back-up care.
- **Risks**: low-ticket, seasonal, schools may disintermediate; dependent on tech-hiring cycles.

### O8. FCA-style regulated funeral/repatriation planning + end-of-life admin for foreigners
- **Pain**: P9 — Iberian collapse 2025; repatriation £2,700–4,800; probate/certificates complexity.
- **Evidence strength**: MEDIUM.
- **Who pays**: individuals (plans €3,000–9,000; decesos insurance €55–70/mo couple).
- **Market-size logic**: ~2–3% annual mortality among 40k foreign over-65s ≈ 800–1,200 deaths/yr in the province; at €4,000 average → €3–5m/yr in funeral/repatriation spend.
- **Existing players**: Avalon, Golden Leaves (FCA-regulated), Costa Funeral Plans/Services, Comparafune, Spanish insurers. Compete via trust (escrow/insurance-backed), bilingual bereavement admin (NIE, wills, bank closures), transparency; or build the comparison/broker layer.
- **Analogs**: UK Co-op Funeralcare plans (FCA), Dignity; Dutch DELA cooperative model.
- **Risks**: reputational after scams; low differentiation; capital-adequacy rules if selling plans.

### O9. English-language dementia day centre + respite (asset-light, in existing venues)
- **Pain**: P12, P5 — spouses caring alone; Spanish day centres (centros de día) not language-accessible; AFA/ADSI charities small.
- **Evidence strength**: MEDIUM (qualitative).
- **Who pays**: families €40–70/day; Junta concerted day-centre places after dependency recognition (reform allows combining with home help).
- **Market-size logic**: dementia prevalence ~7% of over-65s → ~2,800 foreign over-65s with dementia in the province; 15% using day care 3 days/wk at €55 → €3.6m/yr.
- **Existing players**: municipal/Junta centros de día, AFA groups, Cudeca (palliative only). Compete via language, transport, carer training, evening/weekend respite.
- **Analogs**: UK Alzheimer's Society dementia cafés + private day centres; Dutch Odensehuis; Japan's day-service (tsūsho kaigo) under LTCI.
- **Risks**: licensing as centro de día; small ticket; needs O1 for transport/care continuity.

### O10. Multilingual mental-health & wellbeing telehealth for expats (60+ and relocating families)
- **Pain**: P11, P5 — 5,129 on Málaga's mental-health list (2024); English premium; loneliness/isolation.
- **Evidence strength**: MEDIUM.
- **Who pays**: clients €60–100/session; employers (EAP for tech relocators); insurers (Sanitas/DKV include limited psychology sessions).
- **Market-size logic**: 350k foreign residents; 3% annual use × 8 sessions × €70 = €5.9m/yr provincial spend (order of magnitude).
- **Existing players**: solo therapists, Apricity, My Expat Mind, Therapy in Barcelona. Compete via bilingual clinical governance, insurer contracts, group programmes (bereavement, retirement transition), employer EAPs.
- **Analogs**: UK Unmind/Spill, US Talkspace/BetterHelp, Germany's DiGA-approved apps.
- **Risks**: heavy competition from global platforms; psychology licensing across borders; price pressure.

Lower-priority ideas noted but weaker evidence: pet relocation/pet-sitting concierge (P13, low intensity), physio/rehab at home (no local data found), mobility-aid rental (no data), pharmacy delivery (legally constrained), medical-tourism aggregation (already served by hospital groups).

---

## 6. SOURCE LIST

### Public health / waiting lists
- https://www.elespanol.com/malaga/vivir/salud/20260319/malaga-registra-espera-media-dias-cita-medico-cabecera-solo-dan-horas/1003744175435_0.html (El Español, 19 Mar 2026)
- https://www.elespanol.com/malaga/vivir/salud/20260619/pacientes-no-consigue-cita-centro-salud-malaga-solicita/1003744292713_0.html (El Español, 19 Jun 2026)
- https://www.elespanol.com/malaga/vivir/salud/20240507/odisea-pedir-cita-medica-malaga-semana-espera-ir-manera-presencial/853165176_0.html
- https://iuandalucia.org/con-malaga-alerta-del-colapso-de-la-atencion-primaria-y-exige-citas-medicas-en-un-maximo-de-48-horas/
- https://cadenaser.com/andalucia/2025/03/12/lista-de-espera-en-malaga-sube-en-los-principales-hospitales-con-casi-5000-pacientes-fuera-de-plazo-ser-malaga/
- https://www.laopiniondemalaga.es/malaga/2025/09/17/especialidades-medicas-mayor-tiempo-lista-espera-121639053.html
- https://cadenaser.com/andalucia/2025/09/16/baja-la-lista-de-espera-de-consultas-externas-en-el-hospital-de-marbella-mientras-sube-la-quirurgica-ser-marbella-costa-del-sol/
- https://www.elespanol.com/malaga/20240710/lista-espera-especialistas-baja-malaga-pacientes-aguardan-cita/869163484_0.html
- https://www.malagahoy.es/malaga/Operaciones-mas-lista-espera-Malaga-cataratas-piel_0_1896111962.html
- https://espacioandaluz.com/sociedad/malaga-es-la-provincia-andaluza-con-mas-pacientes-en-lista-de-espera-para-salud-mental-5-129/
- https://www.sspa.juntadeandalucia.es/servicioandaluzdesalud/ciudadania/derechos-y-garantias/tiempos-de-respuesta-asistencial-listas-de-espera
- https://www.juntadeandalucia.es/temas/salud/derechos/listas-espera.html
- https://www.seguromedicoya.es/seguro-de-salud/malaga (secondary: Andalucía 136/173 days, Dec 2025)
- https://andalucia.satse.es/es/notas-prensa/-/v/735825/colapso-urgencias-marbella
- https://andalucia.satse.es/es/notas-prensa/-/v/735825/protesta-deficits-costa-sol
- https://facuso.es/noticias/sanidad/sanidad-autonomica/uso-sanidad-andalucia-denuncia-el-colapso-en-el-servicio-de-urgencias-del-hospital-costa-del-sol-en-marbella/
- https://www.telecinco.es/noticias/andalucia/20260623/hospital-costa-sol-caidas-informaticas-comprometen-asistencia-sanitaria_18_019492072.html
- https://www.azcostadelsol.com/estepona/quirofanos-cerrados-urgencias-a-medio-gas-los-motivos-de-la-protesta-por-el-hospital-de-estepona/
- https://esteponainfo.substack.com/p/estepona-hospital-anatomy-of-a-healthcare-infraetructure-in-coma
- https://esteponainfo.substack.com/p/estepona-hospital-to-activate-80-per-cent-services
- https://ayuntamiento.estepona.es/noticia/12926-el-hospital-de-alta-resolucion-de-estepona-atendera-85-000-consultas-91-000-urgencias-y-4-000-intervenciones-quirurgicas-al-ano
- https://ayuntamiento.estepona.es/noticia/17274-el-alcalde-valora-que-el-hospital-de-alta-resolucion-de-estepona-haya-registrado-mas-de-117-000-actos-medicos-desde-su-apertura-
- https://ec.europa.eu/regional_policy/whats-new/newsroom/30-08-2023-eu-cohesion-policy-eur86-million-for-the-expansion-and-upgrade-of-the-marbella-public-hospital_en
- https://guides.waypointsur.com/hospital-costa-del-sol/
- https://www.letsgomalaga.com/relocation/malaga/healthcare/
- https://guides.waypointsur.com/healthcare-in-malaga/

### Dependency / eldercare / care homes
- https://www.teleprensa.com/andalucia/malaga/psoe-exige-moreno-atender-8600-personas-que-esperan-dependencia-malaga-reforma-ley/202609171452312510174.html
- https://www.psoemalaga.es/actualidad/ver-nota-prensa/id/12061/titular/el-psoe-denuncia-que-malaga-es-la-provincia-con-mayor-lista-de-espera-en-dependencia-de-toda-andalucia.html
- https://www.sevillaactualidad.com/andalucia/596223-casi-20-000-andaluces-esperan-que-se-les-reconozca-la-dependencia-durante-una-media-de-435-dias/
- https://www.elplural.com/autonomias/andalucia/fallecen-2204-personas-andalucia-esperando-dependencia-primeros-cinco-meses-2026_392528102
- https://directoressociales.com/wp-content/uploads/2026/03/NdP-XXVI-Dictamen-13-03-26.pdf (Observatorio Estatal de la Dependencia, XXVI Dictamen)
- https://directoressociales.com/wp-content/uploads/2026/04/Informe-Observatorio-Estatal-Dependencia-10-04-26.pdf
- https://www.lawandtrends.com/noticias/administrativo/la-lista-de-espera-de-la-dependencia-ya-se-situa-en-265-503-afectados-al-crecer-en-7-293-personas-a-lo-largo-de-este-1.html
- https://andaluciainforma.eldiario.es/prestaciones/la-atencion-a-la-dependencia-crece-en-andalucia-pero-las-listas-de-espera-frenan-el-triunfalismo-de-la-junta/
- https://www.elindependientedegranada.es/politica/cada-hora-fallece-andalucia-persona-dependiente-lista-espera
- https://www.canalsur.es/noticias/andalucia/montero-marca-prioridad-recuperar-liderazgo_1_1394914.html
- https://www.juntadeandalucia.es/organismos/inclusionsocialjuventudfamiliaseigualdad/servicios/actualidad/noticias/detalle/649852.html
- https://directoressociales.com/wp-content/uploads/2026/01/NdP-residencias-2024.pdf
- https://www.publico.es/sociedad/deficit-plazas-residencias-dispara-faltan-50-000.html
- https://www.elespanol.com/malaga/vivir/salud/20231001/envejecer-malaga-plazas-residencias-mayores-publicas-estancan-privadas-disparan/797920566_0.html
- https://www.eldiario.es/andalucia/falta-plazas-cierre-24-residencias-2022-informe-pide-junta-andalucia-plan-choque_1_13247431.html
- https://miresi.es/precios-residencias-ancianos/malaga/ ; https://miresi.es/residencias-ancianos/andalucia/malaga/
- https://residenciadeancianosmalaga.es/precios-residencias-ancianos-malaga/
- https://residenciasysalud.es/residencias-de-ancianos/malaga
- https://acargo.org/guias/residencia-mayores-quien-paga-cuanto-cuesta.html
- https://www.juntadeandalucia.es/boja/2026/143/36
- https://cadenaser.com/andalucia/2025/08/27/denuncian-el-colapso-en-malaga-de-la-teleasistencia-de-la-junta-hasta-130-usuarios-a-la-vez-que-esperan-20-minutos-para-ser-atendidos-ser-malaga/
- https://www.elplural.com/opinion/moreno-bonilla-apaga-boton-rojo-abandono-mayores-caos-teleasistencia-andalucia_386066102
- https://www.dsca.gob.es/en/comunicacion/notas-prensa/congreso-aprueba-reforma-ley-discapacidad-refundacion-sistema-dependencia
- https://www.elindependiente.com/sociedad/2026/09/17/esto-cambia-nueva-ley-dependencia-quien-tiene-derecho-cobrarla/
- https://www.que.es/2026/09/17/reforma-ley-dependencia-congreso/
- https://acargo.org/guias/reforma-ley-dependencia-2026-novedades.html
- https://www.cuidum.com/blog/reforma-de-la-ley-de-dependencia-cuidadores-2026/

### Home care providers
- https://seniorhomecare.es/ ; https://seniorhomecare.es/senior-home-care-services/
- https://www.wegodoit.com/care-agency-costa-del-sol/ (Costa Angels)
- http://www.britishcareservices.com/
- https://www.spainmadesimple.com/costa-del-sol/care-agencies-nursing-carers/
- https://euroweeklynews.com/2022/10/19/an-all-important-guide-to-the-10-best-care-services-in-marbella/
- https://mirafloreshomecare.org/en/dementiezorg/
- https://edades.eu/malaga/ ; https://www.cuidum.com/interna-24h/malaga/ ; https://wayalia.es/cuidadora-interna-malaga/ ; https://www.interdomicilio.com/cuidadoras-internas-malaga/ ; https://cuideo.com/cuidado-personas-mayores-malaga/ ; https://www.cronoshare.com/cuanto-cuesta/ayuda-a-domicilio
- https://ageinspain.org/care-and-support-in-spain-guide/
- https://holaretire.com/en/services/senior-residences
- https://europeanseniorcare.com/countries/spain
- https://www.angloinfo.com/costa-del-sol/directory/costa-del-sol-nursing-retirement-homes-548

### Expat ageing / Brexit / loneliness
- https://www.usnews.com/news/world/articles/2026-06-19/in-spain-elderly-uk-expats-struggle-for-care-post-brexit (Reuters, 19 Jun 2026)
- https://www.facebook.com/groups/brexpatsinspain/posts/3144770035683984/
- https://www.tandfonline.com/doi/abs/10.1080/1369183X.2025.2573761
- https://euroweeklynews.com/2026/08/31/costa-del-sol-expat-steve-older-neighbours-need-the-same-kindness-we-showed-family-this-summer/
- https://euroweeklynews.com/2025/12/27/study-finds-spaniards-and-expats-face-gaps-in-loneliness-support/
- https://pmc.ncbi.nlm.nih.gov/articles/PMC12555246/
- https://forum.alzheimers.org.uk/threads/british-expat-with-dementia-in-spain.83053/
- https://www.theolivepress.es/spain-news/2019/03/12/were-here-british-expats-on-costa-del-sol-re-launch-alzheimers-and-dementia-support-charity-shop/
- https://euroweeklynews.com/2020/02/25/support-groups-for-alzheimers-and-dementia-on-spains-costa-del-sol/
- https://www.youroverseashome.com/spain/articles/spain-healthcare-options-for-retirees/

### Demographics
- https://www.elespanol.com/malaga/20251112/vecinos-anos-extranjeros-malaga-envejece-gana-diversidad-cultural/1003744008915_0.html
- https://www.elespanol.com/malaga/20250807/malaga-roza-millones-habitantes-crece-gracias-poblacion-extranjera/1003743878232_0.html
- https://www.elespanol.com/malaga/20250213/fuerte-llegada-extranjeros-permite-malaga-rozar-habitantes/923907765_0.html
- https://www.elespanol.com/malaga/20250310/extranjeros-viven-malaga-prefieren-hacerlo-costa-mayoria-britanicos/930157593_0.html
- https://andalucia.ccoo.es/ff25bef2e57ed4203611e1ee0b2c7aa0000057.pdf
- https://epa.com.es/padron/britanicos-en-malaga/ ; https://padron.com.es/brit%C3%A1nicos-en-m%C3%A1laga/
- https://www.theolivepress.es/spain-news/2025/05/05/census-reveals-over-20-of-people-living-in-malaga-are-foreign/
- https://www.eyeonspain.com/blogs/a-view-from-the-mountains/23385/seven-out-of-ten-new-residents-in-malaga-province-are-foreigners.aspx
- https://euroweeklynews.com/2024/12/27/malaga-town-mostly-foreign-residents/
- https://observatoriosocial.malaga.eu/export/sites/omis/.galleries/Datos-sociodemograficos-mayores/Datos-sociodemograficos-de-las-personas-mayores-en-Malaga-2022.pdf
- https://es.wikipedia.org/wiki/Torremolinos

### Insurance
- https://www.65ymas.com/economia/seguros-salud-subidas-mayores-hasta-30-renovar-sus-polizas_78834_102.html
- https://www.65ymas.com/economia/sablazo-mi-seguro-salud-por-cumplir-anos_79685_102.html
- https://www.65ymas.com/economia/cara-seguros-salud-especificos-senior-caros-con-letra-pequena-exclusiones_79456_102.html
- https://www.65ymas.com/actualidad/seguros-salud-65-anos-puede-aseguradora-echarte-edad_46062_102.html
- https://solidaridadintergeneracional.es/wp/edadismo-en-los-seguros-de-salud-los-mayores-pagan-hasta-tres-veces-mas-solo-por-su-edad/
- https://www.pmp.org.es/actualidad/noticias/los-mayores-cargan-contra-los-seguros-medicos-que-suban-las-polizas-por-edad-es
- https://www.polizamedica.es/seguros/salud/por-que-tu-seguro-medico-aumenta-de-precio
- https://roams.es/actualidad/seguros/seguro-medico-sube-precio-recauda-mas-demanda-no-cede-3629-millones-primer-trimestre/
- https://mediadoresseguros.madrid/los-seguros-de-salud-para-empresas-se-encareceran-un-9-en-2026-por-la-inflacion-medica/
- https://dkv.es/corporativo/blog-360/seguros-faciles/cuanto-cuesta-un-seguro-de-salud-los-precios-de-2026
- https://selectra.es/seguros/seguros-salud/mejor-seguro-medico
- https://www.comingtospain.com/blog/best-health-insurance-in-spain-for-over
- https://www.healthplanspain.com/sanitas/sanitas-health-plans/sanitas-unico.html
- https://www.sanitasexpat.com/sanitas-health-insurance-for-expats/sanitas-health-plan-classic-conditions/
- https://www.trustpilot.com/review/sanitas.es
- https://healthinsuranceforspanishvisas.com/adeslas-vs-sanitas-vs-dkv/

### Private providers / home doctor / palliative / mental health / dental / funeral / pets
- https://helicopterossanitarios.com/ ; https://www.spainlifeexclusive.com/your-health-covered-inside-the-helicopteros-sanitarios-membership/
- https://citmarbella.es/socios/hospital-vithas-xanit-internacional/ ; https://www.quironsalud.com/marbella/es/centro/atencion-paciente-internacional-quironsalud ; https://www.panoramamarbella.com/news/hospitals-in-marbella
- https://www.laopiniondemalaga.es/malaga/2026/04/10/cudeca-cuidados-paliativos-malaga-cancer-pediatricos-128953822.html
- https://www.europapress.es/andalucia/malaga-00356/noticia-cudeca-preve-ofrecer-cuidados-paliativos-2100-enfermos-2025-10-mas-hace-llamamiento-solidario-malaga-20241106142451.html
- https://euroweeklynews.com/2025/12/29/cudeca-hospice-faces-deadline-to-secure-e268000-for-inpatient-care/
- https://www.cudeca.org/en/actualidad/extending_becudecaheart/ ; https://www.cudeca.org/en/actualidad/benalmadena-grant-2025/
- https://www.afandaluzas.org/fundacion-cudeca-presenta-sus-resultados-anuales-2025-...
- https://myexpatmind.com/how-much-does-therapy-cost-in-spain-in-2025/ ; https://247expatinsurance.com/guides/mental-health-support-spain-english-speaking-psicologos/ ; https://www.spainmadesimple.com/costa-del-sol/psychiatrists-psychologists/
- https://euroweeklynews.com/2025/11/02/dental-tourism-taking-off-in-costa-del-sol-particularly-with-uk-patients/ ; https://facua.org/en/noticias/facua-denounces-the-fraudulent-closure-of-the-odontology-clinics-dental-line/
- https://www.theolivepress.es/spain-news/2025/03/28/expats-demand-urgent-regulation-of-the-funeral-plan-sector-in-spain-after-collapse-of-iberian/
- https://comparafune.es/repatriation-cost-spain-to-uk/ ; https://avalonfuneralplans.com/expat-funeral-plans/spain/repat-burial-plan-spain/ ; https://www.goldenleavesinternational.com/plan-details/repatriation-plan-spain/ ; https://247expatinsurance.com/guides/funeral-insurance-spain-expat-guide/
- https://petplan.es/en/real-cost-vet-spain-2026/ ; https://www.idealista.com/en/news/lifestyle-in-spain/2026/04/20/848628-moving-to-spain-with-pets-complete-guide-for-2026 ; https://www.crystaltravel.co.uk/news/eu-pet-travel-rules-uk-costs-animal-health-certificate ; https://blog.advancemoves.com/%F0%9F%90%BE-how-to-move-your-pet-to-spain-from-the-uk-the-complete-2025-guide/ ; https://vetspluspets.es/ ; https://www.hospitalveterinariocostadelsol.es/en/

### Senior living
- https://www.eleconomista.es/vivienda-inmobiliario/noticias/13956809/06/26/la-costa-del-sol-acelera-su-carrera-para-convertirse-en-referente-europeo-del-senior-living.html
- https://www.cbre.es/en-gb/insights/articles/senior-living-oportunidad-estrategica-para-dar-solucion-habitacional-a-la-generacion-senior
- https://www.luanaseniorliving.com/en ; https://eurofundgroup.com/projects/luana-senior-living/ ; https://life3a.com/projects/luana-senior-living/
- https://www.thepatiomarbella.com/es/ ; https://huetearquitectos.com/residencia-seniors-the-patio/ ; https://estepona.costasur.com/en/clinic/the-patio-marbella-ccrc.html
- https://miresi.es/apartamentos-para-mayores/andalucia/malaga/malaga/vivienda-para-mayores-coccon-estepona/ ; https://mundomayor.com/informacion/apartamentos-senior
- https://www.watg.com/project/senior-living-at-bogaris-costa-del-sol/
- https://letsinvest.eu/project/178
- https://www.marbella-estates.com/8758-top-10-retirement-communities-on-the-costa-del-sol

### Education / childcare
- https://www.international-schools-database.com/in/malaga-costa-del-sol
- https://www.micole.net/buscador/colegios-internacionales-malaga
- https://www.ischooladvisor.com/articles/schooling-and-school-choice/costs-and-fees-understanding-funding/international-school-fees-marbella-costa-del-sol-2026
- https://guides.waypointsur.com/international-schools-malaga/ ; https://guides.waypointsur.com/school-admissions-spain/
- https://delsolprimehomes.com/en/blog/comparison-guide-best-schools-for-expat-families-in-costa-del-sol
- https://expatpropertygroup.com/costa-del-sol-international-schools-fees-curricula-admissions/
- https://malagaschools.com/2025/11/28/applying-to-private-international-schools-in-spain-from-abroad-what-to-expect-and-how-to-navigate-the-process/
- https://www.malaga.eu/la-ciudad/instalaciones-y-espacios/detalle-de-la-instalacion/?id=234
- https://www.juntadeandalucia.es/temas/estudiar/infantil/admision-primer-ciclo.html ; https://fsieandalucia.es/noticias/ed-infantil-calendario-procedimiento-admision-26-27
- https://donpablito.com/precios/

### Added late (expat ageing / childcare)
- https://euroweeklynews.com/2026/08/04/older-britons-in-spain-face-a-painful-choice-as-the-retirement-dream-becomes-harder-to-live/
- https://www.facebook.com/groups/brexpatsinspain/posts/3393378777489774/
- https://ageconcernfym.com/ ; https://www.facebook.com/ageconcernmarbella/videos/age-concern-marbella-san-pedro/862053399702732/
- https://pccwealth.com/retire-to-spain-from-the-uk/
- https://guides.waypointsur.com/childcare-nurseries-costa-del-sol/
- https://www.expatica.com/es/living/family/childcare-spain-101464/
- https://www.idealista.com/en/news/lifestyle-in-spain/2026/05/05/890078-childcare-in-spain-for-expats-costs-options-what-you-need-to-know-in-2026
- https://costadelsolbabysitting.com/ ; https://luxoestates.com/activities/nannies-babysitting-services-marbella-2026/

### GAPS (not found within tool limits — flagged for follow-up)
- INE padrón 2025 breakdown by nationality x age for Málaga (INE stopped publishing nationality groupings after 2023; need INE microdata or Junta IECA "SIMA").
- Official SAS per-hospital waiting-list tables for 2026 (available on ClicSalud+/SAS site; could not fetch).
- Public residencia waiting time in months for Málaga; Junta concerted-place price.
- Costa del Sol-specific vet complaint data; kennel/pet-sitter pricing.
- English-speaking nursery/nanny hourly rates and shortage evidence.
- Sports academies and tutoring market data.
- Private-hospital international-patient volumes (Quirón/Vithas/HC Marbella).
- Age Concern España / Age in Spain 2025 activity statistics.
- Physiotherapy/rehab and mobility-aid market data.
