---
title: North American Fruit & Nut Tree Crop Wild Relatives Working Group
description:  
---

## Resources, references & data associated with our conservation gap analysis

<br>

# REFERENCES FOR METHODS
Carver, D., Sosa, C. C., Khoury, C. K., Achicanoy, H. A., Victoria Diaz, M., Sotelo, S., Castañeda-Álvarez, N. P., & Ramirez-Villegas, J. (2021). GapAnalysis: an R package to calculate conservation indicators using spatial information. Ecography, 44(7), 1000-1009. <a href="https://onlinelibrary.wiley.com/doi/full/10.1111/ecog.05430" target="_blank">https://onlinelibrary.wiley.com/doi/full/10.1111/ecog.054</a>.

Khoury, C. K., Carver, D., Greene, S. L., Williams, K. A., Achicanoy, H. A., Schori, M., León, B., Wiersema, J. H., & Frances, A. (2020). Crop wild relatives of the United States require urgent conservation action. PNAS, 117(52), 33351-33357. <a href="https://www.pnas.org/doi/10.1073/pnas.2007029117" target="_blank">https://www.pnas.org/doi/10.1073/pnas.2007029117</a>.

The following script repositories were used/created for downloading and processing data, and completing analyses:
 > <a href="https://github.com/eb-bruns/SDBG_CWR-trees-gap-analysis" target="_blank">Download and process occurrence data</a><br>
 > <a href="https://github.com/eb-bruns/CWR-of-the-USA-Gap-Analysis" target="_blank">Create species distribution models</a><br>
 > <a href="https://github.com/eb-bruns/GapAnalysis" target="_blank">Perform conservation gap analyses</a>

<br>

# SPATIAL LAYERS USED IN ANALYSES

**Global ecoregions**<br>
Olson, D. M. 2020. Terrestrial ecoregions of the world (Copy to use in GapAnalysis R package). <a href="https://doi.org/10.7910/DVN/WTLNRG" target="_blank">https://doi.org/10.7910/DVN/WTLNRG</a>. Harvard Dataverse, V1.

**Global protected areas**<br>
Arango, S. & Camilo, C. 2020. Protected areas (WDPA). <a href="https://doi.org/10.7910/DVN/XIV9BL" target="_blank">https://doi.org/10.7910/DVN/XIV9BL</a>. Harvard Dataverse, V1.

<br>

# SOURCES FOR OCCURRENCE POINTS

**Botanical Information and Ecology Network (BIEN)**<br>
BIEN. 2022. Occurrence data downloaded via the R package ‘BIEN’. Accessed 15 November 2022.<br>
>Maitner, B. (2022). BIEN: Tools for Accessing the Botanical Information and Ecology Network Database. R package version 1.2.5, <a href="https://CRAN.R-project.org/package=BIEN" target="_blank">https://CRAN.R-project.org/package=BIEN</a>.

