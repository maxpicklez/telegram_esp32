[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3JUUFBA5MUU4Q)


# Introduction - Introduzione
***ENG***

I devised this project to create a smart security system, without the need for external input devices, such as a numeric keypad for alarm activation, etc.
In fact, the project allows you to manage the esp32 directly from your mobile phone or PC via a telegram bot.

Credits:

To create the project I took inspiration from other projects on the net, such as the following:
https://randomnerdtutorials.com/esp32-cam-take-photo-save-microsd-card/

***ITA***

Ho ideato questo progetto per creare un sistema di sicurezza smart, senza il bisogno di dispositivi esterni per l’input, come ad esempio un tastierino numerico per l’attivazione dell’allarme, ecc.
Il progetto infatti consente di gestire il l’esp32 direttamente dal cellulare o da pc tramite un bot telegram.

Credits:

Per creare il progetto ho preso spunto da altri progetti in rete, come ad esempio il seguente:
https://randomnerdtutorials.com/esp32-cam-take-photo-save-microsd-card/

# Components - Componenti
***ENG***

- ESP32 cam
- PIR
- connection cable

I bought this kit from Amazon: https://www.amazon.it/ideaspark-ESP32-CAM-Istantanea-Riconoscimento-Telecamera/dp/B084H5XNGQ/ref=sr_1_11?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=esp32+kit&qid=1614103288&sr=8-11

The kit already contains the USB2.0 serial cable from USB to TTL PL2303TA needed to program the esp32.

***ITA***

- ESP32 cam
- PIR
- cavo di collegamento

Io ho comprato questo kit da Amazon: https://www.amazon.it/ideaspark-ESP32-CAM-Istantanea-Riconoscimento-Telecamera/dp/B084H5XNGQ/ref=sr_1_11?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=esp32+kit&qid=1614103288&sr=8-11

Il kit contiene già il Cavo USB2.0 seriale da USB a TTL PL2303TA necessario per programmare l'esp32.

# Apps and services

- Arduino ide
- Telegram

# Connection schema - Schema di collegamento
![1](https://user-images.githubusercontent.com/63566699/108887900-18ef8400-760b-11eb-9577-83126cc5da7d.jpg)

![2](https://user-images.githubusercontent.com/63566699/108887553-b4342980-760a-11eb-8a69-92edea0f714c.jpg)

![3](https://user-images.githubusercontent.com/63566699/108887580-bdbd9180-760a-11eb-96de-6bd276b4032f.jpg)

# About the project

***ITA***

Questo semplice sistema di sorveglianza domestico ti consente di ricevere una fotografia su telegram non appena viene rilevato un movimento tramite il sensore PIR, di richiedere all’esp32 una foto istantanea, accendere o spegnere il led integrato sull’esp o di armare e disarmare il sensore PIR. Il tutto tramite dei semplici comandi del bot telegram.
Per la creazione del bot telegram ci sono molte guide online che spiegano come crearlo partendo dal botFather.

***ENG***

This simple home surveillance system allows you to receive a photo on telegram when movement is detected via the PIR sensor, to request an instant photo from the esp32, turn on or off the integrated led on the esp or to arm and disarm the PIR sensor. . All through simple commands of the telegram bot.
For the creation of the telegram bot there are many online guides that explain how to create it starting from the botFather.

![5](https://user-images.githubusercontent.com/63566699/108888560-ea25dd80-760b-11eb-9450-694296854e3f.jpg)

![6](https://user-images.githubusercontent.com/63566699/108888598-f27e1880-760b-11eb-8278-3d2be828c591.jpg)

![7](https://user-images.githubusercontent.com/63566699/108888642-f90c9000-760b-11eb-9130-702b6cecd27a.jpg)

# Arduino Ide configuration
![Screenshot (2)](https://user-images.githubusercontent.com/63566699/109691949-3fbc3600-7b88-11eb-808d-0f3ad156f9c9.png)


# Code

https://github.com/albino98/telegram_esp32/blob/main/telegram_esp32.ino

# Donations
If you liked the project, offer me a coffee!

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3JUUFBA5MUU4Q)

# License

https://github.com/albino98/telegram_esp32/blob/5c9600ddb2f9e9213a218b34de959ea35fd503c8/LICENSE
