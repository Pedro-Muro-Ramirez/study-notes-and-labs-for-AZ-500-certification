# Lab: Create a Microsoft Azure Resource

**Source:**  
Microsoft Learn – AZ-900 Exercise: Create a Microsoft Azure Resource  
https://microsoftlearning.github.io/AZ-900-Microsoft-Azure-Fundamentals/Instructions/Labs/02-exercise-create-azure-resource.html

---

## Objective

Use the Azure portal to create and manage Azure resources, specifically:
- Create a resource group
- Deploy a virtual machine inside that resource group
- Observe how Azure organizes related resources

---

## Steps Performed

### 1. Create a Resource Group
- Signed into the Azure portal
- Navigated to **Resource groups**
- Created a new resource group with the following settings:
  - **Name:** `IntroAzureRG`
  - **Region:** Central US
- Confirmed the resource group was successfully created

---

### 2. Create a Virtual Machine
- Selected **Create a resource → Infrastructure services → Virtual machine**
- Configured the VM with:
  - **Subscription:** Default subscription
  - **Resource group:** `IntroAzureRG`
  - **Virtual machine name:** `my-VM`
  - **Authentication type:** Password
  - **Username:** `azureuser`
  - **Public inbound ports:** None
- Left all other settings as default
- Created the virtual machine and waited for deployment to complete

---

### 3. Verify Resources
- Navigated back to **Resource groups**
- Opened `IntroAzureRG`
- Verified that the VM and its associated resources (network interface, storage, etc.) were created automatically

---

## Cleanup
- Navigated to **Resource groups**
- Selected `IntroAzureRG`
- Deleted the resource group to remove all associated resources and avoid unnecessary costs

---

## Key Learnings
- Resource groups act as logical containers for related Azure resources
- Creating a VM automatically provisions supporting resources such as networking and storage
- Deleting a resource group is an efficient way to clean up all associated resources

---

## AZ-500 Relevance
- Platform protection fundamentals
- Secure resource deployment
- Understanding default security configurations during resource creation
