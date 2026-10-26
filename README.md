# Seguridad en Sistemas y Redes

Dos prácticas de la asignatura Seguridad en Sistemas y Redes (Ingeniería de Computadores, ETSISI – UPM), hechas en un laboratorio aislado de máquinas virtuales con VirtualBox.

**Herramientas:** XCA, Apache (XAMPP), Wireshark, Kali Linux, nmap, Metasploit, VirtualBox.

## 1. Certificados digitales y HTTPS

Práctica en pareja. [Memoria en PDF](01-certificados-y-https/taller-certificados-https.pdf).

- Montaje de una autoridad de certificación propia con XCA.
- Emisión de un certificado personal y de un certificado de servidor a partir de su solicitud de firma (CSR).
- Configuración de Apache con HTTPS y autenticación del cliente mediante certificado.
- Comparación del tráfico HTTP y HTTPS capturado con Wireshark.

## 2. Auditoría de una máquina vulnerable

Reto de grupo, en el que esta parte fue la mía. [Memoria en PDF](02-pentesting-kioptrix/reto1-kioptrix.pdf).

Análisis de la máquina de entrenamiento *Kioptrix: Level 1* (VulnHub): descubrimiento de la red y de los servicios con nmap, identificación de un servicio desactualizado con una vulnerabilidad conocida, comprobación con Metasploit y recomendaciones para corregirlo (actualizar servicios, desactivar los innecesarios y aplicar el mínimo privilegio).

## Nota

Todo se hizo en un laboratorio aislado y sobre máquinas preparadas para practicar. Estas técnicas solo deben usarse en sistemas propios o con autorización expresa.
