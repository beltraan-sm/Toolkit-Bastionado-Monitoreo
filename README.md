# Toolkit-Bastionado-Monitoreo
#Linux Security Toolkit

Toolkit de bastionado y auditoría de sistemas Linux (Ubuntu 20.04/22.04/24.04).

Incluye herramientas para:

- Firewall (UFW)
- Bastionado SSH
- Auditoría de usuarios
- Monitorización de logs

---

##Descripción técnica

El proyecto está compuesto por scripts en Bash que aplican controles básicos de seguridad:

- Principio de mínimo privilegio
- Hardening de servicios críticos
- Auditoría de accesos y usuarios
- Monitorización de eventos sospechosos

Cada script genera un reporte en `/evidences`.

---

##Instalación

```bash
git clone 
cd linux-security-toolkit
chmod +x scripts/*.sh
