# linux-network-diagnostics

# Laboratorio: Despliegue de Red Mesh Privada (VPN) y Securizacion Perimetral

- **Objetivo:** Implemetar administración remota persistente sobre un servidor Linux optimizado (2GB RAM) sin exponer puertos criticos a la intenet pública.
- **Herramientas utilizadas:** Tailscale (WireGuard), UFW (Uncomplicated Firewall), SSH (Key-based authentication).
- **Logros Técnicos:** 
  - Configuración y securización del servicio SSH mediante llaves criptográficas, deshabilitando el acceso por contraseña.
  - Implementación de las reglas perimetrales estrictas con UFW para denegartodo el tráfico entrante por defecto, aislando el host.
  - Creación de un túnel privado encriptado de nivel militar mediante una topología Mesh (Tailscale), asignando una IP global fija dentro del rango '100.X.X.X'.
  - Validación y auditoría exitosa del canal de comunicación realizando conexiones cifradas desde redes externas móviles (4G/5G) hacia el entorno local.

## Scripts de Auditoría y Monítoreo (Bash)

### 1. Cazador de Procesos ('cazador.sh')
Automatización para el monítoreo y caza de procesos de alta carga que pueden comprometer la performance o seguridad del sistema.
[ver demo] (https://asciinema.org/a/1258565)

### 2. Rastreador de conexiones ('rastreador.sh')
Script diseñado para auditar conexiones de red activas, sockets abiertos y procedencia de IPs entrantes.
[ver demo] (https://asciinema.org/a/1258566)   


Linux file management and network diagnostics demo
Objetivo
Demostrar habilidades prácticas en Linux orientadas a gestión de archivos y diagnóstico de red, utilizando herramientas reales en entorno de terminal.

Demo principal
[ver demo] (https://asciinema.org/a/883887) 

Demostraciones
1. Busqueda de archivos con find y eliminacion con rm
Se utiliza find para localizar archivos dentro del sistema apicando filtros por tipo y nombre.
Se utiliza el comando rm para eliminar archivos mediante ruta absoluta, verificando la operación desde terminal.
[ver demo] (https://asciinema.org/a/883830)

2. Edición de archivos con nano
Se edita un archivo de texto utilizando nano, incluyendo guardado y salida del editor.
[ver demo] (https://asciinema.org/a/883871)

3. Analisis de red con traceroute
Se analiza la ruta de paquetes hacia un destino, identificando saltos intermedios y tiempos de respuesta. 
[ver demo] (https://asciinema.org/a/883887)

4. Diagnóstico de sistema (equipo lento)
Se realiza un análisis básico del sistema para identificar posibles causas de lentitud en el equipo.
[ver demo] (https://asciinema.org/a/883885)

5. Gestión de archivos
Se utiliza comandos cd, mkdir, touch, ls para la correcta creación de carpetas y archivos.
[ver demo] (https://asciinema.org/a/883886)

6. Permisos
Se visualizan y modifican permisos de archivos utilizando chmod y ls -l.
[ver demo] (https://asciinema.org/a/883896)

Habilidades demostradas
. Gestión de archivos y permisos en Linux (cd, mkdir, rm, nano, find, chmod)
. Diagnóstico de red (traceroute, mtr)
. Interpretacion de latencia y pérdida de paquetes
. Resolución de errores en tiempo real
. Organización y limpieza de entorno de trabajo

Obsevaciones
Durante la ejecución se presentaron errores que fueron corregidos en el momento, demostrando capacidad de análisis, adaptación y resolución.

Tecnologías
.Linux
.Terminal
.Asciinema
   