Original data sources for our BIEN downlaod include:
 > Enquist, B. J., Sandel, B., Boyle, B., Svenning, J.-C., McGill, B. J., Donoghue, J. C., … ter Steege, H. (n.d.). Botanical big data shows that plant diversity in the New World is driven by climatic-linked differences in evolutionary rates and biotic exclusion.<br><br>
 S., M. B., Brad, B., Nathan, C., Rick, C., John, D., M., D. S., … J., E. B. (n.d.). The bien r package: A tool to access the Botanical Information and Ecology Network (BIEN) database. Methods in Ecology and Evolution, 9(2), 373–379. doi:10.1111/2041-210X.12861.<br><br>
 Peet, R. K., Lee, M. T., Boyle, M. F., Wentworth, T. R., Schafale, M. P., & Weakley, A. S. (2012).<br><br>
 Vegetation-plot database of the Carolina Vegetation Survey. Biodiversity and Ecology, 4, 243–253.<br><br>
 Enquist, B., & Boyle, B. (2012). SALVIAS -- the SALVIAS vegetation inventory database. Biodiversity & Ecology, 4, 288–288.<br><br>
 SpeciesLink. (2012). Retrieved 29 March 2012, from http://www.splink.org.br/.<br><br>
 Peet, R. K., Lee, M. T., Jennings, M. D., & Faber-Langendoen, D. (2012). VegBank: a permanent, open-access archive for vegetation plot data. Biodiversity and Ecology, 4, 233–241.<br><br>
 *We acknowledge the herbaria that contributed data to this work:* U, MBML, BRIT, M, CSLA, CMC, CM, BRNU, BHSC, BERN, AU, LOB, KSP, KR, GJO, FSC, DES, TAA, SJC, SHIN, PI, NMLU, WSCO, WCUH, A, AAU, ABH, AD, AK, ARAN, ASU, B, BABY, BC, BG, BOON, BOUM, BR, BRI, CANB, CAS, CHR, CHRB, CHSC, CICY, CNH, COA, COLO, CORD, CS, CU, DAV, DBG, E, EKY, F, FCO, FLAS, FR, FSU, FTG, FULD, FURB, G, GEO, GH, GLM, GZU, HAL, HAST, HO, HSS, HU, HUSA, IAC, ICN, INM, INPA, KYO, K, KMN, KPM, KSTC, KU, L, LAGU, LD, LEB, LI, LSU, MA, MAF, MBK, MBM, MEL, MELU, MICH, MIN, MNHM, MNHN, MO, MSC, NAC, NAS, NCSC, NCU, NE, NMR, NSW, NT, NY, O, OBI, OSC, PAMP, PE, PH, POM, RM, RSA, S, SBBG, SCFS, SD, SDSU, SFV, SI, SJSU, TAI, TAIF, TALL, TAM, TENN, TEX, TI, TKPM, TNS, TROM, UAM, UCR, UCS, UCSB, UCSC, UFMA, UFMT, UNEX, UNM, US, USCH, USF, USP, UTEP, VAL, VIT, VT, W, WU.
 
**Global Biodiversity Information Facility (GBIF)**<br>
GBIF.org (14 November 2022) GBIF Occurrence Download <a href="https://doi.org/10.15468/dl.365w8r" target="_blank">https://doi.org/10.15468/dl.365w8r</a>. Downloaded via the R package ‘rgbif’.
>Chamberlain, S., Barve, V., Mcglinn, D., Oldoni, D., Desmet, P., Geffert, L., & Ram K. (2021). rgbif: Interface to the Global Biodiversity Information Facility API. R package version 3.6.0, <a href="https://CRAN.R-project.org/package=rgbif" target="_blank">https://CRAN.R-project.org/package=rgbif</a>.

**Integrated Digitized Biocollections (iDigBio)**<br>
iDigbio. 2022. Occurrence data downloaded via the R package ‘ridigbio’. Accessed 15 November 2022.<br>
>Michonneau F., & Collins, M. (2022). ridigbio: Interface to the iDigBio Data API. R package version 0.3.6, <a href="https://CRAN.R-project.org/package=ridigbio" target="_blank">https://CRAN.R-project.org/package=ridigbio</a>.

**IUCN Red List**<br>
IUCN. 2022. The IUCN Red List of Threatened Species. Version 2022-2. <a href="https://www.iucnredlist.org/search?permalink=f697d499-894b-46c3-a095-d3e4955e750d" target="_blank">https://www.iucnredlist.org/search?permalink=f697d499-894b-46c3-a095-d3e4955e750d</a>. Accessed on 15 November 2022.

