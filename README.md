# e-scruti-box

## Inhalt und Purpose vom Projekt

Inhalte der E-Scruti-Box sollen neu angeordnet werden und ein neuer Schaum geschnitten werden. Alle bestehenden Inhalte der Scruti-Box werden konstruiert, um die im CAD anzuordnen.

Es wird eine neue 60V-Quelle entwickelt, die die alte ersetzen soll. Dazu gibt es auch ein neues Ladegerät bzw. Kaltgeräte-Stecker mit Transformator. Die müssen alle neu konstruiert und angeordnet werden.


## Creo und Konstruktion

### Hinweise für Creo

Es gibt einen eigenen PTC-Creo-Start-Links. Ist aus dem 3D-Druck-Projekt kopiert.

### Anpassungen an die Konstruktion

Ausschnitt für die Banana-Cable weiter nach links schieben.

Dadrüber ist dann Platz für die Eieruhr.

Ausschnitt für die beiden Messschieber größer machen.

Im der Main-Assembly "00_escruti_box_v1.asm" gibt es den Parameter "ABSTAND_ZUM_SCHAUM", mit dem die Komponenten eingebaut und ausgebaut werden können.

Probe kann in as Fach von den Messschiebern getan werden. Oder zum Zollstock.

Abmessungen vom Klemmbrett sind nur abgeschätzt, die müssen noch neu gemacht werden.


## Fehlende Modelle

Klemmbrett. Gehört zur Gruppe 05.

Korrekte Abmessungen der 04-Komponenten (Battery-Source, Ladegerät, Kaltgeräte-Stecker/Kabel)

Kabel, Messspitzen, Kelvin-Probe sind Gruppe 06


# Inhalte der Kiste und aktueller Status




Lfd. Nr. | Inhalt according google-sheets-Liste | Umsetzung / Status | Datei [*.prt]         | Kommentar
---------| ------------------------------------ | ------------------ | --------------------- | ----------------
-2       |                                      | Haupt-Modell       | 00_escruti_box_v1.asm | Main-Assembly
-1       |                                      | Haupt-Modell       | 01a_wuerth_box        | Vereinfachtes Modell der Wuerth-Box.
0        |                                      | Haupt-Modell       | 01b_schaum.prt        | Daran wird hauptsächlich gearbeitet. Soll am Ende exportiert und dann verwendet werden.
4        | Notizblock                           | Fertig             | 05_notizblock         | FSG-Standard-Notizblock
5        | 2 Stifte                             | Fertig             | 05_stift              | FSG-Standard-Kugelschreiber
6        | Zollstock                            | Fertig             | 03_zollstock          | 1m-Zollstock. Kunststoff.
9        | Feuerzeug                            | Fertig             | 07_feuerzeug          | 
11       | Messschieber (Metall)                | Fertig             | 03_messschieber_gross | 
12       | Messchieber (Kunststoff)             | Fertig             | 03_messchieber_klein  | 
13       | Insulated Test-Probe                 | Fertig             | 03_probe              | 
14       | IMD-Tester                           | Fertig             | 06_imd_tester         | 
15       | Eieruhr                              | Fertig             | 03_eieruhr            | 
16       | Kabel mit Bananensteckern (2 rot, 2 schwarz) | Fertig     | 06_bananenkabel       | Vereinfachtes Quader-Modell.
19       | Maßband                              | Fertig             | 03_massband           | 
20       | Metrahit                             | Fertig             | 02_metrahit           | 
21       | Taschenlampe                         | Fertig             | 07a_taschenlampe      | 
22       | Sekundenkleber                       | Fertig             | 07_sekundenkleber     | Ungefähre Abmessungen abgschätzt.
23       | UV Taschenlampe                      | Fertig             | 07b_uv_taschenlampe   | Als Vorlage wird die normale Taschenlampe genutzt.
1        | Klemmbrett                           | Fehlt              |                       | 
2        | ASF-Flow-Chart                       | Fehlt              |                       | 
3        | Scruti-Sheet                         | Fehlt              |                       | 
7        | Power Supply                         | Fehlt              |                       | 
8        | Kaltgerätestecker für PS             | Fehlt              |                       | 
10       | Messspitzen (1 rot, 1 schwarz)       | Fehlt              |                       | 
17       | Krokodil-Klemmen                     | Fehlt              |                       | 
18       | Kelvin-Probe                         | Fehlt              |                       | 


# Bauteil-Gruppen


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



# Hinweise

Bananenkabel sind nicht korrekt und im Detail konstruiert, es wird nur ein ungefährer Raum als Quader abgschätzt und verwendet.

05_notizblock.prt, 05_stift.prt | Schreibmaterial
06_bananenkabel.prt"
06_imd_tester.prt"
07_feuerzeug.prt, 07_sekundenkleber.prt, 07a_taschenlampe.prt, 07b_uv_taschenlampe.prt | Verschiedenes.



# Sonstiges

HTML-Tabelle mit Teilung


<table>
<tr><th>Name</th><th>Alter</th></tr>
<tr><td>Anna</td><td>25</td></tr>
<tr><td>Ben</td><td>30</td></tr>

<tr><td colspan="2"><hr></td></tr>

<tr><td>Carl</td><td>28</td></tr>
</table>

