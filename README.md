# Bachelorprojekt
Bachelorthema ist Entwicklung einer autarken Wetterstation mit LoRaWAN, MQTT und Datenvisualisierung.

Abstract:
Diese Bachelorarbeit beschäftigt sich mit der Entwicklung einer autarken Wetterstation, die me
teorologische Daten wie Temperatur, Luftfeuchtigkeit und Luftdruck erfasst und über große Ent
fernungen mittels LoRaWAN und MQTT überträgt. Die Wetterstation ist so konzipiert, dass sie 
in abgelegenen Regionen mit begrenzter Infrastruktur eingesetzt werden kann. Die Energiever
sorgung erfolgt durch eine Solarzelle und eine Lithium-Ionen-Batterie, wodurch ein längerer au
tarker Betrieb gewährleistet wird. Die erfassten Daten werden auf einem Raspberry Pi-basierten 
Server gespeichert und mithilfe von InfluxDB und Grafana visualisiert. Die Arbeit umfasst die 
Auswahl geeigneter Hardwarekomponenten, die Implementierung der Software sowie die Ana
lyse der Energieeffizienz und der Zuverlässigkeit der Datenübertragung. Die Ergebnisse zeigen, 
dass das System in der Lage ist, Wetterdaten zuverlässig zu erfassen und zu übertragen, wobei 
die Autarkie durch den Einsatz von Solarenergie und optimierte Energiesparmodi erreicht wird. 
Zukünftige Arbeiten könnten sich auf die weitere Optimierung des Energieverbrauchs und die 
Erweiterung des Systems um zusätzliche Sensoren konzentrieren. 

Hinweis:
Für die Implementierung des Deep-Sleep-Modus wurde der Code aus dem Repository ESP32-LMIC-DeepSleep-example von JackGruber als Grundlage verwendet und weiterentwickelt.
https://github.com/JackGruber/ESP32-LMIC-DeepSleep-example/blob/master/src/main.cpp

Hardware:
![image](https://github.com/user-attachments/assets/3c95c783-46a7-4c8b-aa4f-fef518ef0c66)


Software Architektur der Raspberrypi-Server:
![image](https://github.com/user-attachments/assets/4896970a-4bcb-4320-bfc8-32777b3086ac)
