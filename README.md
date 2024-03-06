# SuperScan
Escaneo automatizado de hosts que utiliza nmap, whatweb y openssl.

Uso
Ejecuta el script con el siguiente comando:
   
    ./superscan.sh
Ingresa la dirección IP del host que deseas escanear cuando se te solicite.

El script creará una carpeta con el nombre del host y generará un archivo llamado resultado_escaneo.txt con la información recopilada.

¡Listo! Puedes revisar los resultados en la carpeta generada.

Funcionalidades

Escaneo de puertos con nmap.

Verificación de puertos 80 y 443 abiertos.
Ejecución de whatweb para obtener información adicional si los puertos 80 o 443 están abiertos.
Comandos openssl para puertos 80 y 443 si están abiertos.
Escaneo de puertos 445 con scripts de nmap para servicios SMB.
Escaneo de puertos 23 con nmap y scripts para servicios Telnet.
Notas
Este script asume que estás ejecutándolo en un entorno Linux.
Asegúrate de tener permisos de ejecución para el script (chmod +x superscan.sh).
