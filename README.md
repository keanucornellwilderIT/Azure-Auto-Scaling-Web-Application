# Azure Auto-Scaling Web Application

A highly available web application deployed in **Microsoft Azure** using a **Virtual Machine Scale Set** and **Azure Load Balancer**.

## 🎯 Why I Built This

I wanted to understand how Azure keeps applications available when traffic increases or when a server becomes unhealthy.

This lab demonstrates how to build infrastructure that can **distribute traffic, monitor VM health, and automatically scale resources based on demand**.

## 🏗️ Architecture

```text
Internet
   │
   ▼
Public IP
   │
   ▼
Azure Load Balancer
   │
   ▼
Virtual Machine Scale Set
   │
   ├── VM Instance 1
   ├── VM Instance 2
   └── VM Instance 3
          │
          ▼
     Azure Monitor
          │
          ▼
      Autoscaling
```

## ⚙️ What I Did

1. Created an Azure Virtual Network.
2. Deployed a Virtual Machine Scale Set.
3. Installed a web server on the VM instances.
4. Created a public Azure Load Balancer.
5. Configured the backend pool and health probe.
6. Connected the Load Balancer to the Scale Set.
7. Configured Azure Monitor autoscaling rules.
8. Tested traffic distribution between VM instances.
9. Tested automatic scale-out and scale-in behavior.

## 🧠 Skills Demonstrated

* Microsoft Azure
* Azure Virtual Machines
* Virtual Machine Scale Sets
* Azure Load Balancer
* Virtual Networks
* Network Security Groups
* Health Probes
* Azure Monitor
* Autoscaling
* High Availability
* Cloud Troubleshooting

## 💡 What This Lab Demonstrates

This project demonstrates my ability to build a **scalable and highly available cloud environment in Azure** instead of relying on a single virtual machine.

The environment can distribute incoming traffic across multiple servers and automatically increase or decrease capacity based on demand.
