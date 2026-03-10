# gcp-vm-instances-lab
# Creating Virtual Machines in Google Cloud

This project demonstrates how to create and configure different types of Virtual Machine instances in Google Cloud Platform (GCP).

The lab explores the configuration of Compute Engine instances with different machine types and operating systems.

---

# Lab Objectives

In this lab we learned how to:

- Create standard virtual machines
- Deploy Windows virtual machines
- Create custom machine types
- Explore VM instance configuration
- Monitor VM logs
- Verify system resources using Linux commands

---

# Environment

Platform: Google Cloud Platform  
Service: Compute Engine  
Region: europe-west4
Zone: europe-west4-a

---

# Virtual Machines Created

## 1. Utility VM

Configuration:

- Name: utility-vm
- Machine type: e2-medium
- Series: E2
- External IP: None

Purpose:
This VM was created to explore machine types and VM configuration settings.

---

## 2. Windows Virtual Machine

Configuration:

- Name: windows-vm
- OS: Windows Server 2016 Datacenter Core
- Machine type: e2-standard-2
- Disk: 64GB SSD

Firewall rules enabled:

- HTTP
- HTTPS


Password configuration:

![Windows Password]
---

## 3. Custom Virtual Machine

Configuration:

- Name: custom-vm
- CPU: 2 vCPUs
- Memory: 4 GB
- OS: Debian 12

This VM demonstrates how to create a custom machine configuration instead of predefined machine types.


---

# Verifying System Resources

After connecting to the custom VM via SSH, the following commands were executed.
free

Displays memory usage.

nproc

Shows number of processors.

lscpu

Displays detailed CPU information.


---

# Logs Monitoring

Compute Engine logs were explored using Logs Explorer to monitor VM activity.


---

# Key Concepts Learned

This lab demonstrates the following Google Cloud concepts:

- Compute Engine VM creation
- Machine types and custom machines
- Windows VM deployment
- SSH access to Linux instances
- Resource monitoring
- Logging in Google Cloud

---

# Conclusion

This lab provides hands-on experience with Google Cloud Compute Engine and demonstrates how to deploy and manage different types of virtual machines.
