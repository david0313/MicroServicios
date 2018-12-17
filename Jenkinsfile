#!groovy

node {

stage 'Compilar'

FICHERO="*.xml"
NOMBRE="${*%.*}"
EXTENSION="${FICHERO##*.}"

echo $NOMBRE
echo $EXTENSION


stage 'test'

sh'cd /
cd /home/david/Música/SoapUI-5.2.1-linux-bin/SoapUI-5.2.1/bin/
./testrunner.sh -r /home/david/Escritorio/MIcroservicios/SoapUI_CEM_20181205/01-MS-Registro_Jugador/02-Pruebas/PlayerRegistration-soapui-project.xml
'

}


