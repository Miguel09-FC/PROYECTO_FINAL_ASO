# FINAL-ASO

# [Instalar el rol de Directorio Activo, crear una estructura de dominio, instalar IIS y permitir que se pueda acceder al IIS mediante usuario y contraseña creados anteriormente en el Directorio Activo](https://github.com/jesusninoc/ClasesASO/blob/master/2024-02-20.md)

***Script PowerShell:***

**Active Directory e IIS:**

- Instala y configura Active Directory con el dominio "andel.local."
- Instala IIS, crea una carpeta web en "C:\web," y establece un sitio de prueba en el puerto 81.

**Sitios Web para Varios Clientes:**

- Crea sitios web individuales para clientes listados en un archivo, asignando puertos consecutivos a partir de 82.

**Unidades Organizativas (U.O.) en Active Directory:**

- Crea tres U.O. llamadas "asir," "alumnos," y "profesores" en Active Directory.

**Creación Masiva de Usuarios:**

- Crea usuarios con contraseñas predefinidas en la U.O. "alumnos/asir."

**Configuración de IIS:**

- Habilita la autenticación de Windows y deshabilita la autenticación anónima.

**Reinicio del Sitio Web de Prueba:**

- Reinicia el sitio web de prueba para aplicar los cambios de configuración.

**Configuración de Red:**

- Asigna configuración de red (IP, máscara, puerta de enlace, DNS) a la interfaz "Wi-Fi."

*Asegúrate de tener privilegios adecuados antes de ejecutar este script, ya que realiza cambios significativos en la configuración del sistema.*
