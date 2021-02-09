
# **Progetto QGIS per USC2020**

Il progetto QGIS, realizzato su Qgis 3.10, comprende tutti gli Strati, Temi e Classi previsti dalla Specifica (fascicolo 3), ordinati nella Table of Content (TOC) nello stesso modo (Fig.1).

_Fig. 1 - La TOC del progetto è organizzata in Strati, Temi e Classi come la specifica (Fascicolo 3)_

I vari livelli (corrispondenti alle classi della specifica) sono contenuti in un unico file (USC2020.gpkg), insieme alle tabelle contenenti i domini degli attributi.

Il formato geopackage, standard OGC, è letto dalla maggior parte dei software GIS moderni.

E’ presente una tabella METADATI (senza geometrie) in cui devono essere memorizzate alcune informazioni (tipologia di variante, fase procedimentale, numero e data della delibera di approvazione/adozione, professionista incaricato,…), da compilarsi per la consegna (Fig. 2).

Per ogni classe è stata realizzata una apposita maschera che facilita l’inserimento dei dati e l’interrogazione (Fig.3).

La compilazione del campo ISTAT (richiesto ad ogni inserimento di geometrie) avviene automaticamente, ma occorre compilare preventivamente la variabile di progetto ‘ISTAT’.

Per fare questo, aprire il progetto, andare sul menu Progetto, selezionare Proprietà, e quindi Variabili. Si troverà la variabile ‘ISTAT’ il cui valore dovrà essere settato al codice ISTAT del Comune in esame (Fig. 4). In questo modo, la compilazione del campo ISTAT per tutte le classi avverrà automaticamente.

Si rammenta che le vestizioni grafiche sono puramente indicative e devono essere riviste in base alle specificità del territorio comunale e del progetto di piano, in modo da garantire la leggibilità delle tavole e l'immediata riconducibilità degli oggetti grafici alla corrispondente normativa di attuazione.

Anche l’ordine di sovrapposizione dei livelli segue l’articolazione delle classi in specifica, e non è funzionale alla rappresentazione cartografica per gli allestimenti delle tavole. In tal senso si consiglia di utilizzare il pannello “Ordine Layer” per personalizzare l’ordine dei livelli senza modificarne la disposizione nella TOC e  lo strumento “Gestisci Temi Mappa” per impostare le viste dei diversi elaborati di consegna (fascicolo 2) con specifici livelli visualizzati.

Si rimane a disposizione per eventuali necessità di chiarimenti sugli aspetti tecnico-operativi attraverso gli uffici dei settori regionali competenti.

Il progetto presenta, inoltre, già precaricati alcuni servizi di mappa (WMS e WFS) che possono essere di utilità. Ulteriori servizi, maggiori informazioni e, se presenti, i dati in scarico sono recuperabili dal Geoportale Piemonte.



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")


_Fig. 2 - Tabella metadati. Sostituire il contenuto con le informazioni relative ai file di consegna. Ad ogni fase procedimentale corrisponde una versione dei file di consegna, e quindi la tabella conterrà sempre un solo record (riga)._



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")




<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")


_Fig. 3 - Esempio di maschera per l’inserimento dei dati. Il tab “HELP” contiene indicazioni per la compilazione_



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")


_Fig. 4 - Impostazione della variabile di progetto “ISTAT”._


## 


## ELENCO SERVIZI PRECARICATI 

Sono qui elencati alcuni dati e servizi di mappa esposti tramite il GeoPortale Piemonte ([www.geoportale.piemonte.it](www.geoportale.piemonte.it)). L’elenco non è esaustivo, e si raccomanda di utilizzare il Geoportale, cercando nel catalogo le versioni più aggiornate delle informazioni di interesse.

Nell’elenco, il titolo è un link che porta direttamente al metadato corrispondente, l’url è quella da inserire nel software GIS utilizzato. 

Si prega di evitare di utilizzare i servizi WFS per visualizzare i dati su estensioni di territorio troppo grandi. 


<table>
  <tr>
   <td colspan="3" >
