# Windows System Troubleshooting

## 📌 Overview

This project documents hands-on Windows troubleshooting and system administration tasks performed in a Windows environment.

## 🎯 Objectives

- Understand basic Windows system administration
- Investigate system performance
- Identify running processes and services
- Review Windows system information
- Practice using built-in Windows troubleshooting tools

## 🛠️ Tools Used

- Task Manager
- Windows Services
- System Information
- Command Prompt
- PowerShell
- Event Viewer

## 🧪 Lab Tasks

### 1. System Information

#### Objective

To gather basic Windows system information using built-in command-line tools.

#### Commands Used

```cmd
systeminfo
hostname
whoami
````

#### Information Checked

* Operating system and version
* System architecture
* Processor details
* Installed physical memory
* Computer name
* Current logged-in user
* Network configuration

#### Key Learning

Learned how to use built-in Windows command-line tools to quickly gather system information for IT support and troubleshooting.
#### Screenshots

![Task 1 – System Information](task1-systeminfo.png)

![Task 1 – Hostname and User Information](task1-hostname-whoami.png)

### 2. Running Processes

#### Objective

To investigate running applications and background processes and review their resource usage using Windows Task Manager.

#### Tool Used

- Windows Task Manager

#### Information Checked

- Running applications
- Background processes
- CPU usage
- Memory usage
- Disk usage
- Network usage

#### Findings

Task Manager was used to review the processes currently running on the system.

At the time of testing:

- CPU usage was approximately **8%**
- Memory usage was approximately **84%**
- Disk usage was approximately **2%**
- Network usage was approximately **0%**

Google Chrome and Microsoft Teams were among the applications using higher amounts of memory, while VirtualBox was using some CPU and memory resources.

#### Key Learning

Learned how to use Windows Task Manager to identify running processes and monitor system resource usage. This can help IT support staff investigate performance-related issues.

#### Screenshot

![Task 2 – Running Processes](task2-running-processes.png)

### 3. Windows Services

Investigated Windows services and their:

- Status
- Startup type
- Service name
- Description

### 4. Event Viewer

Reviewed Windows Event Viewer to understand how system and application events are recorded.

### 5. Command-Line Troubleshooting

Used Windows command-line tools to gather system and network information.

## 🧠 Key Learning

Windows troubleshooting should follow a structured approach:

1. Identify the problem
2. Gather information
3. Check system resources
4. Review processes and services
5. Check relevant logs
6. Identify the root cause
7. Apply and verify the solution

## 📚 Skills Demonstrated

- Windows troubleshooting
- System administration fundamentals
- Process investigation
- Service management
- Event log analysis
- Command-line troubleshooting
- Technical documentation
