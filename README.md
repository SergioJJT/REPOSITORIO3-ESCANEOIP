# 🛠 Network Scanner - Escaneo de IPs y Puertos en la Red  

Este script en **Bash** permite detectar dispositivos activos en una red local, escanear puertos abiertos y generar un informe con la información obtenida.  

## 📌 Características  

✅ **Detección de direcciones IP activas** en la red local mediante `ping`.  
✅ **Identificación del sistema operativo** en el que se ejecuta el script.  
✅ **Escaneo de puertos abiertos** en dispositivos detectados.  
✅ **Generación automática de un informe** con los resultados.  

## 🚀 Instalación y Uso  

1️⃣ Clona este repositorio o descarga el script:  

```bash
git clone https://github.com/tuusuario/network-scanner.git
cd network-scanner

2️⃣ Asigna permisos de ejecución al script:

```bash
chmod +x scanner.sh

3️⃣ Ejecuta el script en una terminal:

```bash
./scanner.sh

4️⃣ Sigue las instrucciones ingresando los octetos de la red que deseas escanear.

5️⃣ Una vez finalizado, el informe se guardará automáticamente en un archivo Informe.txt.

#####⚙️ Requisitos
Sistema operativo Linux o MacOS (no compatible con Windows).
Herramientas básicas de red preinstaladas (ping, hostname, bash).
📂 Archivos
scanner.sh
Este es el archivo principal que ejecuta todo el proceso. Su función es escanear la red local en busca de dispositivos activos, identificar puertos abiertos y generar un informe con los resultados.

UpIps.txt
Este archivo es generado automáticamente por el script y almacena las direcciones IP activas detectadas durante el escaneo de la red.

Informe.txt
Es el archivo de salida que contiene el informe detallado con los resultados del escaneo, incluyendo las IPs activas y los puertos abiertos de cada una.



