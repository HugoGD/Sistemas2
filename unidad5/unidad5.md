---
layout: default
title: "Modificación y compilación de Kernels"
---

## Sprint 5. XAMP

  1. Descargamos el paquete XAMP

<img width="572" height="378" alt="image" src="https://github.com/user-attachments/assets/89709236-34e1-4f60-911d-68f425962373" />

  2. Damos permisos de ejecución

<img width="628" height="57" alt="image" src="https://github.com/user-attachments/assets/14d2b01b-ba89-4661-9502-701b75e76b71" />

  3. Ejecutamos el paquete instalado y comenzara la instalación de los servicios

<img width="548" height="519" alt="image" src="https://github.com/user-attachments/assets/29067023-83dc-46ab-8d7b-90cef6efaa9c" />

  4. Mostramos los servicios encendidos

<img width="623" height="435" alt="image" src="https://github.com/user-attachments/assets/57344579-a0c3-4a53-a8ee-437b334d6446" />

  5. Ahora vamos a hacer el certificado primero creamos la carpeta donde estara el certificado ssl

<img width="623" height="60" alt="image" src="https://github.com/user-attachments/assets/aa3dc586-1b35-425a-9ebd-4c67ad33ec74" />

  6. Creamos el certificado valido

<img width="622" height="312" alt="image" src="https://github.com/user-attachments/assets/ebaf3578-2134-48bd-a1e2-55b9c4a0ea79" />

  7. Descomentamos las siguientes Lineas del documento /opt/lampp/etc/httpd.conf

<img width="474" height="232" alt="image" src="https://github.com/user-attachments/assets/ef0d409f-cfab-4314-ade5-47a6aad0b1f7" />

  8. Tambien descomentamos las lineas del archivo /opt/lampp/etc/extra/httpd-ssl.conf

<img width="621" height="453" alt="image" src="https://github.com/user-attachments/assets/ab8bda81-d131-4eab-80ea-2160a33d09fb" />

  9. Reiniciamos el servicio

<img width="627" height="169" alt="image" src="https://github.com/user-attachments/assets/92be7bf6-97dc-499f-bffe-f32e66cf709c" />

  10. Comprobamos que se abre (no va el certificado)

<img width="620" height="546" alt="image" src="https://github.com/user-attachments/assets/560e070c-3afb-4e3f-a145-c37c948bad47" />

  11. Creamos la pagina php

<img width="805" height="381" alt="image" src="https://github.com/user-attachments/assets/5b116c31-f70a-49ba-8386-56af37bc3b42" />

<img width="954" height="537" alt="image" src="https://github.com/user-attachments/assets/2ddf8751-5d52-4b25-a216-d4b0ac8c3268" />

