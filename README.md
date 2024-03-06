<h1>SuperScan</h1>

<h2>Descripción</h2>

<p>Este script en bash, llamado SuperScan, te permite realizar un escaneo completo de puertos en un host específico. Desarrollado por skipy95d, este script utiliza herramientas como nmap, whatweb, y openssl para obtener información detallada sobre los servicios y puertos abiertos en el host.</p>

<h2>Requisitos</h2>

<p>Asegúrate de tener instalado el comando <code>figlet</code>. Si no lo tienes, puedes instalarlo ejecutando:</p>

<pre><code>sudo apt-get install -y figlet
</code></pre>

<h2>Uso</h2>

<ol>
  <li>Ejecuta el script con el siguiente comando:</li>

    ./superscan.sh

  <li>Ingresa la dirección IP del host que deseas escanear cuando se te solicite.</li>
  <li>El script creará una carpeta con el nombre del host y generará un archivo llamado <code>resultado_escaneo.txt</code> con la información recopilada.</li>
  <li>¡Listo! Puedes revisar los resultados en la carpeta generada.</li>
</ol>

<h2>Funcionalidades</h2>

<ul>
  <li>Escaneo de puertos con nmap.</li>
  <li>Verificación de puertos 80 y 443 abiertos.</li>
  <li>Ejecución de whatweb para obtener información adicional si los puertos 80 o 443 están abiertos.</li>
  <li>Comandos openssl para puertos 80 y 443 si están abiertos.</li>
  <li>Escaneo de puertos 445 con scripts de nmap para servicios SMB.</li>
  <li>Escaneo de puertos 23 con nmap y scripts para servicios Telnet.</li>
</ul>

<ul>
  <li>Este script asume que estás ejecutándolo en un entorno Linux.</li>
  <li>Asegúrate de tener permisos de ejecución para el script (<code>chmod +x superscan.sh</code>).</li>
</ul>
