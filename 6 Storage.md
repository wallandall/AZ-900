# 6 Storage
[Azure Storage](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction) uses storage accounts as the base for all Azure Storage types e.g: Blob, Disk, File or Archive data.
An Azure Storage Account is a unique Azure Namespace in Azure which means it has a unique web address in the following format ``` uniquename.<storagetype>.core.windows.net ```
### Benefits of Azure Storage
Azure Storage services offer the following benefits for application developers and IT professionals:

- Durable and highly available. Redundancy ensures that your data is safe in the event of transient hardware failures. You can also opt to replicate data across data centers or geographical regions for additional protection from local catastrophe or natural disaster. Data replicated in this way remains highly available in the event of an unexpected outage.
- Secure. All data written to an Azure storage account is encrypted by the service. Azure Storage provides you with fine-grained control over who has access to your data.
- Scalable. Azure Storage is designed to be massively scalable to meet the data storage and performance needs of today's applications.
- Managed. Azure handles hardware maintenance, updates, and critical issues for you.
Accessible. Data in Azure Storage is accessible from anywhere in the world over HTTP or HTTPS. Microsoft provides client libraries for Azure Storage in a variety of languages, including .NET, Java, Node.js, Python, PHP, Ruby, Go, and others, as well as a mature REST API. Azure Storage supports scripting in Azure PowerShell or Azure CLI. And the Azure portal and Azure Storage Explorer offer easy visual solutions for working with your data.

## Blob
Blob storage or "Binary Large Object" is a term used for any digital file. Azure suipports the following Blob types:
- Block: Store text and binary data up to 4.78TB. Made up of indevidually managed blocks of data
- Append: Block blobs that are optimized for append operations. Works well for logging where data is continuously appended.
- Page: Store files up to 8TB. Any part of the file could be accessed at any time , for example a virtual hard drive
  
Blob data is provided in three different pricing toiers:
- Hot: Frequently accessed files with lower access times and higher access cost
- Cold : Lower storage costs and higher access times. Data is stored for at least 30 Days.
- Archive: Lower costs and highest access times

## Disk
Disk Storage is a managed disk and comes in 4 different disk types:
- HDD: Spinning Hard Drive with low cost and suitable for backups.
- Standard SSD: Standard for production with higher reliability , scalability and lower latency than HDD.
- Premium SSD: Super fast and high performance with very low latency and is used for critical workloads.
- Ultra Disk: For most demanding , data intensive workloads. Can have disks up to 64TB in size.

## File
File Storage is a fully managerd storage solution for storing files in Azure

## Archive
Azure Archiving is a low cost arciving solution for archiving data in Azure.


[back](ReadMe.md)