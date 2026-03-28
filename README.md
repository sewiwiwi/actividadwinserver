Evaluación de Implementación de Servidores (Fase 1 y 2)

Este repositorio documenta el proceso de creación y configuración de máquinas virtuales según los requerimientos de la evaluación práctica.

## Máquina Virtual 1: Windows Server 2019 (GUI)

### 1. Configuración de Hardware Virtual
Se creó una máquina virtual en VMware Workstation asignando los recursos solicitados en la pauta:
* **Memoria RAM:** 8 GB (8192 MB)*
* **Procesadores:** 2 vCPU
* **Disco Duro:** 30 GB
* **Medio de instalación:** Archivo ISO de Windows Server 2019.

*(Nota: Aunque la captura muestra 8GB de RAM, por limitaciones físicas del equipo anfitrión (Out of Memory), la memoria se redujo a 4GB posteriormente para poder ejecutar la máquina de manera estable).*

![Configuración de RAM y CPU])
<img width="905" height="801" alt="como sale en la guia" src="https://github.com/user-attachments/assets/8d22e743-9102-40f7-a4a0-44dbcabf675f" />

![Configuración de Disco 30GB]
<img width="659" height="586" alt="ponerle 30" src="https://github.com/user-attachments/assets/29529ed8-23b6-487b-af39-4dc6de651418" />

![Carga de archivo ISO]
<img width="1009" height="739" alt="creando maquina virtual win2019" src="https://github.com/user-attachments/assets/2ef03c1a-8d9b-4ea8-bbeb-0eb9bece0532" />

### 2. Instalación del Sistema Operativo
Durante el proceso de instalación de Windows, se seleccionó específicamente la versión **Windows Server 2019 Standard (Experiencia de escritorio)** para cumplir con el requisito de instalar el servidor con Interfaz Gráfica de Usuario (GUI).

![Selección de Experiencia de Escritorio]
<img width="1307" height="838" alt="win" src="https://github.com/user-attachments/assets/c6677822-f7ab-4eab-9d67-4debab0e12d6" />

![Proceso de instalación]
<img width="1107" height="801" alt="inehstalandoc" src="https://github.com/user-attachments/assets/7f7abc48-7da1-49d6-bc8b-aedd003f9288" />

### 3. Verificación de la Dirección IP
Una vez iniciado el sistema operativo, se abrió el Símbolo del sistema (cmd) y se ejecutó el comando `ipconfig` para identificar la dirección IPv4 asignada a la máquina virtual.

![Ejecución de ipconfig]
<img width="1094" height="566" alt="ipconfig" src="https://github.com/user-attachments/assets/b50676cf-c1dc-4925-803d-74633b492c76" />

### 4. Habilitación de Acceso Remoto por RDP
Para permitir la administración remota del servidor, se ingresó al **Administrador del servidor > Servidor local**. Desde el panel de propiedades, se modificó la configuración de "Escritorio remoto" pasando de su estado por defecto a **Habilitado**, permitiendo así las conexiones entrantes por RDP.

![Dashboard del Administrador del Servidor]
<img width="1721" height="960" alt="Captura" src="https://github.com/user-attachments/assets/56170193-689c-4336-92f8-0ae4ed87316b" />

![Escritorio Remoto Habilitado]
<img width="918" height="407" alt="servidor ssh activado" src="https://github.com/user-attachments/assets/3ff50ef8-4c42-4a6f-9396-cda6fb97ec7c" />
