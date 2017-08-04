# suitetgs

Terrassa Ground Station (UPC - ESEIAAT) script designed to control the next items in one place:
the different functional blocks (antenna controllers, radio, webcam).

  - Antenna Controller
  - Radio
  - WebCam
  - GPredict
  - GPredict Iterface

Please, refer to the program help menu in order to learn how to use it.

### Todos

1. long flags
2. Add dependecies managment
3. Cam streaming:
	* On server: cvlc -vvv v4l2:///dev/video0 --sout '#standard{access=http,mux=ogg,dst=*server-ip*:*server-port*}' 
	* On client: cvlc http://*server-ip*:*streaming-port*/

License
----
GPL
