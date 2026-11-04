<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:2EC866&height=220&section=header&text=Rodrigo%20Mart%C3%ADnez&fontSize=56&fontColor=2EC866&animation=fadeIn&fontAlignY=38&desc=Ingenier%C3%ADa%20del%20Software%20%C2%B7%20Ciberseguridad%20%C2%B7%20U-TAD&descAlignY=60&descAlign=50" alt="Rodrigo Martínez · Ingeniería del Software · Ciberseguridad · U-TAD" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2EC866&center=true&vCenter=true&width=760&height=40&lines=Estudiante+de+cuarto+curso+de+Ingenier%C3%ADa+del+Software+en+U-TAD;Especializaci%C3%B3n+en+Ciberseguridad;Blue+Team+%C2%B7+DFIR+%C2%B7+Bastionado+%C2%B7+Seguridad+ofensiva;Construyendo+herramientas+de+seguridad+en+Python+y+Node.js" alt="Estudiante de cuarto curso de Ingeniería del Software en U-TAD · Especialización en Ciberseguridad · Blue Team · DFIR · Bastionado · Seguridad ofensiva · Construyendo herramientas de seguridad"/>

<a href="https://www.linkedin.com/in/rodrigo-martinez-sec/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=2EC866" alt="LinkedIn"/></a>
<a href="mailto:rodrimartinezhernandez2003@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email"/></a>

</div>

<br/>

Estudiante de cuarto curso de **Ingeniería del Software** en **U-TAD** (Madrid), con especialización en **Ciberseguridad**. Mi principal interés es **Blue Team** —análisis forense, bastionado y análisis de malware—, con base de seguridad ofensiva y una línea de crecimiento en **ingeniería inversa**.

Documento lo que aprendo y construyo herramientas para que el trabajo de seguridad sea reproducible. Busco mis primeras prácticas en ciberseguridad; **OSCP** es mi objetivo a medio plazo y la **ingeniería inversa**, mi siguiente área de desarrollo.

```text
Enfoque actual   →  4.º curso: TFG · Bastionado · Proyectos de Ciberseguridad
Construyendo     →  Argos (triaje local de malware) · Ganzua (analizador de ZIP cifrados)
Intereses        →  Blue Team · DFIR · Bastionado · Seguridad ofensiva
Aprendiendo      →  Ingeniería inversa
Objetivo         →  OSCP (aún no certificado) · Prácticas en ciberseguridad
Idiomas          →  Español (nativo) · Inglés B2 (C1 en curso)
```

---

## 🎓 Tercero y cuarto

### Tercero (2025-26)

| Asignatura | Qué trabajé |
|---|---|
| **Análisis Forense** | DFIR en Linux: gestión de evidencias, artefactos de disco y memoria, timelines y esteganografía. |
| **Hacking Ético** | Pentesting de aplicaciones web, SSH tunneling, laboratorio de intrusión en Active Directory y escalada de privilegios. |
| **Introducción a la Seguridad Informática** | Fundamentos de seguridad de la información. |
| **Programación Web II (Servidor)** | HTTP, Express, MVC + MongoDB, autenticación JWT, seguridad, testing y documentación de API. |
| **Programación Web I (Cliente)** | JavaScript en el cliente. |
| **Aplicaciones Móviles** | Android con Kotlin (fragments, ciclo de vida) y Flutter. |
| **Inteligencia Artificial** | Datos tabulares, ANN, CNN, NLP, modelos generativos, aprendizaje por refuerzo y ética. |
| **Proyectos III** | Reto Eventbrite: backend de un asistente de notificaciones con IA. |
| **Programación de Sistemas Distribuidos** | Kubernetes sobre AWS EC2 con Docker y NFS. |
| **Fundamentos de UX** | Investigación de usuarios, protocolos de test y encuestas. |
| **Dirección y Gestión de Proyectos** | SCRUM y entrega Agile. |

### Cuarto (2026-27)

| Asignatura | Qué estoy trabajando |
|---|---|
| **Bastionado** | Bastionado de Linux y Windows: CIS Benchmarks, MITRE ATT&CK, Apache, BIOS/GRUB, firewall/DMZ/WAF/VPN/IDS/SIEM. |
| **Proyectos de Ciberseguridad** | Desarrollo de herramientas de seguridad (Argos) y wargames. |
| **Técnicas y metodologías de investigación en Ciberseguridad** | Análisis de investigaciones de congresos y comunicación técnica de resultados. |
| **Ingeniería de Software** | Requisitos, UML y modelado de casos de uso. |
| **Paradigmas de Programación** | Programación funcional y reactiva en Python. |

### Trabajo de Fin de Grado (2026-27)

**Evasión de anti-cheats mediante hipervisor (Ring -1)** — investigación sobre la escalada de privilegios en el ecosistema cheat/anti-cheat: anillos de privilegio x86-64, internals del kernel de Windows (EPROCESS, VAD tree, KUSER_SHARED_DATA) y ocultación mediante hipervisor frente a un target propio.

`C/C++` · `Ensamblador x86-64` · `VT-x / AMD-V` · `Kernel de Windows` · `HyperDbg / hvpp`