<h3>Allestimenti cartografici e dati di base</h3>


   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6686&currTab=rndt">PLANIMETRIA CATASTALE DI RIFERIMENTO REGIONALE</a></strong>
   </td>
   <td>https://wmscatasto-gis.csi.it/ms/wms_catasto?
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6686&currTab=rndt">PLANIMETRIA CATASTALE DI RIFERIMENTO REGIONALE</a></strong>
   </td>
   <td>https://wfscatasto-gis.csi.it/ms/wfs_catasto?
   </td>
   <td>wfs
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6686&currTab=rndt">PLANIMETRIA CATASTALE DI RIFERIMENTO REGIONALE</a></strong>
   </td>
   <td>https://vtcatasto-gis.csi.it/catasto/{z}/{x}/{y}.pbf
<p>
<em>[NB: Il formato VectorTile richiede Qgis 3.16] </em>
   </td>
   <td>vector tiles
   </td>
  </tr>
  <tr>
   <td colspan="3" ><em>La cartografia catastale può anche essere scaricata su taglio comunale accedendo a </em><a href="http://visregpga.territorio.csi.it/visregpga/?printEnabled=true&ricercaTopoEnabled=true&lang=it&topic=BDTRE&bgLayer=0&layers=Download_per_comune20180319132344034&X=5013275.00&Y=413698.50&zoom=7">http://visregpga.territorio.csi.it/visregpga/?printEnabled=true&ricercaTopoEnabled=true&lang=it&topic=BDTRE&bgLayer=0&layers=Download_per_comune20180319132344034&X=5013275.00&Y=413698.50&zoom=7</a>   \
<em>Occorre, sulla mappa che appare, cliccare sul comune di interesse e quindi, sul popup che si apre, selezionare l’url “mosaica</em>ti”.
   </td>
  </tr>
</table>



<table>
  <tr>
   <td colspan="3" >
<h3>Difesa del suolo/dissesto</h3>


   </td>
  </tr>
  <tr>
   <td>F<strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=5930&currTab=rndt">ASCE FLUVIALI - GEO-SERVIZIO WMS</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/vtdifsuolo/rp-01/fascpaiwms/wms_vtdifsuolo_fasce_fluviali?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=7062&currTab=rndt">AREE INONDABILI VIGENTI</a></strong> \

   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/vtdifsuolo/rp-01/disspaiwms/wms_vtdifsuolo_dissesti_pai?service=WMS&version=1.1.1&request=getCapabilities
<p>
<em>(il servizio contiene anche frane conoidi etc PAI)</em>
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=4500&currTab=rndt">AREE RME - GEO-SERVIZIO WMS</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/vtdifsuolo/rp-01/rmepaiwms/wms_vtdifsuolo_aree_rme?
   </td>
   <td>wms
   </td>
  </tr>
</table>





<table>
  <tr>
   <td colspan="3" >
<h3>Commercio</h3>


   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6633&currTab=rndt">AREE DI INSEDIAMENTO COMMERCIALE CONSOLIDATE (ADDENSAMENTI) O IN PROGRAMMAZIONE (LOCALIZZAZIONI)</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/geocomm/rp-01/geocommwms/wms_insediamento_comm?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6959&currTab=rndt">RETE DISTRIBUTIVA COMMERCIALE</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/geocomm/rp-01/geocommwms/wms_rete_distributiva?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
</table>



<table>
  <tr>
   <td colspan="3" >
