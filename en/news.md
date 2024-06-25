---
title: News
permalink: /news/
lang: en 
---
### NEWS

___
#### We present our work in summer 2024:

- **Stellenbosch, South Africa, 23.6.-28.6.2024**: [The 2024 IAML Congress](https://www.iaml.info/congresses/2024-stellenbosch):  
   (Kevin Page, David Lewis, David Weigl): 'Annotating digital music notation: past, present and future approaches'    

   
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
- We develop the editorial platform E-LAUTE (host ÖNB):
![](/assets/img/E-LAUTEdb_2exampl_01.png)

___
- We have developed an internal database (E-LAUTEdb) for the material E-LAUTE and in particular for the historical-bibliographical cataloguing of model- and improvisation-based repertoire or fragments.
  
(1) We are working on the source-original and uniform titles / text incipits, independent of the individual manuscripts or prints;
  
![](/assets/img/ELAUTEdb_1_001.png)
(2) then we incorporate the entries (text, images, music) into each individual manuscript or print under the categories mentioned here, i.a. we do a new indexing of the whole material; 
  
![](/assets/img/E-LAUTEdb_2_001.png)
(3) and then we work on the indivudual entries (text, images, music) from the individual manuscript or print under the categories mentioned here, i.a. 'Concordances'.  

![](/assets/img/E-LAUTEdb_3_001.png)

___
- We develop and finalise the infrastructure of the entire project.
  
In the Git working environment (e.g., GitHub or GitLab), MEI files are produced by the E-Laute-Team using various technologies (Fronimo/Oxygen, AbsolutelyTabulous, mei-friend, etc.). Releases of these files are stored on the research data management system [TU-RDM](https://researchdata.tuwien.at/), which is based on InvenioRDM. The newest versions of these files are also stored on the GAMS infrastructure from ÖNB, where the digital edition is hosted. On the TU-RDM, each released version of a file receives a DOI, allowing for easy access to older versions. This ensures that all code executed with the data in our research environment can be reproduced at a later date and yield the same results. In JupyterHub, template notebooks with stubs to connect to DB Repo, TU-RDM, GAMS, and other resources are provided to facilitate this objective. DB Repo, a repository for databases that supports data evolution, citation, and versioning, is being developed by TU [dbrepo](https://www.ifs.tuwien.ac.at/infrastructures/dbrepo). The data of the bibliographic e-lautedb is mapped to a [GAMS](https://gams.uni-graz.at/context:gams) instance provided by ÖNB. There, a triple store enables the use of linked data to explore connections between original sources (stored in IIIF format in the ÖNB and other libraries), MEI files, audios, and TEIs. 
  
![](/assets/OeNB_workflow_TU_1.png)  

___
- We evelop and finalise our editing / encoding workflows.

Here is a simplified schematic overview of our encoding workflow, the way to MEI files, which we are editing and will soon make available to everyone: we entered music into Fronimo (tablature) and MuseScore (CMN), convert the files to MEI and finalise them using mei-friend to all required files. As the diagram shows, we co-operate with other developers, e.g. Luteconve, and at the same time create our own tools (TabMEI_transcirber). 
  
![](/assets/img/Workflow_edition_01.png)  
<div class="acks"></div>



![](/assets/img/Luteconv_01.png)


