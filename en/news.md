---
title: News
permalink: /news/
lang: en 
---
### NEWS
________________________________________________________________________________________  
### News/Edition E-LAUTE-ÖNB-Platform
- February 2026: release of [Jacob Turner, _Lautenbüchlein des Jakob Thurner_, A-Wn Cod. 9704](https://edition.onb.ac.at/fedora/objects/o:lau.A-Wn_Cod._9704/methods/sdef:TEI/get)    
- January 2026: release of [118 audio recordings](https://edition.onb.ac.at/fedora/objects/o:lau.audio/methods/sdef:TEI/get) from various sources (beta version)
- January 2026: release of [part of the database search](https://edition.onb.ac.at/fedora/objects/o:lau.db-search/methods/sdef:TEI/get) (beta version)
- December 2025: release of [Hans Judenkünig, _Ain schone kunstliche underweisung_, Wien 1523](https://edition.onb.ac.at/fedora/objects/context:elaute-overview/methods/sdef:Context/get)
- December 2025: release of [Hans Judenkünig, _Utilis et compendiaria introductio_, Wien [1523]](https://edition.onb.ac.at/fedora/objects/context:elaute-overview/methods/sdef:Context/get)
  

________________________________________________________________________________________      


________________________________________
#### Our Workshops:

- **Munich, Ludwig-Maximilian-University & Bayerische Staatsbibiliothek,18.9.-20.9.2024**: E-LAUTE Workshop
  
- **Basel, Schola Cantorum Basiliensis / FHNW Basel & Study Group Tablature in Western Music, International Musicology Society (IMS)**, 10.9.- 13.9.2025: E-LAUTE Workshop & IMS Tablature Group Conferece (public)     

___
#### What are we working on right now:
- We are developing the **editorial platform E-LAUTE** (host Austrian National Library, =ÖNB), which will be published in its initial phase in 2025:
  
 
<img class="left" src="/assets/img/Ed_platform_001.png"/>  
<img class="left" src="/assets/img/edition_1ex_001.png"/>

____
- **We are editing 1700 pages of tablature music**, searching for concordances and preparing synoptic views. Together with TabMEI Group and Laurent Pugin (Verovio) we are preparing the new version of MEI with lute tablatures (MEI 5.1.).
  
An example in mei-friend:  
<img class="left" src="/assets/img/Elslein_MEI-Friend_001.png"/>

An example on the ÖNB platform:     
<img class="left" src="/assets/img/Ed_ILT_MEI_001.png"/>  

____
- We have developed an internal **database (E-LAUTEdb)** for the material E-LAUTE and in particular for the historical-bibliographical cataloguing of model- and improvisation-based repertoire or fragments.
  
(1) We work on the source-original and uniform titles / text incipits, independent of the individual manuscripts or prints. So we are moving away from the concept of a 'completed unique piece':
  
<img class="left" src="/assets/img/ELAUTEdb_1_002.png"/>    
(2) Then we incorporate the entries (text, images, music) into each individual manuscript or print under the categories mentioned here, i.a. we do a new indexing of the whole material. 
  
<img class="left" src="/assets/img/E-LAUTEdb_2_001.png"/>  

(3) And then we work on the indivudual entries (text, images, music) from the individual manuscript or print under the categories mentioned here, i.a. 'Concordances'.  

<img class="left" src="/assets/img/E-LAUTEdb_3_001.png"/>  


____
- We discuss and finalise the joint **_Editorial Conventions_** for the literal and edited transcriptions into all tablature notations and common music notation (=CMN). The documentation will be published on the E-LAUTE edition platform.    
  

____
- Our lute performers ([_Schola Cantorum Basiliensis_](https://www.musik-akademie.ch/schola-cantorum-basiliensis/de/hochschule/studium.html)) create **audio recordings**. This audio part of the E-LAUTE project is increasingly developing into a comprehensive teaching project that will occupy several students of the lute class (Marc Lewon). (Further information will follow.)

<img class="left" src="/assets/img/Laute_Fragment_003.JPG"/>


____
- We evelop and finalise our **editing / encoding workflows**.

Here is a simplified schematic overview of our encoding workflow, the way to MEI files, which we are editing and will soon make available to everyone: we entered music into Fronimo (tablature) and MuseScore (CMN), convert the files to MEI and finalise them using [_mei-friend_](https://mei-friend.github.io) (Werner Goebl, David M. Weigl) to all required files. As the diagram shows, we co-operate with other developers, e.g. [_Luteconv_](https://luteconv.mdw.ac.at) (Paul Overell, E-LAUTE team), and at the same time create our own tools (_TabMEI_transcriber_; _AbsoLutely Tabulous_) (both Reinier de Valk). 
  
<img class="left blend" src="/assets/img/Workflow_edition_01.png"/>      



**Luteconv Converter:**     
<img class="left" src="/assets/img/Luteconv_01.png"/>

**AbsoLutely Tabulous:**   

<img class="left" src="/assets/img/AbsoLutely_001.png"/>

____
- We create **literal transcriptions in a project-specific reduced variant of CMN** that is in accordance with the tablature notation, consisting of one or two staves containing only stemless, black noteheads and rhythm flags (placed above the staff — as in the
tablature), in order to provide only pitch information (also automatically changeable) and avoid suggestions of duration and voice-leading (i.e., of polyphonic structure).  

<img class="left" src="/assets/img/iconic_MEI_ich_bin_ihr_001.png"/>  


____
- We are working on the **connection between MEI and TEI**:
   
<img class="left" src="/assets/img/Newsidler_Blatt_001.png"/>  

<img class="left blend" src="/assets/img/MEI_TEI_002.png"/>

____
- We develop and finalise **the infrastructure of the entire project**.
  
In the Git working environment (e.g., GitHub or GitLab), MEI files are produced by the E-Laute-Team using various technologies (Fronimo/Oxygen, AbsolutelyTabulous, mei-friend, etc.). Releases of these files are stored on the research data management system [TU-RDM](https://researchdata.tuwien.at/), which is based on InvenioRDM. The newest versions of these files are also stored on the GAMS infrastructure from ÖNB, where the digital edition is hosted. On the TU-RDM, each released version of a file receives a DOI, allowing for easy access to older versions. This ensures that all code executed with the data in our research environment can be reproduced at a later date and yield the same results. In JupyterHub, template notebooks with stubs to connect to DB Repo, TU-RDM, GAMS, and other resources are provided to facilitate this objective. DB Repo, a repository for databases that supports data evolution, citation, and versioning, is being developed by TU [dbrepo](https://www.ifs.tuwien.ac.at/infrastructures/dbrepo). The data of the bibliographic e-lautedb is mapped to a [GAMS](https://gams.uni-graz.at/context:gams) instance provided by ÖNB. There, a triple store enables the use of linked data to explore connections between original sources (stored in IIIF format in the ÖNB and other libraries), MEI files, audios, and TEIs. 
  
<img class="left" src="/assets/OeNB_workflow_TU_1.png"/>  

**ÖNB infrastructure:** The trajectory of a source (and its encoding) from its digitisation to its management and final delivery, consisting of the following components: (i) integration of facsimiles via IIIF; (ii) working git repository for all data; (iii) GAMS repository for published data; (iv) transformation to target formats (e.g., HTML, PDF) using XSLT

<img class="left" src="/assets/img/OeNB_Workflow_001.png"/>  
