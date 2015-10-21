# sliderHtml_with_littleBits

1/ pusher les données d'un dimmer slider littleBits sur le port série via l'arduino  http://www.instructables.com/id/littleBits-Serial-Data/?ALLSTEPS

2/ installer https://github.com/johnlauer/serial-port-json-server et le lancer serialport-server /dev/tty.usbmodem1411 -hp 8783 -wp 8784 -sp 8785 (attention les valeurs pour les paramètres hp wp et sp sont ici utilisées à titre d'exemple, ne pas hésitez à lire la documentation de l'outil) 

3/ télécharger le fichier test.html et le lancer dans son navigateur
