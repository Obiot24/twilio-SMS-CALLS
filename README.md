# twilio-SMS-CALLS
Uso basico de twilio atravez de node js.

Instalacion 

1.npm install

Configuracion

1. Crear una cuenta en https://www.twilio.com/
2. Cambiar el ACCOUNT SID y el AUTH TOKEN
 en var client = new twilio.RestClient('{ACCOUNT SID}', '{AUTH TOKEN}');
3.lanzar el servidor node app
________________________________________________________________________

Mensaje de texto SMS

http://localhost:8080/sms
parametros post num = numero , msg = mensaje

Hacer una llamada enviando solo texto

http://localhost:8080/call
parametros post num = numero , msg = mensaje

opcionales en la llamada 
https://www.twilio.com/docs/api/twiml/say