---

## 🛡️ Ciberseguridad

### Blue Team · DFIR · Bastionado

| Proyecto | Descripción | Stack |
|---|---|---|
| **[Argos](https://github.com/rodrigomhz/argos-entrega-intermedia)** | Analizador local de ficheros sospechosos: huellas, tipo real del fichero, cabeceras PE, YARA, Defender local, EMBER2024 y una VM desechable para análisis dinámico. Ninguna muestra sale de la máquina. | Python · YARA · PE · VMware · CAPEsolo · EMBER2024 |
| **[Ganzua](https://github.com/rodrigomhz/ganzua)** | CLI para análisis forense de ZIP cifrados: detecta ZipCrypto frente a AES-256, extrae material para hashcat y verifica candidatos de contraseña. | Node.js · AES-256 · ZipCrypto · hashcat |
| **Prácticas de Análisis Forense** | DFIR: adquisición de evidencias, análisis de memoria y disco, timelines y esteganografía. | Volatility · Autopsy · Wireshark |
| **Prácticas de Bastionado** | Ejercicios de bastionado de Linux/Windows: Apache, BIOS/GRUB, CIS Benchmarks y mapeo de MITRE ATT&CK. | Linux · Windows · Apache · CIS · ATT&CK |

### Seguridad ofensiva

| Proyecto | Descripción | Stack |
|---|---|---|
| **Prácticas de Hacking Ético** | Pentesting de aplicaciones web, SSH tunneling y laboratorio de intrusión en Active Directory desde la DMZ hasta el Domain Controller. | Burp Suite · Nmap · sqlmap · Impacket · BloodHound |

---

## 🚀 Proyectos de software

| Proyecto | Descripción | Stack |
|---|---|---|
| **Eventbrite × U-TAD** | Backend de un asistente de notificaciones con IA: plantillas, disparadores de eventos, autenticación y avisos multicanal en tiempo real. Equipo de 10, SCRUM y presentación en Demo Day. | Node.js · Express · LangChain · OpenRouter · WebSockets · JWT · Swagger |
| **AñadaMaster (ISOF)** | Requisitos y modelo UML de casos de uso para un sistema de gestión de bodega, a partir de una entrevista con el cliente. | UML · Requisitos · Casos de uso |
| **[Kubernetes file manager](https://github.com/rodrigomhz/PracticaKubernetes)** | Servicio distribuido de gestión de ficheros en un clúster de 3 nodos en AWS EC2: broker + servidores de ficheros, imágenes Docker y almacenamiento NFS compartido con 3 réplicas. | Kubernetes · Docker · NFS · AWS |
| **[Web client practices](https://github.com/rodrigomhz/ProgramacionWebCliente)** | Prácticas de JavaScript en el cliente. | JavaScript |
| **Mobile apps** | Prácticas de Android/Kotlin y Flutter: fragments, ciclo de vida y gestión de eventos. | Kotlin · Flutter |

---

## 🧰 Stack técnico

<div align="center">

**Lenguajes**<br/>
<img src="https://skillicons.dev/icons?i=py,js,c,cpp,kotlin,bash,powershell&perline=7" alt="Python, JavaScript, C, C++, Kotlin, Bash, PowerShell"/>

**Web, datos e infraestructura**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,react,mongodb,mysql,flutter,linux,kali,docker,kubernetes,aws,git&perline=11" alt="Node.js, React, MongoDB, MySQL, Flutter, Linux, Kali, Docker, Kubernetes, AWS, Git"/>

**Seguridad**<br/>
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" alt="Burp Suite"/>
<img src="https://img.shields.io/badge/Nmap-004B87?style=flat-square" alt="Nmap"/>
<img src="https://img.shields.io/badge/sqlmap-2B2D38?style=flat-square" alt="sqlmap"/>
<img src="https://img.shields.io/badge/MITRE_ATT%26CK-C41E3A?style=flat-square&logo=mitre&logoColor=white" alt="MITRE ATT&CK"/>
<img src="https://img.shields.io/badge/Volatility-2B2D38?style=flat-square" alt="Volatility"/>
<img src="https://img.shields.io/badge/Autopsy-4B0082?style=flat-square" alt="Autopsy"/>
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" alt="Wireshark"/>
<img src="https://img.shields.io/badge/YARA-2B2D38?style=flat-square" alt="YARA"/>

</div>

---

## 🎯 Objetivos

**Interés principal:** Blue Team (DFIR, bastionado y detección) con base ofensiva y desarrollo progresivo de ingeniería inversa.

| Estado | Objetivo | Enfoque |
|:---:|---|---|
| 🎯 | **OSCP** — OffSec Certified Professional | Certificación objetivo, aún no obtenida |
| 📚 | **Ingeniería inversa** | Desarrollo de habilidades: análisis de binarios y malware |

---

## 📫 Contacto

<p align="center">
  <a href="https://www.linkedin.com/in/rodrigo-martinez-sec/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=2EC866" alt="LinkedIn"/></a>
  <a href="mailto:rodrimartinezhernandez2003@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email"/></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:2EC866&height=100&section=footer" width="100%" alt=""/>
