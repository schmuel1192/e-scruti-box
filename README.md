# e-scruti-box

## Inhalt und Purpose vom Projekt

Für die E-Scruti-Boxen soll ein neuer Schaum geschnitten werden, in dem alle Messmitel sicher verwahrt werden. Dafür wurden die Box selbst und alle Inhalte in Creo konstruiert und positioniert.

Zusätzlich gibt es eine neue 60V-Quelle, die von Grund auf neu designt und konstruiert wurde. Das git zur 60V-Quelle ist: https://github.com/daniw/bat_source. Dazu gibt es auch ein Ladegerät bzw. Kaltgeräte-Stecker mit Kabel und Transformator, die ebenfalls untergebracht werden müssen.



## Creo und Konstruktion

### Hinweise für Creo

Es gibt einen eigenen PTC-Creo-Start-Link. Ist aus dem 3D-Druck-Projekt kopiert. Verknüpfung verweist dann auf den Ordner mit config- und search-Datei.

In der search-Datei wird nur zusätzlich der Pfad zum Ordner mit der 60V-Quelle referenziert.

### Anpassungen an die Konstruktion

In der Main-Assembly "00_escruti_box_v1.asm" gibt es den Parameter "ABSTAND_ZUM_SCHAUM", mit dem die Komponenten eingebaut und ausgebaut werden können.

Wert kann geändert werden über "Tools --> Parameters" und dann in der Tabelle ein neuer Wert eingegeben werden. Danach mus mit Strg+G die Darstellung neu geladen werden.


  


## 60V-Quelle

Im CAD der 60V-Quelle gibt es einen step-Export "00_01_mechanical_assembly_red_asm.stp", der hier genutzt wird. Besteht nur aus Gehäuse und Deckel, um die äußeren Abmessungen zu haben.


Mit Dani klären, wie genau denn eigentlich das Ladegerät aussieht und ob das auch noch Platz finden muss.



## Bauteil-Gruppen


Nummer | Baugruppe      
-------| ------------------------------
00     | Main-Assembly
01     | Kiste und Schaum
02     | Metrahit
03     | Analoge/Mechanische Messmittel
04     | 60V-Quelle und Zubehör
05     | Schreibmaterial
06     | Teile und Zubehör zum Strom-Messen
07     | Verschiedenes



## Inhalte der Kiste und aktueller Status




Lfd. Nr. | Inhalt according google-sheets-Liste         | Datei [*.prt / *.asm]                 | Kommentar
---------| -------------------------------------------- | ------------------------------------- | ----------------
-2       |                                              | 00_escruti_box_v1.asm                 | Haupt-Modell. Main-Assembly
-1       |                                              | 01a_wuerth_box                        | Haupt-Modell. Vereinfachtes Modell der Wuerth-Box.
0        |                                              | 01b_schaum.prt                        | Haupt-Modell. Daran wird hauptsächlich gearbeitet. Soll am Ende exportiert und dann verwendet werden.
2        | ASF-Flow-Chart                               | 05_ASF_flow_chart                     | 
3        | Scruti-Sheet                                 | 05_scruti_sheet                       | 
4        | Notizblock                                   | 05_notizblock                         | FSG-Standard-Notizblock
5        | 2 Stifte                                     | 05_stift                              | FSG-Standard-Kugelschreiber
6        | Zollstock                                    | 03_zollstock                          | 1m-Zollstock. Kunststoff.
9        | Feuerzeug                                    | 07_feuerzeug                          | 
11       | Messschieber (Metall)                        | 03_messschieber_gross                 | 
12       | Messchieber (Kunststoff)                     | 03_messchieber_klein                  | 
13       | Insulated Test-Probe                         | 03_probe                              | 
14       | IMD-Tester                                   | 06_01_imd_tester                      | 
16       | Kabel mit Bananensteckern (2 rot, 2 schwarz) | 06_02_bananenkabel                    | Vereinfachtes Quader-Modell mit räumlichen Abschätzungen.
18       | Kelvin-Probe                                 | 06_03_kelvin_probe                    | 
17       | Krokodil-Klemme                              | 06_04_krokoklemme                     | Online-Modell, leicht angepasst.
10       | Messspitzen (1 rot, 1 schwarz)               | 06_05_messspitze                      | Zwei identische Modelle, Unterschied ist nur die Farbe.
15       | Eieruhr                                      | 03_eieruhr                            | 
19       | Maßband                                      | 03_massband                           | 
20       | Metrahit                                     | 02_metrahit                           | 
21       | Taschenlampe                                 | 07a_taschenlampe                      | 
22       | Sekundenkleber                               | 07_sekundenkleber                     | Ungefähre Abmessungen abgeschätzt.
23       | UV Taschenlampe                              | 07b_uv_taschenlampe                   | Als Vorlage wird die normale Taschenlampe genutzt.
1        | Klemmbrett                                   | 05_klemmbrett                         | Hat keinen designierten Platz, wird mit Scruti-Sheet und ASF-Flow-Chart einfach nur oben aufgelegt.
7        | Power Supply / 60V-Quelle                    | 00_01_mechanical_assembly_red_asm.stp | Vereinfachtes Modell der 60V-Quelle. (04_60V_bat_source)
8        | Kaltgerätestecker für PS                     | 04_03_60v_ladekabel.asm               | Eigene Baugruppe aus Kabel und zwei Steckern. Muss im search-Datei mit angegeben werden.






## Hinweise

* Bananenkabel sind nicht korrekt und im Detail konstruiert, es wird nur ein ungefährer Raum als Quader abgeschätzt und verwendet.

* Ausgewählter Kaltgeräte-Stecker für die 60V-Quelle ist Typ C13 (female). Nicht sicher, ob das der richtige ist, aber Dimension sollte passen.


* Anmerkungen zur Krokodil-Klemme und Kelvin-Probe

  * Kelvin-Probe und Krokodil-Klemme haben ein eigenes Kabel hinten dran. Das muss in dem Fach auch noch Platz finden. Ist im Modell nicht berücksichtigt.
  
  
  * Krokodil-Klemme, Abmessungen. Runtergeladenes Modell etwas angepasst und kürzer gemacht. Stimmt immer noch nicht, ist aber besser als die DIY-Variante.


   Maß    | Soll (scruti-box) | Ist (Modell) | Ist (skaliert)
   -------| ------------------| -----------------------------
   Länge  | 91                | 179          | 139
   Breite | 15                | 19           | 19
   Höhe   | 40                | 49           | 49

  



## Sonstiges

HTML-Tabelle mit Teilung


<table>
<tr><th>Name</th><th>Alter</th></tr>
<tr><td>Anna</td><td>25</td></tr>
<tr><td>Ben</td><td>30</td></tr>

<tr><td colspan="2"><hr></td></tr>

<tr><td>Carl</td><td>28</td></tr>
</table>