<h3>Ambiente</h3>


   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=5731&currTab=rndt">AREE PROTETTE E RETE NATURA 2000</a></strong> \

   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/gsareprot/rp-01/areeprotwms/wms_gsareprot_1?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6022&currTab=rndt">MAPPATURE ACUSTICHE - ANNO 2012 - GEOSERVIZIO WMS</a></strong> 
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/siradec/rp-01/siradecwms/wms_rumore?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6471&currTab=rndt">STABILIMENTI SOGGETTI AD AUTORIZZAZIONE AMBIENTALE</a></strong>
   </td>
   <td>http://gisserver.territorio.csi.it/geoserver/decsiraogc_stabilimenti/wms?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=4449&currTab=rndt">ATTIVITÀ SOGGETTE A NORMATIVA SEVESO - ELEMENTI TERRITORIALI E AMBIENTALI VULNERABILI</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/arbo/rp-01/arbowmspub/wms_siar_compat_territ?
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6548&currTab=rndt">PUNTI DI SCARICO INDUSTRIALI</a></strong> <strong>e URBANI </strong>
   </td>
   <td>http://gisserver.territorio.csi.it/geoserver/decsiraogc_scarichi/wms?
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6513&currTab=rndt">IMPIANTI DI DEPURAZIONE DELLE ACQUE REFLUE URBANE</a></strong>
   </td>
   <td>http://gisserver.territorio.csi.it/geoserver/decsiraogc_stabilimenti/wms?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6980&currTab=rndt">IMPIANTI GESTIONE RIFIUTI - AUTORIZZATI CON AUA, PROCEDURA SEMPLIFICATA FUORI AUA , AIA, EX ART. 208 D.LGS 152/2006</a></strong>
   </td>
   <td>http://gisserver.territorio.csi.it/geoserver/decsiraogc_rifiuti_generici/wms?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6981&currTab=rndt">IMPIANTI RECUPERO E SMALTIMENTO RIFIUTI - AUTORIZZAZIONE INTEGRATA AMBIENTALE (AIA) O EX ART. 208 D.LGS 152/2006</a></strong>
   </td>
   <td>http://gisserver.territorio.csi.it/geoserver/decsiraogc_rifiuti_smaltimento/wms?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6565&currTab=rndt">IMPIANTI RECUPERO RIFIUTI - AUTORIZZATI CON A.U.A. O CON PROCEDURA SEMPLIFICATA (FUORI A.U.A.)</a></strong>
   </td>
   <td>http://gisserver.territorio.csi.it/geoserver/decsiraogc_rifiuti_aua/wms?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6978&currTab=rndt">IMPIANTI RIFIUTI DISCARICHE - AUTORIZZAZIONE INTEGRATA AMBIENTALE (AIA) O EX ART. 208 D.LGS 152/2006</a></strong>
   </td>
   <td>http://gisserver.territorio.csi.it/geoserver/decsiraogc_rifiuti_discarica/wms?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=7164&currTab=rndt">CENTRI DI RACCOLTA RIFIUTI – GEO-SERVIZIO WMS</a></strong>
   </td>
   <td>http://opengis.csi.it/ws/bdtre/rp-01/centriraccwms/wms_centriraccolta?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=2421&currTab=rndt">ANAGRAFE REGIONALE DEI SITI CONTAMINATI (ASCO)</a></strong>
   </td>
   <td>dati in scarico
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=3922&currTab=rndt">RETICOLO IDROGRAFICO AI SENSI DELLA DIRETTIVA EUROPEA SULLE ACQUE 2000/60/CE (WFD)</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/esiri/rp-01/siriogc/wms_corpi_idrici_wfd?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=7202&currTab=rndt">ELEMENTI DELLA RETE ECOLOGICA: CARTA DEGLI HABITAT, AREE DI VALORE ECOLOGICO (AVE) E AREE PRIORITARIE DELLA RETE ECOLOGICA IN PROVINCIA DI NOVARA</a></strong>
   </td>
   <td>dati in scarico
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6489&currTab=rndt">ELEMENTI DELLA RETE ECOLOGICA: CARTA DEGLI HABITAT E AREE DI VALORE ECOLOGICO (AVE) RELATIVA AL SITO UNESCO "I PAESAGGI VITIVINICOLI DEL PIEMONTE"</a></strong>
   </td>
   <td>dati in scarico
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=7224&currTab=rndt">ELEMENTI DELLA RETE ECOLOGICA: CARTA DEGLI HABITAT E AREE DI VALORE ECOLOGICO (AVE) RELATIVA AL TERRITORIO DELLA CITTÀ METROPOLITANA DI TORINO</a></strong>
   </td>
   <td>dati in scarico
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6599&currTab=rndt">ELEMENTI DELLA RETE ECOLOGICA: CARTA DELLA CONNETTIVITÀ ECOLOGICA (MODELLO FRAGM) RELATIVA AL SITO UNESCO "I PAESAGGI VITIVINICOLI DEL PIEMONTE"</a></strong>
   </td>
   <td>dati in scarico
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=7222&currTab=rndt">ELEMENTI DELLA RETE ECOLOGICA: CARTA DELLA CONNETTIVITÀ ECOLOGICA (MODELLO FRAGM) RELATIVA AL TERRITORIO DELLA CITTÀ METROPOLITANA DI TORINO</a></strong>
   </td>
   <td>dati in scarico
   </td>
  </tr>
