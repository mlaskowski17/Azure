# Azure - storage

## 1. Set up

### 1.1 Resource Group
Create a resource group
```
Resource group: SYSTEM
Region: East US
```

### 1.2 Storage
Having resource group create a service called Azure Storage
```
Resource group: SYSTEM
Storage account name: storagename01
Location: East US
Performance: Standard
Account kind: StorageV2 (general purpose v2)
Replication: Read-access geo-redundant storage (RA-GRS)
Access ties (default): Hot
```

### 1.3 Connection string
Copy `connection string` from Access keys of previously created Storage service and paste inside notebooks `azure_datastore.ipynb`. This is important step, without it you will not be able to connect to datastore and uploaded data / download data.  