**North American herbaria consortia (via SEINet Portal)**<br>
*Biodiversity occurrence data published by:* AASU, ACU, ALA, ALAM, ALBC, ANHC, APCR, APSC, ARCH, ARIZ, ASC, ASDM, ASU, AUA, AUGIE, AVCH, AWC, BALT, BAYLU, BCH, BCMEX, BCWS, BDI, BDWR, BENN, BEREA, BHSC, BLM, BOON, BRIT, Brown, BRU, BRY, BTA, Bureau of Land Management, BUT, CalBG, CALVIN, CATU, CAU, CHAS, CHIC, CHRB, CIAD, CIBO, CINC, CLEMS, CM, CMC, CMN, COCO, COLO, CONV, CS, CSCN, DAV, DBG, DEK, DES, DOV, DSC, DSUND, DUKE, DWC, ECUH, EIU, EKY, EMC, ENLC, ENMU, ENO, EPHR, ERDC, ETSU, F, FARM, FLAS, FLD, FMUH, FSU, FTG, FTPK, FTU, FUGR, FWNC, GA, GAS, GCNP, GEO, GMDRC, GMUF, GND, GreaterGood, GREE, GSMNP, GSW, GVSC, Harvard, HBSH, HCHM, HCIB, HEND, HJAAA-FCB, HLSD, HNT, HOSP, HPC, HSU, HTTU, HUAP, HUDC, HUNT, HWBA, HXC, IBUG, ICHAUWAY, ILL, ILLS, iNaturalist, IND, IPN, ISTC, IUP, JEF, JEMEZ, JMUH, JWC, KANU, KE, KNFY, KNK, KSP, LAF, LCDI, LEA, LFCC, LL, LOB, LSU, LSUA, LSUS, LUC, LYN, MABA, MARY, MCA, MDKY, MEM, MESA, MICH, MIN, MISS, MISSA, MISU, MMNS, MNA, MO, MOAR, MOR, MOVC, MSC, MSUB, MSUNH, MTSU, MU, MUHW, MUR, MUSK, MWCF, MWI, NAVA, NBYC, NC, NCSC, NCSM, NCU, NCZP, NEON, NHI, NLU, NMC, NMCR, NO, NPS, NTS, NTSC, NY, OBI, OCU, ODU, OKL, OKLA, OSC, OSH, PAC, PAUH, PEMB, PFBP, PGC, PH, PIHG, PUA, PUSC, QMEX, RARO, RENO, RHNM, RM, RMBL, SALK, SAT, SAU, SBAC, SBBG, SC, SCFS, SCIR, SD, SDSU, SEINet, SEL, SEL, USF, SELU, SENEY, SEU, SFRP, SIM, SJNM, SJSU, SNM, Sonoran Atlas, SPIF, SRSC, SSLP, STAR, SUCO, SUU, SWMT, SWRS, SWSL, TAC, TAF, TAWES, TCNJ, TENN, TEX, TLU, TROY, TSJC, TTC, TTRS, UAC, UAM, UARK, UAS, UCAC, UCHT, UCOL, UCR, UCSC, UNA, UNCA, UNCC, UNLV, UNM, UOS, uruza, URV, USAM, USCH, USCS, USF, USFS, USFS/BHSC, USFWS, USMS, USON, USU, UT, Utah State University, Utah Tech University, UTEP, UTM, UVSC, UWEC, UWFP, UWGB, UWSP, VCU, VDB, VMIL, VPI, VSC, VSUH, VT, WASH, WCUH, Weber State University, WET, WEWO, WFU, WGC, WILLI, WINU, WIS, WJC, WLM, WMU, WSC, WVA, WVW, WWC, YPM, ZNP (Accessed through SEINet Portal Network Data Portal, <a href=“https://swbiodiversity.org/seinet/collections/index.php" target="_blank">https://swbiodiversity.org/seinet/collections/index.php</a>, 2022-11-15)

**USDA Forest Inventory and Analysis (FIA)**<br>
November 16, 2022. Forest Inventory and Analysis Database, St. Paul, MN: U.S. Department of Agriculture, Forest Service, Northern Research Station. Available only on internet: <a href="https://apps.fs.usda.gov/fia/datamart/datamart.html" target="_blank">https://apps.fs.usda.gov/fia/datamart/datamart.html</a>

<br>

# SOURCES FOR EX SITU ACCESSIONS DATA

**Genesys**<br>
Data accessed through Genesys, <a href="https://www.genesys-pgr.org/a/v2glq2qZEPm" target="_blank">https://www.genesys-pgr.org/a/v2glq2qZEPm</a>, 17 March 2022.

**Food and Agriculture Organization of the United Nations**<br>
FAO. WIEWS - World Information and Early Warning System on Plant Genetic Resources for Food and Agriculture. Ex situ search. <a href="https://www.fao.org/wiews/data/ex-situ-sdg-251/search/en/?no_cache=1" target="_blank">https://www.fao.org/wiews/data/ex-situ-sdg-251/search/en/?no_cache=1</a>. Accessed 23 May, 2022.

**Ex situ accession-level survey, carried out as part of this project**<br>
*Thank you to the following institutions, who provided their collections data:* Adkins Arboretum | Arboreti sperimentali di Vallombrosa | Arboretum at Penn State, The | Arboretum at the University of California, Santa Cruz | Arboretum Kirchberg | Arboretum Mustila | Arboretum National des Barres (et Fruticetum Vilmorinianum) | Arboretum Wespelaar | Arboretum-Pinetum Lucus Augusti | Arnold Arboretum of Harvard University, The | Atlanta Botanical Garden | Bamboo Brook Outdoor Education Center | Batumi Botanical Garden | Bedgebury National Pinetum & Forest | Bergen Botanical Garden | Bergius Botanic Garden | Bernheim Arboretum and Research Forest | Betty Ford Alpine Gardens | Birmingham Botanical Gardens and Glasshouses | Blue Mountains Botanic Garden, Mount Tomah | Bogor Botanic Gardens | Bok Tower Gardens Conservation Program - Living Plants | Bok Tower Gardens Conservation Program - Seed Bank | Botanic Garden at Historic Barns Park, The | Botanic Garden, Lund University | Botanic Gardens of South Australia | Botanical Garden of Klaipeda University | Botanical Garden of Tartu University | Botanical Garden of the University of Bern | Botanische Gärten der Universität Bonn | Botanischer Garten der Carl von Ossietzky-Universitat Oldenburg | Botanischer Garten der Technischen Universitaet Darmstadt | Botanischer Garten der Universitat Osnabruck | Botanischer Garten Frankfurt am Main | Brenton Arboretum, The | Brisbane Botanic Gardens | Brooklyn Botanic Garden | California Botanic Garden | California Botanic Garden - Seed Bank | Centennial Museum and Chihuahuan Desert Gardens | Central Siberian Botanical Garden, Siberian Branch, Russian Academy of Sciences | Château Pérouse | Chesterfield County Arboretum | Chicago Botanic Garden | Coastal Maine Botanical Gardens | Connecticut College Arboretum | Conservatoire et Jardin botaniques de la Ville de Genève | Cornell Botanic Gardens | Cowichan Lake Research Station Arboretum | Dawes Arboretum, The | Denver Botanic Gardens | Denver Botanic Gardens - Seed Bank | Descanso Gardens | Desert Botanical Garden | Desert Botanical Garden - Seed Bank | Donald E. Davis Arboretum | Douglas County Fairgrounds Arboretum | Dunedin Botanic Garden | Eastwoodhill Arboretum | Edison and Ford Winter Estates | Fairchild Tropical Botanic Garden | Filoli | Finnish Museum of Natural History / Helsinki University Botanic Garden | Forstbotanischer Garten der Technischen Universität Dresden | Frelinghuysen Arboretum | Ghent University Botanic Garden | Gothenburg Botanical Garden | Gradina Agro-Botanica din Cluj-Napoca | Great Lakes Forestry Centre Arboretum | Green Bay Botanical Garden | Greenwich Town Arboretum | Harold L. Lyon Arboretum | Hazel Crest Openlands | Hof ter Saksen Arboretum | Hortus Arboretum and Botanical Gardens | Hortus Botanicus Amsterdam | Hortus Botanicus Reykjavikensis | Huntington Library, Art Museum and Botanical Gardens, The | Huntsville Botanical Garden | Instituto de Botânica 'Gonçalo Sampaio' | Jardí Botànic Marimurtra | Jardim Botânico da Universidade de Lisboa | Jardim Botânico de Jundiaí - Valmor de Souza | Jardim Botânico Tropical | Jardin Botânico Benjamin F. Johnston | Jardín Botánico de Bogotá José Celestino Mutis | Jardín Botánico de la ciudad de Buenos Aires "Carlos Thays'' | Jardín Botánico Francisco Javier Clavijero | Jardín Botanico-Historico "La Concepción" de Malaga | Jardin Botanique Alpin de la Jaÿsinia | Jardin botanique de l'Université de Fribourg | Jardin Botanique de l'Université de Strasbourg | Jardin botanique de Paris | Jardin Botanique Exotique "Val Rahmeh" | Jardin des Plantes | Jardin des Plantes de Paris et Arboretum de Chevreloup | JC Raulston Arboretum | Jerusalem Botanical Gardens | Kaskey Gardens | Les Jardins Suspendus | Lincoln Park Zoo | Linnaean Gardens of Uppsala, The (Uppsala University) | Longwood Gardens | Lystigardur Akureyrar | Maribor University Botanic Garden | Marie Selby Botanical Gardens | Mary M.B. Wakefield Estate & Arboretum | Memorial University Botanical Garden | Millennium Seed Bank | Milner Gardens and Woodland | Minnesota Landscape Arboretum | Missouri Botanical Garden | Missouri Botanical Garden - Seed Bank | Montgomery Botanical Center | Montreal Botanical Garden / Jardin botanique de Montréal | Morden Arboretum Research Station | Morton Arboretum, The | Mount Auburn Cemetery | Mount Holyoke College Botanic Garden | Mt. Airy Arboretum | Mt. Cuba Center | Museo Orto Botanico di Roma | Nanjing Botanical Garden Mem. Sun Yat-sen | Naples Botanical Garden | National Botanic Garden of Wales | National Botanic Gardens, Glasnevin | National Plant Germplasm System - USDA-ARS-NGRL | National Tropical Botanical Garden | National Tropical Botanical Garden - Seed Bank & Laboratory | Neuer Botanischer Garten der Universität Göttingen | New York Botanical Garden, The | Nezahat Gokyigit Botanic Garden | North Carolina Botanical Garden | Northwest Trek Wildlife Park | Olcott Arboretum at the Theosophical Society | Orto Botanico “Giardino dei Semplici” | Orto Botanico dell'Università degli Studi di Padova | Orto Botanico dell'Università della Calabria | Orto e Museo Botanico Università di Pisa | Oxford University Botanic Garden & Arboretum | Palomar College Gardens, The | Peckerwood Garden | Planting Fields Arboretum State Historic Park | Polly Hill Arboretum, The | Preston B. Bird/Mary Heinlein Redland Fruit & Spice Park | Pruhonice Botanic Garden | Pukekura Park | Quarryhill Botanical Garden | Red Butte Garden and Arboretum | Regional Parks Botanic Garden | Reiman Gardens | Rogów Arboretum of Warsaw University of Life Sciences | Rotterdam Zoological and Botanical Gardens | Royal Botanic Garden Edinburgh | Royal Botanic Gardens Kew, Wakehurst | Royal Botanic Gardens Sydney | Royal Botanic Gardens, Victoria - Melbourne Gardens | Royal Botanical Gardens, Ontario | Royal Horticultural Society's Garden, Harlow Carr | Royal Horticultural Society's Garden, Hyde Hall | Royal Horticultural Society's Garden, Rosemoor | Royal Horticultural Society's Garden, Wisley | Salisbury University Arboretum | San Diego Botanic Garden | San Francisco Botanical Garden | San Luis Obispo Botanical Garden | Sarah P. Duke Gardens | Seeds of Success (SOS) | Shaw Nature Reserve of the Missouri Botanical Garden | Sir Harold Hillier Gardens, The | Sister Mary Grace Burns Arboretum | Spring Grove Cemetery and Arboretum | Starhill Forest Arboretum | State Arboretum of Virginia (Orland E. White Arboretum) | State Botanical Garden of Kentucky, The Arboretum | Stoneleigh: a natural garden | Tasmanian Arboretum Inc | Trompenburg Gardens & Arboretum | UC Davis Arboretum | UConn Plant Biodiversity Conservatory and Research Center | United States Botanic Garden | United States National Arboretum | University Botanic Gardens Ljubljana | University of British Columbia Botanical Garden | University of California Botanical Garden at Berkeley | University of California Riverside Botanic Gardens | University of Guelph Arboretum | University of Washington Botanic Gardens | University of Washington Medicinal Herb Garden and Tree Collection | Utrecht University Botanic Gardens | VanDusen Botanical Garden | Viles Arboretum | W. J. Beal Botanical Garden | Wellesley College Botanic Gardens | Western Illinois School of Agriculture Greenhouse | Willowwood Arboretum | Xishuangbanna Tropical Botanical Garden, CAS

**BGCI GardenSearch**<br>
BGCI. 2022. GardenSearch. Botanic Gardens Conservation International. Richmond, U.K. Available at <a href="https://tools.bgci.org/garden_search.php" target="_blank">https://tools.bgci.org/garden_search.php</a>. Accessed January 2022.

**BGCI PlantSearch**<br>
BGCI. 2022. PlantSearch. Botanic Gardens Conservation International. Richmond, U.K. Available at <a href="https://tools.bgci.org/plant_search.php" target="_blank">https://tools.bgci.org/plant_search.php</a>. Accessed January 2022.

<br>

# OCCURRENCE DATA USED IN OUR CONSERVATION GAP ANALYSIS

Please note the large file size for these raw data downloads. You can also download data for each target taxon individually via the <a href="https://northamericanfruitnuttreecwr.github.io" target="_blank">taxon-specific reports</a>.

<a href="https://drive.google.com/file/d/1zB3ElICgQwlrfyFds7Q7QJHtaXikk2I3/view?usp=share_link" target="_blank">Download raw occurrence data for all target taxa [463 MB]</a><br>
>*Recommended citation:* Bruns, E.B., Khoury, C.K., McCarry, N., Meyer, A., Mims, R., Warschefsky E., and the North American Fruit and Nut Tree Crop Wild Relatives Working Group. (2023). Distributions and conservation status of North American fruit and nut tree crop wild relatives. Raw occurrence data for all target taxa. Accessed [DAY MONTH YEAR] from https://northamericanfruitnuttreecwr.github.io/docs/references.

<a href="https://drive.google.com/file/d/147dDMz_Hx8i2pdAqaLU_OH7qvxWQXWjT/view?usp=share_link" target="_blank">Download vetted occurrence coordinates (used to map) for all target taxa [56 MB]</a><br>
>*Recommended citation:* Bruns, E.B., Khoury, C.K., McCarry, N., Meyer, A., Mims, R., Warschefsky E., and the North American Fruit and Nut Tree Crop Wild Relatives Working Group. (2023). Distributions and conservation status of North American fruit and nut tree crop wild relatives. Vetted occurrence coordinates for all target taxa. Accessed [DAY MONTH YEAR] from https://northamericanfruitnuttreecwr.github.io/docs/references.

<br>
<br>
<br>
<br>

---

### Navigate to…
> <a href="https://NorthAmericanFruitNutTreeCWR.github.io" target="_blank">Landing page</a><br>
  <a href="https://NorthAmericanFruitNutTreeCWR.github.io/pages/taxa-home" target="_blank">Taxon-level conservation summaries</a><br>
  <a href="https://NorthAmericanFruitNutTreeCWR.github.io/pages/summaryfig" target="_blank">Summary figure of all conservation gap analysis results</a><br>

<br>

This work was led by Emily Beckman Bruns, Colin Khoury, Nan McCarry, Abby Meyer, Ray Mims, and Emily Warschefsky, and funded by the United States Botanic Garden. Emily Beckman Bruns was also supported by NSF ABI grant #1759759. Additional thanks to San Diego Botanic Garden, Botanic Gardens Conservation International - US, The Morton Arboretum, and Missouri Botanical Garden for providing organizational support. 

February 2023

<img src="https://NorthAmericanFruitNutTreeCWR.github.io/pages/partner-logos-composite.png" alt="Partner Logos"/>