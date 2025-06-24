# DevOps
Scripts para monitoreo y uso de recursos (CPU, RAM, disco)
# 🖥️ Monitor de Recursos en Linux - CPU, Memoria, Disco 📊

Este proyecto contiene un script en Bash que permite **monitorear en tiempo real** el consumo de CPU, memoria RAM y almacenamiento en sistemas Linux, ideal para tareas de soporte, diagnóstico o administración básica de servidores.

---

## 📌 Características

- 📡 Muestra en consola el uso actual de:
  - CPU
  - Memoria RAM
  - Espacio en disco
- 📁 Guarda logs diarios en archivos `.log`
- ⏱ Intervalo personalizable (cada X segundos)
- 🛑 Alerta en consola si el uso excede los umbrales críticos
- 🧪 Compatible con distribuciones basadas en Debian, RHEL, Arch, etc.

---

## ⚙️ Requisitos

- Linux con Bash (`/bin/bash`)
- Comandos estándar: `top`, `free`, `df`, `date`, `awk`, `grep`, `sed`
- Permisos de ejecución (`chmod +x`)

---

## 🚀 Uso

```bash
git clone https://github.com/tu-usuario/monitor-recursos-linux.git
cd monitor-recursos-linux
chmod +x monitor.sh
./monitor.sh
BUILDING.....