</table>



<table>
  <tr>
   <td colspan="3" >
<h3>Suolo</h3>


   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=2684&currTab=rndt">CONSUMO DI SUOLO (AGGIORNAMENTI 2008-2013)</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/taims/rp-01/taimsbasewms/wms_cds?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6522&currTab=rndt">CARTA DEI SUOLI 1:50.000</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/agrigeo/rp-01/carsuowms/wms_carsuo?service=WMS&version=1.1.1&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=2416&currTab=rndt">ATLANTE DELLE ANALISI DEI TERRENI</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/agrigeo/rp-01/atlterwms/wms_atlter?service=WMS&version=1.3.0&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6999&currTab=rndt">ZONE VULNERABILI AI NITRATI DI ORIGINE AGRICOLA</a></strong> 
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/agrigeo/rp-01/zvnwms/wms_zvn?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
</table>



<table>
  <tr>
   <td colspan="3" >
<h3>Copertura forestale</h3>


   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6070&currTab=rndt">CARTA DEI PAESAGGI AGRARI E FORESTALI 1:250.000 GEO-SERVIZIO WMS</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/agrigeo/rp-01/carpaswms/wms_carpas?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6109&currTab=rndt">CARTA FORESTALE (EDIZIONE 2016)</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/sifor/rp-01/aggcartaforwms/wms_cartafor_2016?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=2496&currTab=rndt">CARTA FORESTALE E ALTRE COPERTURE DEL TERRITORIO (2000)</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/vtmonfor/rp-01/cartaforwms/wms_vtmonfor_cartafor?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6576&currTab=rndt">AREE A VOCAZIONE TARTUFIGENA</a></strong>
   </td>
   <td>[http://geomap.reteunitaria.piemonte.it/ws/sifor/rp-01/tartufiwms/wms_vocazione_tartufigena?service=WMS&version=1.3&request=getCapabilities]
   </td>
   <td>wms
   </td>
  </tr>
</table>


	


<table>
  <tr>
   <td colspan="3" >
<h3>Altro</h3>


   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=2493&currTab=rndt">INCENDI BOSCHIVI - AREE E PUNTI DI INNESCO</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/vtmonfor/rp-01/incendiwms/wms_vtmonfor_incendi_boschivi?service=WMS&version=1.1.1&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=2499&currTab=rndt">RETE SENTIERISTICA DELLA REGIONE PIEMONTE</a></strong>
   </td>
   <td>http://geomap.reteunitaria.piemonte.it/ws/vtmonfor/rp-01/sentieriwms/wms_vtmonfor_sentieri?service=WMS&version=1.3&request=getCapabilities
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=7235&currTab=rndt">RETE ESCURSIONISTICA REGIONALE (ITINERARI)</a></strong>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=2751&currTab=rndt">AREE SCOLASTICHE - EDIFICI SCOLASTICI</a></strong>
   </td>
   <td>http://osgis2.csi.it/qgs/Scuole/BDTRE_SCUOLE_pubblicazione?
   </td>
   <td>wms
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=7123&currTab=rndt">RETE CICLABILE DI INTERESSE REGIONALE</a></strong> 
   </td>
   <td>dati in scarico
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=7200&currTab=rndt">TRAFFICO GIORNALIERO MEDIO 2019 SU ELEMENTO STRADALE BDTRE</a></strong> 
<p>
<em>(disponibile anche per anni precedenti)</em>
   </td>
   <td>dati in scarico
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong><a href="http://www.geoportale.piemonte.it/geonetworkrp/srv/ita/metadata.show?id=6689&currTab=rndt">VALORI ECONOMICI IMMOBILIARI (OMI 2016) E POPOLAZIONE RESIDENTE (CENSIMENTO 2011) DELLA CLASSE EDIFICIO DELLA BDTRE</a></strong>
   </td>
   <td>dati in scarico
   </td>
  </tr>
</table>
