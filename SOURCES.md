# Historical Rebirth — source and editorial review

Checked: 2026-10-28
Dataset: `rebirth-era-data.json`
Schema: 1; kind: `era`; slug: `rebirth-era`

## Content inventory

- 24 stable scenario IDs.
- 8 actual text languages: Korean, English, Spanish, Simplified Chinese, Japanese, German, French and Portuguese.
- 192 localized entry objects, each with name, blurb, five fields and an independently authored two-sentence vignette.
- Fields: clothes, home, work, day and life.
- All entries have `art.type = "human"`; the renderer uses original schematic SVG parameters. No external image, font, SVG, photograph or museum illustration is included.
- All integer years from 10000 BCE through 1 BCE and 1 CE through 2026 are covered by at least one scenario. Year zero is absent.
- All 24 scenarios have weight 10. These are authored game weights, with equal initial scenario probability of 1/24, approximately 4.17%. They are not demographic estimates. A scenario is selected first and a year is selected uniformly inside its inclusive range. Therefore years are not globally uniform; overlapping and shorter ranges change a year's total chance.
- Redraw excludes the current scenario and therefore has conditional probabilities. The application must retain this distinction when showing percentages.

## Historical facts and fictional placements

The sources establish broad contexts: periods, settlements, material culture, subsistence, crafts, trade or documented changes in housing. The game then places an invented unnamed person within a compatible context. No person is identified as an actual historical individual. Their particular job assignment, household, rented room, actions, conversations, tools prepared that evening and personal schedule are authored fiction. They are neither representative surveys nor a reconstruction of every person in that society.

Clothing is especially uncertain in prehistoric contexts. Those entries explicitly call their clothing imagined and avoid claiming a known garment cut. Other fictional workwear remains deliberately plain. No elite garment is asserted to have been the universal dress of a population. Houses and occupational roles are possible scenario settings; they are not promised for all inhabitants.

The long Nile scenario is explicitly a farming household, without a specific dynasty, monument or title. Mesopotamia's early range uses a general water-channel context instead of projecting later city institutions into 4000 BCE. Çatalhöyük ends at 6200 BCE to remain inside the cited eastern-settlement chronology. The Shang entry does not claim that its person worked at Anyang throughout the dynasty. The Han clerk does not repeat the source page's simplified claim about a fully developed entrance-examination system. The Tang scenario starts at 618. The Norse scenario depicts a farm rather than assuming that everyone was a raider.

Maya cultural continuity is respected: the dataset does not imply that Maya people vanished. Maize context is supported by archaeological research alongside a Smithsonian Indigenous educational resource; no sacred narrative is reproduced. Great Zimbabwe is explicitly a Shona context, not an outside-origin legend. No empire, nation or region is ranked as superior.

The modern Tokyo and Seoul ranges cross war, disaster and reconstruction. Their localized conditions fields explicitly state strong differences by year. A fictional home and shop can exist in a drawn year, but the game does not imply an undamaged city or a single unchanged lifestyle. Singapore's 2001–2026 setting uses established housing, amenities and transport. It makes no unverified 2026 price, employment-share, current-officeholder or future-event claim, and it avoids assigning smartphones to every year in the range.

## Scenario ranges and source mapping

| ID | Inclusive historical-year range | Main citation IDs |
| --- | --- | --- |
| britain-forager | -10000 to -4001 | britain |
| catalhoyuk-household | -7100 to -6200 | catal, catal-chronology |
| mesopotamia-canal-worker | -4000 to -2000 | meso |
| nile-farming-household | -3000 to -301 | egypt, egypt-clothes |
| indus-bead-worker | -2600 to -1900 | indus |
| shang-bronze-assistant | -1600 to -1050 | shang, china-chronology |
| greek-pottery-worker | -800 to -301 | greek |
| roman-market-worker | -300 to -1 | roman |
| han-clerk | 1 to 220 | han |
| moche-irrigation-farmer | 200 to 700 | moche |
| maya-maize-grower | 250 to 900 | maya, maya-farming |
| tang-market-assistant | 618 to 907 | tang |
| norse-farm-household | 800 to 1100 | norse |
| abbasid-basra-potter | 800 to 1100 | abbasid |
| great-zimbabwe-trade-helper | 1100 to 1450 | zimbabwe |
| angkor-water-worker | 1100 to 1400 | angkor |
| joseon-village-household | 1400 to 1600 | joseon |
| ottoman-iznik-potter | 1500 to 1700 | ottoman |
| mughal-cotton-tailor | 1600 to 1750 | mughal |
| edo-clothing-mender | 1700 to 1850 | edo |
| manchester-mill-worker | 1850 to 1900 | manchester |
| tokyo-neighbourhood-shop-worker | 1901 to 1950 | tokyo |
| seoul-household-shop-helper | 1951 to 2000 | seoul, seoul-housing |
| singapore-neighbourhood-worker | 2001 to 2026 | singapore |

## Sources and verification boundary

The URLs below were verified in web search results or opened with the web tool during this work. Verification means that a matching institutional/research title and relevant content were returned. Not every full page or PDF was read end to end, and no browser visual inspection was performed. Source facts were used selectively; the fictional particulars described above do not carry a claim of direct historical attestation.

