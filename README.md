Automatische Kreisel-Erkennung in SwissImage-Daten



Dieses Projekt automatisiert die Detektion von Kreisverkehrsanlagen (Kreiseln) in hochauflösenden SwissImage-Luftbildern (0.1 m) mittels YOLO und SAHI. Ziel ist eine End-to-End-Pipeline, die Rohbilder und Geodaten aufbereitet, ein Modell trainiert und große Bilddateien in Slices analysiert, um die Positionen der Kreisel in LV95-Koordinaten auszugeben. Hintergrundkacheln (Negative Samples) werden gezielt erzeugt, um False Positives zu minimieren.



Der Datensatz umfasst aktuell 42'639 Kacheln, darunter 2'279 mit existierenden Kreiseln. Die Modellleistung wird über mAP und einen Confidence Score gemessen. Visualisierungen der Slices ermöglichen eine schnelle Kontrolle der Datensatzqualität und der Detektionsergebnisse. Die Methoden aus Deep Learning und Computer Vision werden auf Schweizer Luftbilder anwendet.



Kontakt: markus.geiser@stud.hslu.ch

