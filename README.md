[POL]  Są to programy, stworzone w Node-RED służący do wizualizacji danych z czujników Ela Innovation odbieranych przez MQTT.
 
  -> temperatura - program dla czujnika Blue PUCK T EN12830, wyświetla wartości, takie jak nazwa czujnika, aktualna temperatura, sygnał RSSI oraz status połączenia z brokeram na prostej aplikacji dashboard. Wykorzystuje widgety takie jak tekst, wykres, miernik oraz wskaźnik LED do przedstawienia danych w czasie rzeczywistym.

  -> ruch i drgania - program dla czujnika Blue PUCK MOV, przyjmuje dane w obu trybach czujnika: MOV (stan ruchu oraz ilość poruszeń) i ANG (ruch w przestrzeni trójwymiarowej).
Program monitoruje i wyświetla nazwę czujnika, sygnał RSSI, ilość poruszeń oraz status ruchu (dla czujnika w trybie MOV) oraz ruchu czujnika w przestrzeni trójwymiarowej, określając kierunki w osiach x, y, z (dla czujnika w trybie ANG). Aplikacja dashboard wykorzystuje różne widgety do wizualizacji tych danych, takie jak tekst, wykres, miernik oraz wskaźnik LED, zapewniając użytkownikom dostęp do danych w czasie rzeczywistym.

 -> temperatura i wilgotność - program dla czujnika Blue PUCK RHT, wyświetla wartości, takie jak nazwa czujnika, aktualna temperatura i wilgotność, sygnał RSSI oraz status połączenia z brokeram na prostej aplikacji dashboard. Wykorzystuje widgety takie jak tekst, wykres, miernik oraz wskaźnik LED do przedstawienia danych w czasie rzeczywistym.


[ENG] These are programs created in Node-RED for visualizing data from Ela Innovation sensors received via MQTT.

  -> temperatura (temperature) - a program for the Blue PUCK T EN12830 sensor that displays values such as the sensor name, current temperature, RSSI signal, and connection status with the broker on a simple dashboard application. It uses widgets like text, chart, gauge, and LED indicator to present real-time data.

  -> ruch i drgania (motion and vibration) - a program for the Blue PUCK MOV sensor accepts data in both sensor modes: MOV (motion status and count of movements) and ANG (motion in three-dimensional space). The program monitors and displays the sensor name, RSSI signal, movement count, and motion status (for MOV mode), as well as sensor motion in three-dimensional space, determining directions in x, y, z axes (for ANG mode). The dashboard application utilizes various widgets to visualize this data, such as text, graphs, gauges, and LED indicators, providing users with real-time access to the data.

  -> temperatura i wilgotność (temperature and humidity) - a program for the Blue PUCK RHT sensor that displays values such as the sensor name, current temperature and humidity, RSSI signal, and connection status with the broker on a simple dashboard application. It uses widgets like text, chart, gauge, and LED indicator to present real-time data.