No external assets or protected passages are redistributed. Facts were independently restated in new concise prose, then independently translated into each supported language. Source titles and URLs are citations. This work does not rely on permission to reproduce a source's text, photographs or editorial illustrations. In particular, the Çatalhöyük Research Project labels its site CC BY-NC 4.0; no licensed text or image from that site is copied, adapted as an asset or distributed under that license. UNESCO's page descriptions identify CC BY-SA IGO 3.0; their prose and translated descriptions were not reused. Links do not imply institutional endorsement.

### britain

[British Museum — Prehistoric Britain school resource](https://www.britishmuseum.org/sites/default/files/2019-09/visit-resource_prehistoric-britain-KS2.pdf)

Scope: Mesolithic gathering, fishing, seasonal movement; clothing is explicitly imagined.

Reuse: citation and underlying historical facts only. No source text or assets included.

### catal

[Çatalhöyük Research Project — Life at Çatalhöyük](https://www.catalhoyuk.com/node/57)

Scope: Grain processing context and bone/obsidian craft; no text or illustrations reused.

Reuse: citation and underlying historical facts only. No source text or assets included.

### catal-chronology

[UNESCO — Çatalhöyük nomination](https://whc.unesco.org/uploads/nominations/1405.pdf)

Scope: Settlement chronology; the scenario ends at 6200 BCE.

Reuse: citation and underlying historical facts only. No source text or assets included.

### meso

[Penn Museum — Mesopotamian City Life](https://www.penn.museum/sites/expedition/mesopotamian-city-life/)

Scope: Labour, food, housing and differentiated occupations. Individual canal-worker routine is fiction.

Reuse: citation and underlying historical facts only. No source text or assets included.

### egypt

[Harvard Digital Giza — Daily Life in Ancient Egypt](https://giza.fas.harvard.edu/lessons/daily-life-in-ancient-egypt/)

Scope: Agriculture, grain preparation, crafts; evidence is incomplete and funerary scenes have ritual purposes.

Reuse: citation and underlying historical facts only. No source text or assets included.

### egypt-clothes

[Glencairn Museum / Penn Museum curator — Daily Life in Ancient Egypt](https://www.glencairnmuseum.org/newsletter/2025/11/4/daily-life-in-ancient-egypt-insights-from-the-glencairn-museum-collection)

Scope: Clothing and daily-use objects; selected contextual facts only.

Reuse: citation and underlying historical facts only. No source text or assets included.

### indus

[National Museum, New Delhi — Life in Harappan Civilization](https://nationalmuseumindia.gov.in/assets/pdf/Life-in-Harappan-Civilization-activity-booklet.pdf)

Scope: Harappan houses, craft and cotton; imagined household and personal schedule.

Reuse: citation and underlying historical facts only. No source text or assets included.

### shang

[Smithsonian National Museum of Asian Art — Ancient Chinese Bronzes](https://asia.si.edu/ancient-chinese-bronzes/)

Scope: Bronze casting and Shang objects; no social treatment of an individual is claimed.

Reuse: citation and underlying historical facts only. No source text or assets included.

### china-chronology

[Smithsonian National Museum of Asian Art — Explore by Dynasty](https://asia-archive.si.edu/learn/for-educators/teaching-china-with-the-smithsonian/explore-by-dynasty/)

Scope: Shang, Han and Tang chronology.

Reuse: citation and underlying historical facts only. No source text or assets included.

### greek

[The Metropolitan Museum of Art — Ancient Greek Dress](https://www.metmuseum.org/ko/essays/ancient-greek-dress)

Scope: Chiton and work clothing; pottery assistant and rented room are fictional assignments.

Reuse: citation and underlying historical facts only. No source text or assets included.

### roman

[University of Münster Archaeological Museum — Ancient Costume](https://www.uni-muenster.de/ArchaeologischesMuseum/en/f_hrungen/antike_tracht.html)

Scope: Roman tunic and cloak context; market job and tenancy are fictional assignments.

Reuse: citation and underlying historical facts only. No source text or assets included.

### han

[Smithsonian National Museum of Asian Art — Han dynasty](https://asia-archive.si.edu/learn/for-educators/teaching-china-with-the-smithsonian/explore-by-dynasty/han-dynasty/)

Scope: Writing and clerical scripts; no claim of a modern-style examination system.

Reuse: citation and underlying historical facts only. No source text or assets included.

### moche

[Yale eHRAF Archaeology — Moche description](https://ehrafarchaeology.yale.edu/traditions/se55/description)

Scope: Irrigation farming and north-coast context, 50–800 CE.

Reuse: citation and underlying historical facts only. No source text or assets included.

### maya

[Smithsonian National Museum of the American Indian — Creation Story of the Maya](https://maya.nmai.si.edu/the-maya/creation-story-maya)

Scope: Maize significance; no mythic characters or sacred narrative reproduced.

Reuse: citation and underlying historical facts only. No source text or assets included.

### maya-farming

[Early isotopic evidence for maize as a staple grain in the Americas — original research](https://pmc.ncbi.nlm.nih.gov/articles/PMC7269666/)

Scope: Archaeological evidence for maize as a regional staple, not a universal quantified diet.

Reuse: citation and underlying historical facts only. No source text or assets included.

### tang

[Smithsonian National Museum of Asian Art — Tang dynasty](https://asia-archive.si.edu/learn/for-educators/teaching-china-with-the-smithsonian/explore-by-dynasty/tang-dynasty/)

Scope: Chang'an, trade and movement of goods; individual market helper is fictional.

Reuse: citation and underlying historical facts only. No source text or assets included.

### norse

[Museum of the Viking Age, University of Oslo — Society and Daily Life](https://www.vikingtidsmuseet.no/english/viking-age/society-and-daily-life/)

Scope: Farm-centred work, household and community.

Reuse: citation and underlying historical facts only. No source text or assets included.

### abbasid

[Ashmolean Museum — Abbasid Ceramics: Pottery as Alchemy](https://islamicceramics.ashmolean.org/Abbasid/pottery.htm)

Scope: Basra kiln evidence; personal housing and routine are fictional.

Reuse: citation and underlying historical facts only. No source text or assets included.

### zimbabwe

[UNESCO — Great Zimbabwe National Monument](https://whc.unesco.org/en/list/364)

Scope: Shona city, 1100–1450 construction, earthen households, farming, herding and trade.

Reuse: citation and underlying historical facts only. No source text or assets included.

### angkor

[UNESCO — Angkor](https://whc.unesco.org/en/list/668/)

Scope: Hydraulic structures and agricultural context; wooden household and maintenance schedule are imagined.

Reuse: citation and underlying historical facts only. No source text or assets included.

### joseon

[National Institute of Korean History — Clothes](https://contents.history.go.kr/play/view.do?levelId=tz_b18)

Scope: Hemp/cotton clothing and status-linked dress; household is fictional.

Reuse: citation and underlying historical facts only. No source text or assets included.

### ottoman

[Ashmolean Museum — Ottoman ceramics](https://jameelcentre.ashmolean.org/collection/6/653/834)

Scope: İznik production from late 15th century; no use of a later colour at an earlier date is required.

Reuse: citation and underlying historical facts only. No source text or assets included.

### mughal

[The Metropolitan Museum of Art — Man's Robe (Jama) with Poppies](https://www.metmuseum.org/art/collection/search/448247)

Scope: Cotton garment and rank-linked dress; elite object is not presented as a commoner's exact outfit.

Reuse: citation and underlying historical facts only. No source text or assets included.

### edo

[The Metropolitan Museum of Art — Kimono Style exhibition](https://www.metmuseum.org/de/press/exhibitions/2022/kimono-style)

Scope: Kosode/kimono context, regulation and reuse of cotton clothing.

Reuse: citation and underlying historical facts only. No source text or assets included.

### manchester

[Science and Industry Museum — Textiles Gallery guide, book 1](https://www.scienceandindustrymuseum.org.uk/sites/default/files/2021-12/SIM_LargePrintBook_TextilesGallery_UpperLevel_Book1-compressed.pdf)

Scope: Mechanised cotton work and cotton dust hazards; no invented fixed hours or wage figures.

Reuse: citation and underlying historical facts only. No source text or assets included.

### tokyo

[Edo-Tokyo Museum — Permanent Exhibition](https://www.edo-tokyo-museum.or.jp/en/p-exhibition/)

Scope: Urban household/shop context, earthquake and wartime disruption; dates remain broad fiction.

Reuse: citation and underlying historical facts only. No source text or assets included.

### seoul

[Seoul Museum of History — Problems of Overcrowded Seoul](https://museum.seoul.go.kr/www/board/NR_boardView.do?bbsCd=1182&seq=20221212145905646&sso=ok&tr_code=sweb)

Scope: Housing pressure and shortages in 1960s context; not asserted unchanged throughout 1951–2000.

Reuse: citation and underlying historical facts only. No source text or assets included.

### seoul-housing

[Seoul Metropolitan Archives — Housing change in the 1950s and 1960s](https://archives.seoul.go.kr/contents/house-03)

Scope: Changing housing types, not a fixed universal dwelling.

Reuse: citation and underlying historical facts only. No source text or assets included.

### singapore

[Housing & Development Board — Plan and Design Towns](https://www.hdb.gov.sg/about-us/our-role/plan-and-design-towns)

Scope: Town amenities, public transport and neighbourhood connections; no 2026 population or price claim.

Reuse: citation and underlying historical facts only. No source text or assets included.

## Validation

Dataset structure, IDs, positive weights, all eight language keys, matching field keys, two-sentence story strings, valid art enums/colours, nonzero historical ranges, source references and complete required-year coverage were checked. Native-language editorial review, archaeological specialist review, browser rendering, game-controller behavior and release verification remain application/release responsibilities.

The SVG is schematic rather than an archaeological costume reconstruction. Avoid describing it as a verified portrait or precise historical outfit. Wide scenario ranges and the limited number of regions are deliberate game simplifications; the dataset does not cover every culture or social condition.
