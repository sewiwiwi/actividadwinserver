---

## Máquina Virtual 2: Rocky Linux 9 (CLI)

### 1. Configuración de Hardware Virtual
Para el servidor Linux, se configuró una máquina virtual con los siguientes recursos para asegurar un entorno CLI (línea de comandos) eficiente:
* **Memoria RAM:** 8 GB (8192 MB).
* **Procesadores:** 2 vCPU.
* **Disco:** 30 GB.
* **Sistema Operativo:** Rocky Linux 9.

![Instalacion y Locacion Rocky ]

<img width="817" height="677" alt="rcoky" src="https://github.com/user-attachments/assets/abf69254-af45-4d6e-ba01-3c466df902e0" />
<img width="739" height="670" alt="rcockkck" src="https://github.com/user-attachments/assets/74036632-9542-4dec-8790-dfa12a231979" />

![Configuración de Disco 30GB]
<img width="809" height="704" alt="rcoky30" src="https://github.com/user-attachments/assets/901a1590-9cd9-4cf3-ae88-5709d264da87" />
![Configuración de HardWare]
<img width="939" height="817" alt="rcoky33" src="https://github.com/user-attachments/assets/24efdf2b-c684-46bf-9854-0c1b3b529094" />

### 2. Proceso de Instalación y Cuentas
Se procedió con la instalación mínima del sistema. Durante este proceso se configuraron las credenciales de acceso, habilitando la cuenta de 'root' y creando el usuario administrador del sistema.

![Instalación en progreso]
<img width="1668" height="857" alt="rcoky22" src="https://github.com/user-attachments/assets/0609c2d2-41c2-4135-9f68-209c6962e8fb" />

![Configuración de cuenta root]
<img width="1573" height="911" alt="cuenta root" src="https://github.com/user-attachments/assets/bc8e2744-40a9-458e-a299-f18cfadf3a80" />



### 3. Verificación de Dirección IP
Una vez finalizada la instalación y tras realizar el primer inicio de sesión (login), se ejecutó el comando `ip addr show`. Se confirmó que el servidor obtuvo la dirección IPv4 **192.168.198.133** a través de la interfaz de red activa.

![Comando ip addr show]
<img width="844" height="282" alt="ip" src="https://github.com/user-attachments/assets/09a4ed67-8e26-498a-8442-ce17951846e7" />


### 4. Habilitación y Comprobación de SSH
Se verificó el estado del servicio de acceso remoto mediante el comando `systemctl status sshd`. El sistema devolvió un estado **active (running)**, lo que confirma que el servidor está listo para recibir conexiones remotas seguras.

![Estado del servicio SSH]
<img width="979" height="312" alt="Captura" src="https://github.com/user-attachments/assets/c4e0076e-b7fa-46a9-aa8b-df614de8e4d4" />
