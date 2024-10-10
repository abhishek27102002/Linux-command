sysopctl
sysopctl is a simple system management tool designed to help users perform basic system operations such as listing services, monitoring system load, checking disk usage, analyzing logs, and backing up files.

Features
Service Management: List, start, and stop system services.
System Monitoring: View system load and monitor running processes.
Disk Usage: Check disk space usage.
Log Analysis: Analyze system logs.
Backup: Backup system files to a specified path.
Installation
Download or clone the repository to your local system.
Ensure that the script has execution permissions:
bash
Copy code
chmod +x sysopctl
Usage
The script accepts several commands, each designed to perform a specific task. Below is a list of available commands:

Help and Version
sysopctl --help
Display help information and list available commands.

sysopctl --version
Display the current version of sysopctl.

Service Management
sysopctl service list
List all running services.

sysopctl service start <service-name>
Start a specific service by its name.

sysopctl service stop <service-name>
Stop a specific service by its name.

System Monitoring
sysopctl system load
View the current system load (output of uptime command).

sysopctl process monitor
Monitor system processes (opens the top command).

Disk Usage
sysopctl disk usage
Check the system’s disk usage.
Log Analysis
sysopctl logs analyze
Analyze critical system logs using journalctl.
Backup
sysopctl backup <path>
Backup system files from a specified path to /backup/destination.
Examples
List all running services:

bash
Copy code
sysopctl service list
Start a service:

bash
Copy code
sysopctl service start nginx
Check disk usage:

bash
Copy code
sysopctl disk usage
Backup system files:

bash
Copy code
sysopctl backup /path/to/files
Version
sysopctl v0.1.0

License
This project is licensed under the MIT License.

