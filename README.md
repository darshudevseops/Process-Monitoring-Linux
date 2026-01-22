# Linux Process Management Task


## 📋 Overview
Complete implementation of Linux process management task covering:
- Process monitoring and listing
- Process termination and management
- Service control with systemctl
- Resource monitoring and optimization
- Interview Q&A preparation

## 🛠️ Tools Used
- Linux Command Line Interface (CLI)
- systemctl for service management
- ps, top, htop for process monitoring
- kill, pkill for process termination

## 📁 Repository Structure
linux-process-management/
├── README.md
├── docs/
│ ├── task-report.md
│ └── interview-answers.md
├── scripts/
│ ├── monitor-processes.sh
│ └── service-manager.sh
└── examples/
└── command-outputs/



## 🚀 Quick Start

### Basic Commands:
```bash
# List all processes
ps aux

# Monitor in real-time
top

# Manage services
sudo systemctl status ssh
sudo systemctl restart nginx

Run Monitoring Script:
chmod +x scripts/monitor-processes.sh
./scripts/monitor-processes.sh

📚 Contents
1. Process Management
Process listing with ps, top, htop

Process states and their meanings

Process termination techniques

2. Service Management
Starting/stopping services with systemctl

Enabling services at boot

Service dependencies and troubleshooting

3. Resource Monitoring
CPU, memory, and I/O monitoring

Identifying and handling resource spikes

Performance optimization

4. Interview Preparation
Common interview questions

Detailed answers and explanations

Practical scenarios and solutions

🔧 Scripts Included
monitor-processes.sh - Automated process monitoring

kill-processes.sh - Safe process termination

service-manager.sh - Service management utility
