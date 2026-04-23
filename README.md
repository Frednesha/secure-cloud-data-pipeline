# 🌆 Azure Cloud Based Dashboard
This project demonstrates how to build a secure, cloud-based data solution using Microsoft Azure and Power BI.

## 🎯 Project Overview

The goal of this project was to simulate how a city government might track and analyze public data (e.g., park usage) using cloud services.

Instead of relying on local files, this solution stores data in the cloud and securely connects it to a reporting tool.

## 🏗️ Architecture
Data stored in Azure Blob Storage
Secure access via Shared Access Signature (SAS)
Data visualization in Power BI

## 🔐 Security
Access to the data was controlled using a SAS token with:
- Read permissions
- Time-bound access
- Scoped to container and object levels

## 🛠️ Tools & Technologies
- Microsoft Azure (Storage Account / Blob Storage)
- Power BI
- Command Line (data preparation)

## 📊 Features
- Cloud-hosted dataset
- Secure external access
- Interactive dashboard showing:
- Visitors by park
- Trends over time

## 💡 Key Learnings
- How to store and manage data in Azure Blob Storage
- Differences between RBAC and SAS-based access
- Connecting cloud data sources to Power BI
- Building a simple data pipeline for reporting

## 🚀 Future Improvements
- Automate deployment using Terraform
- Add real-time data ingestion
- Implement private endpoints for enhanced security

![Architecture Diagram](azure-city-data-dashboard/architecture/City_Data_Dashboard_Achitecture_Diagram.drawio.png)