# amm-22-gst-shootingstars_team
amm-22-gst-shootingstars_team created by GitHub Classroom



Gstreamer se debe introducir la siguiente línea en la terminal.

gst-launch-1.0 filesrc location="video.ogv" ! oggdemux ! theoradec ! videoconvert ! videobalance saturation=0.0 ! textoverlay font-desc="Sans bold 30" text="Video en blanco y negro" color=4294967040 ! queue ! theoraenc ! m. oggmux name=m ! queue ! tcpserversink host=127.0.0.1 port=9090


Una vez iniciado el pipeline hay que darle al botón de Gstreamer de la página multimedia, y se podrá ver el video en blanco y negro además de un texto superpuesto.
En cambio si se le pulsa a video original, la página mostrará el video sin ningún cambio.
Participantes:
 
- Alicia Antón Rivas --> 100429271
- Paula Gallejones López --> 100429182
- Irene Torres Gámez --> 100429210
- Ignacio Moreno Mulet --> 100383694
