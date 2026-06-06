# ⚙️ DevOps Automation Scripts

A collection of production-grade shell scripts and 
Kubernetes configurations for system monitoring, 
backup automation, and containerized deployments.

## 📂 Scripts

### 🖥️ System Health Monitor
`system_health_monitor.sh` — Monitors CPU, memory, 
disk usage and triggers alerts when thresholds are exceeded.

### 💾 Backup Automation  
`backup_script.sh` — Automates file/database backups 
with timestamped archives and retention policies.

### 🐄 WiseCow Deployment
`wisecow.sh` + `wisecow.yml` — Containerized app 
deployment with Kubernetes manifest.

## 🛠️ Tech Stack
`Bash` `Shell Scripting` `Docker` `Kubernetes` `GitHub Actions`

## 🚀 Usage
```bash
# System health check
chmod +x system_health_monitor.sh
./system_health_monitor.sh

# Run backup
chmod +x backup_script.sh
./backup_script.sh
```

## 🔄 CI/CD
Automated Docker build via GitHub Actions on every push.
