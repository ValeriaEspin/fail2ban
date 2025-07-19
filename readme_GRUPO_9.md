# readme_GRUPO_9.md

## 🔍 Resumen del proyecto seleccionado: Fail2ban  

Fail2ban es una herramienta de código abierto diseñada para mejorar la seguridad en servidores Linux mediante la prevención de ataques de fuerza bruta y accesos no autorizados. Su funcionamiento se basa en el monitoreo de archivos de registro del sistema (log files), donde detecta intentos fallidos repetitivos de inicio de sesión u otras actividades sospechosas. Una vez identificado el patrón de ataque, Fail2ban bloquea automáticamente la dirección IP ofensiva a través de reglas de firewall como `iptables` o `firewalld`.

Es altamente configurable, lo que permite proteger distintos servicios como SSH, FTP, Nginx, Apache, entre otros. Además, permite definir filtros personalizados y establecer tiempos de baneo según el nivel de riesgo. Su estructura modular lo convierte en una solución eficiente y adaptable a diversos entornos de producción.

---


## 🎯 Justificación de la elección del repositorio  


El grupo seleccionó Fail2ban porque representa una solución concreta, efectiva y ampliamente utilizada para mitigar ataques comunes en entornos reales de servidores. En especial, su uso es clave para prevenir ataques de fuerza bruta que buscan vulnerar servicios expuestos a Internet, como SSH.

Según Rankin (2017), Fail2ban es una de las herramientas más recomendadas en entornos Linux para el "hardening" o endurecimiento del sistema, debido a su bajo consumo de recursos y su capacidad de respuesta automática. También es valorada por su integración sencilla con sistemas de firewall y por formar parte de muchas distribuciones GNU/Linux como Debian, Ubuntu y CentOS.

Fail2ban no solo es práctico para administradores de sistemas, sino también relevante para estudiantes y profesionales en formación en ciberseguridad, ya que permite observar cómo los sistemas pueden reaccionar ante amenazas reales en tiempo real.


