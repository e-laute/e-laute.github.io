---
title: News
permalink: /news/
lang: en 
---
### NEWS

___
#### We present our work in summer 2024:

- **Stellenbosch, South Africa, 23.6.-28.6.2024**: [The 2024 IAML Congress](http://iaml2024.sun.ac.za/):  
   (David M. Weigl, Olja Januš, Reinier de Valk, Kateryna Schöning): 'Encoding strategies for notations combining text and music'
   
- **Lissabon, 26.6.-29.6.2024**: [Digital Technologies Applied to Music Research: Methodologies, Projects and Challenges](https://echoes.fcsh.unl.pt/conference-info/):  
    (Ilias Kyriazis): 'The E-LAUTE critical edition as open knowledge platform and semantic network';  
    (Olja Janjuš): 'Computational analysis of German lute tablature: The interplay of data representations and tools';  
    (Reinier de Valk): 'AbsoLutely Tabulous — A toolbox for computational processing and analysis of music in lute tablature'  

 
- **Granada, 6.7.-9.7.2024**: [MedRen: Medieval and Renaissance Music Conference](https://www.medren2024.com):  
    (David Weigl): 'Introduction. Interplay in the Corpora of German Lute Tablature'    
    (Silas Bischoff): 'German Lute Tablature - Truly a German invention or a souvenir from other music cultures?'  
    (Olja Janjuš): 'See the bigger picture? - Applying computational approaches to tablature data sets'  

___
#### Recently published or accepted for publication:  
- Kateryna Schöning, Reinier de Valk, David M. Weigl, Ilias Kyriazis, Olja Janjuš, Henning Burghoff und Christoph Steindl, 'A Collaborative Digital Edition of 15th- and 16th-Century German Lute Tablature: The E-LAUTE Project', in _Journal of New Music Research_ (accepted april 2024)


- Werner Goebl, David M Weigl, 'mei-friend: An Interactive Web-based Editor for Digital Music Encodings', in _Journal of Open Source Software_ 9/98 (2024)


- Tim Crawford, Reinier de Valk, David Lewis, Marc Lewon, Paul Overell, Kateryna Schöning, David Weigl, '_Ain schone kunstliche underweisung_: Modelling German lute tablature in MEI', 2023/9/12

  
- Andrea Puentes-Blanco, Metoda Kokole, Philippe Vendrix, María Gembero-Ustárroz, Rebecca Herissone, Christian Troelsgård, Klemen Grabnar, Birgit Lodes, Kateryna Schöning, Vilena Vrbanić, 'The monumental edition in the digital age: creating a sustainable future', in _Journal of New Music Research_ (accepted feb. 2023)

___
#### Our Workshops:

- **Munich, Ludwig-Maximilian-University & Bayerische Staatsbibiliothek,18.9.-20.9.2024**: E-LAUTE Workshop (intern; the agenda will be announced soon) 
  
- Basel, Schola Cantorum Basiliensis / FHNW Basel & Study Group Tablature in Western Music, International Musicology Society (IMS), 10.9.- 13.9.2025: E-LAUTE Workshop & IMS Tablature Group Conferece (public)     

___
#### What are we working on right now:
- We develop the **editorial platform E-LAUTE** (host Austrian National Library, =ÖNB), which first steps will be published in autumn 2024:
  
  
![](/assets/img/Ed_platform_001.png)
[](/assets/img/edition_1ex_001.png)

____
- **We are editing 1700 pages of tablature music**, searching for concordances and preparing synoptic views. Together with TabMEI Group and Laurent Pugin (Verovio) we are preparing the new version of MEI with lute tablatures (MEI 5.1.).
  
An example in mei-friend:  
![](/assets/img/Elslein_MEI-Friend_001.png)

An example on the ÖNB platform:     
![](/assets/img/Ed_ILT_MEI_001.png)  

____
- We have developed an internal **database (E-LAUTEdb)** for the material E-LAUTE and in particular for the historical-bibliographical cataloguing of model- and improvisation-based repertoire or fragments.
  
(1) We work on the source-original and uniform titles / text incipits, independent of the individual manuscripts or prints. So we are moving away from the concept of a "completed unique piece":
  
![](/assets/img/ELAUTEdb_1_002.png)    
(2) Then we incorporate the entries (text, images, music) into each individual manuscript or print under the categories mentioned here, i.a. we do a new indexing of the whole material. 
  
![](/assets/img/E-LAUTEdb_2_001.png)  

(3) And then we work on the indivudual entries (text, images, music) from the individual manuscript or print under the categories mentioned here, i.a. 'Concordances'.  

![](/assets/img/E-LAUTEdb_3_001.png)  

____
- We evelop and finalise our **editing / encoding workflows**.

Here is a simplified schematic overview of our encoding workflow, the way to MEI files, which we are editing and will soon make available to everyone: we entered music into Fronimo (tablature) and MuseScore (common music notation, =CMN), convert the files to MEI and finalise them using [_mei-friend_](https://mei-friend.github.io) (Werner Goebl, David M. Weigl) to all required files. As the diagram shows, we co-operate with other developers, e.g. [_Luteconv_](https://luteconv.mdw.ac.at) (Paul Overell, E-LAUTE team), and at the same time create our own tools (_TabMEI_transcriber_; _AbsoLutely Tabulous_) (both Reinier de Valk). 
  
![](/assets/img/Workflow_edition_01.png)      



Luteconv Converter:     
![](/assets/img/Luteconv_01.png)

AbsoLutely Tabulous:   

![](/assets/img/AbsoLutely_001.png)

____
- We discuss and finalise the joint **_Editorial Conventions_** for the literal transcription and the edition of the German, French and Italian lute tablature.  
Furthermore, we create literal transcriptions in a project-specific reduced variant of CMN that is in accordance with the tablature notation, consisting of one or two staves containing only stemless, black noteheads and rhythm flags (placed above the staff — as in the
tablature), in order to provide only pitch information (also automatically changeable) and avoid suggestions of duration and voice-leading (i.e., of polyphonic structure).  

![](/assets/img/iconic_MEI_ich_bin_ihr_001.png)  


____
- We are working on the **connection between MEI and TEI**:
   
![](/assets/img/Newsidler_Blatt_001.png)  

![](/assets/img/MEI_TEI_002.png)

____
- We develop and finalise **the infrastructure of the entire project**.
  
In the Git working environment (e.g., GitHub or GitLab), MEI files are produced by the E-Laute-Team using various technologies (Fronimo/Oxygen, AbsolutelyTabulous, mei-friend, etc.). Releases of these files are stored on the research data management system [TU-RDM](https://researchdata.tuwien.at/), which is based on InvenioRDM. The newest versions of these files are also stored on the GAMS infrastructure from ÖNB, where the digital edition is hosted. On the TU-RDM, each released version of a file receives a DOI, allowing for easy access to older versions. This ensures that all code executed with the data in our research environment can be reproduced at a later date and yield the same results. In JupyterHub, template notebooks with stubs to connect to DB Repo, TU-RDM, GAMS, and other resources are provided to facilitate this objective. DB Repo, a repository for databases that supports data evolution, citation, and versioning, is being developed by TU [dbrepo](https://www.ifs.tuwien.ac.at/infrastructures/dbrepo). The data of the bibliographic e-lautedb is mapped to a [GAMS](https://gams.uni-graz.at/context:gams) instance provided by ÖNB. There, a triple store enables the use of linked data to explore connections between original sources (stored in IIIF format in the ÖNB and other libraries), MEI files, audios, and TEIs. 
  
![](/assets/OeNB_workflow_TU_1.png)  

