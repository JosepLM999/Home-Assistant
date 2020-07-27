# Home-Assistant configuration
Configuración e instalación de HA <br>
Mis Notas

# Instalación inicial en Raspberry 4
La instalación en Raspberry puede realizarse por varios métodos: <br>
1- Método rápido y automático a través de una imagen con un SO mínimo y HA ya integrado 
2- Método manual. Intalación previa del SO raspbian y posterior instalación de HA siguiendo los pasos indicados en la web oficial de HA

Diferencias: En 1 se instala el sistema oficial de pluguins automáticos EN 2 tenemos mayor control y acceso al SO
Los pasos de la configuración están en : https://www.home-assistant.io/docs/installation/raspberry-pi/<br>

# Plugins instalados y probados

# Plugins dispositivos SONOFF
https://github.com/peterbuga/HASS-sonoff-ewelink -> Seguir las notas del autor

# Plugins dispositivos gobernados por SmartLife
Se consigue instalando el componente Tuya: https://www.home-assistant.io/integrations/tuya/k -> Seguir las notas del autor

# Plugins integración cámaras Yi
Requiere modificar firmware de la cámara: https://github.com/TheCrypt0/yi-hack-v4#supported-cameras

# Configuración en HA del RTSP para poder trabajar con las cámaras anteriores
https://github.com/TheCrypt0/yi-hack-v4/wiki/Home-Assistant-RTSP-configuration

# Instalación Docker
https://ugeek.github.io/blog/post/2019-02-03-instalar-docker-en-raspberry-pi-con-raspbian.html

 run:

ha core update --version=0.XX.X
Run
