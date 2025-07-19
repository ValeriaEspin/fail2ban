# readme_GRUPO_9.md

## 🔍 Resumen del proyecto seleccionado: Fail2ban  

Fail2ban es una herramienta de código abierto diseñada para mejorar la seguridad en servidores Linux mediante la prevención de ataques de fuerza bruta y accesos no autorizados. Su funcionamiento se basa en el monitoreo de archivos de registro del sistema (log files), donde detecta intentos fallidos repetitivos de inicio de sesión u otras actividades sospechosas. Una vez identificado el patrón de ataque, Fail2ban bloquea automáticamente la dirección IP ofensiva a través de reglas de firewall como `iptables` o `firewalld`.

Es altamente configurable, lo que permite proteger distintos servicios como SSH, FTP, Nginx, Apache, entre otros. Además, permite definir filtros personalizados y establecer tiempos de baneo según el nivel de riesgo. Su estructura modular lo convierte en una solución eficiente y adaptable a diversos entornos de producción.

---


## 🎯 Justificación de la elección del repositorio  


El grupo seleccionó Fail2ban porque representa una solución concreta, efectiva y ampliamente utilizada para mitigar ataques comunes en entornos reales de servidores. En especial, su uso es clave para prevenir ataques de fuerza bruta que buscan vulnerar servicios expuestos a Internet, como SSH.

Según Rankin (2017), Fail2ban es una de las herramientas más recomendadas en entornos Linux para el "hardening" o endurecimiento del sistema, debido a su bajo consumo de recursos y su capacidad de respuesta automática. También es valorada por su integración sencilla con sistemas de firewall y por formar parte de muchas distribuciones GNU/Linux como Debian, Ubuntu y CentOS.

Fail2ban no solo es práctico para administradores de sistemas, sino también relevante para estudiantes y profesionales en formación en ciberseguridad, ya que permite observar cómo los sistemas pueden reaccionar ante amenazas reales en tiempo real.
## 🧩 Ventajas técnicas, comunidad y soporte  

Fail2ban ofrece una arquitectura flexible que permite gestionar múltiples "jails" (reglas de detección y acción) en paralelo, facilitando su aplicación en múltiples servicios. Además, puede enviar alertas por correo electrónico, integrarse con scripts externos, y adaptarse a sistemas de autenticación personalizada.
Es una herramienta ampliamente documentada, con una comunidad activa y soporte continuo desde su repositorio oficial en GitHub. Está incluida en manuales de buenas prácticas de seguridad y en cursos técnicos sobre administración de sistemas y seguridad ofensiva y defensiva.
Su uso puede combinarse con otras herramientas de monitoreo y automatización, lo que lo convierte en un recurso estratégico dentro de entornos DevSecOps y servidores auto-gestionados.
---
## 📚 Referencias
- Rankin, K. (2017). *Linux Hardening in Hostile Networks*. Addison-Wesley Professional.
- Fail2ban GitHub Repository: https://github.com/fail2ban/fail2ban
- Fail2ban Official Documentation: https://www.fail2ban.org/wiki/index.php/Main_Page
- Red Hat (2023). *Fail2ban: Preventing brute-force logins*. https://access.redhat.com
- Linux Foundation. (2022). *Introduction to Linux Security*. edX Course.

