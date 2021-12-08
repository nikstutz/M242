# M242

Hier ist die Dokumentation zum Modul 242 der Gruppe 3 (Zellweger, Docampo, Lippuner)

# Inhalt

* [Lernumgebung](https://github.com/SayHeyD/M242/tree/main/Lernumgebung)
* [Cloud](https://github.com/SayHeyD/M242/tree/main/Cloud)
* [IoTKitV3](https://github.com/SayHeyD/M242/tree/main/IoTKitv3)
* [Load Balancer](https://github.com/SayHeyD/M242/tree/main/Load%20Balancer)
* [Selbst aufsetzen](https://github.com/SayHeyD/M242/tree/main/Projekt%20selbst%20aufsetzen)

# Wissenstand (K2)
Ich hatte in der Schule bereits ein Modul in welchem ich einen Raspberry Pi verwendet habe. Dort haben ich bereits ein kleines Projekt mit einem RFID-Scanner umgesetzt, jedoch war dies im ersten Lehrjahr und ich habe nicht mehr viel in Erinnerung behalten. Ansonsten hatte ich was IoT, Sensoren und Aktoren angeht wenig Wissen. Allerdings bin ich wenn es um Services geht besser aufgestellt, da ich in der Freizeit selber gerne Web-Services entwickle und mich mit dem Thema beschäftige. Ebenfalls habe ich auch schon öfters in Modulen in denen es Möglichg war Web-services entwickelt und, oder konzipiert da mich diese Thema sehr stark interessiert.


# Wichtige Lernschritte (K6)

Ich habe am meisten beim Programmieren der Applikation für den Mikroprozessor gelernt. Da ich nur Erfahrung in C# hatte und mir C++ erst einaml für ein paar Stunden angeschaut hatte, konnte ich in diesem Modul mein Wissen was C++ betrifft vertiefen. Das was mich am meisten überrascht hat, aber im Nachinein natürlich völlig logisch ist, ist, dass ich das Zertifikat für einen HTTPS Request dem Mikroprozessor übergeben muss, da dieser wie die meisten Betriebssysteme keinen Vorinstallierten Zertifikatsspeicher hat. Ebenfalls konnte ich noch nie einen Load-Balancer konfigurieren und habe somit auch damit in diesem Modul meine ersten Erfahrungen damit gemacht.


# Reflexion (K6)

Ich fand es spannend mal mit solche einem Board zu arbeiten. Werde definitif in Zukunft etwas mehr mit IOT Geräten arbeiten bzw. dieses im Hinterkopf behalten jedoch aktuell eher im Privatem rahmen. Ich denke, ich bin allgemein gut mit meinen Arbeiten für das Modul vorangekommen, hätte aber wahrscheinlich etwas früher die Bewertungskriterien anschauen sollen
Ich konnte einiges neues in diesem Modul lernen.


# Unser Service (K5)

Wir haben uns dafür entschieden einen Temperatur-Alarm mit dem IoT-Board umzusetzen. Das bedeutet, dass wir die Temperatur mittels des Sensors auf dem Board lesen und dann per REST API an eine Web-App übermitteln wollen.

Die Web-App ist für das logging der Einträge verantwortlich. Ausserdem kann über die Web-App ein Temperaturberich festgelegt werden. Bei allen Temperaturen, die ausserhalb dieses Bereiches liegen, wird "Alarm" geschalgen.

Der Alarm, zeigt sich ersten indem die Temperaturanzeige in der Web-App Rot angezegit wird und zweitens auf dem Board ein entsprechendes LED eingeschaltet wird. Ebenfalls wird auch auf dem OLED-Display eine NAchricht ausgegeben die zeigt, was der Feherl nun genau bedeutet.

Weitere Informationen zu den Error-States finden Sie [hier](https://github.com/SayHeyD/M242/tree/main/IoTKitv3#Error-States).


