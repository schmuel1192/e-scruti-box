# e-scruti-box

## Inhalt und Purpose vom Projekt

Inhalte der E-Scruti-Box sollen neu angeordnet werden und ein neuer Schaum geschnitten werden.

Es wird eine neue 60V-Quelle entwickelt, die die alte ersetzen soll. Dazu gibt es auch ein neues Ladegerät bzw. Kaltgeräte-Stecker mit Transformator. Die müssen alle neu konstruiert und angeordnet werden.

##  Vorgehen

Alle bestehenden Inhalte der Scruti-Box werden konstruiert, um die im CAD anzuordnen.

## Anpassungen an die Konstruktion

Ausschnitt für die Banana-Cable weiter nach links schieben.

Dadrüber ist dann Platz für die Eieruhr.

Ausschnitt für die beiden Messschieber größer machen.

Es gibt einen eigenen PTC-Creo-Start-Links. Ist aus dem 3D-Druck-Projekt kopiert.

## Fehlende Modelle

Klemmbrett. Gehört zur Gruppe 05.

## Übersicht der Dateien. Aufbau und Struktur


Datei | Inhalt / Kommentar
 ------------ | ------------- 
Content from cell 1 | Content from cell 2 
Content in the first column | content in the second column
00_escruti_box_v1.asm, 00_escruti_box_v1.stp | Haupt-Modell, Assembly
01a_wuerth_box.prt | Vereinfachtes Modell der Wuerth-Box
01b_schaum.prt | Schaum. Daran wird hauptsächlich gearbeitet. Soll am Ende exportiert und dann verwendet werden.
02_metrahit | Vereinfachtes Modell vom Metrahit
03_massband.prt, 03_messchieber_klein.prt, 03_messschieber_gross.prt | "Mechanische" Messmittel
05_notizblock.prt, 05_stift.prt | Schreibmaterial.
04_60v_assembly.asm, 04_60v_body_0.prt, 04_60v_koerper_40.prt, 04_60v_koerper_3472.prt, 04_ladegeraet_60v_v1.prt, 04_ladegeraet_60v_v1_kabel.prt | Alle Dateien fuer die 60V-Quelle. Werden durch ein vereinfachtes Modell, "dummy" ersetzt.
60v_quelle_dummy.prt | Dummy-Modell für die 60V-Quelle. Muss noch umbenannt und dann die Abmessungen angepasst werden.
------------ | ------------- 
60v_quelle_dummy.prt | Dummy-für die 60V-Quelle
bananenkabel.prt, eieruhr.prt, escruti_box_v1.stp, feuerzeug.prt,imd_tester.prt, probe.prt, sekundenkleber.prt, taschenlampe.prt | Modell müssen noch umbenannt werden.