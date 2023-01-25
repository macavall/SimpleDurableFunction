# DurableFunction
---
Durable Functions Simple Example of how to watch a Durable Function work Hands-On

## Requirements
- Install Fiddler
- Install the [Storage Explorer](https://github.com/microsoft/AzureStorageExplorer/releases)
  ![image](https://user-images.githubusercontent.com/43223084/214461609-503fdf61-6338-4157-b591-9dfbac65cf33.png)

- Download this Repository
- Import the ```.\Fiddler\DurableFunctionRules.farx```
  - Import these rules to the Fiddler **AutoResponder**
    ![image](https://user-images.githubusercontent.com/43223084/214461317-d51cc29d-7d56-4506-b6cd-1cd2071bf75e.png)  
  - Ensure the **Configurations** are as shown in the ***Screenshot*** above  

### Run the Project and execute the provided URL  

  ![image](https://user-images.githubusercontent.com/43223084/214462111-8e8ff5b8-aeba-47e7-83dc-9e5491825884.png)  
  
### Check the **Storage Emulator Control Queue**  
  ![image](https://user-images.githubusercontent.com/43223084/214461906-50748a0e-5351-4a8b-966d-f76ec110aea0.png)  

### Uncheck the **Control Queue Fiddler Rule**  
![2023-01-24_19h46_48](https://user-images.githubusercontent.com/43223084/214462239-2fde958b-66d6-4246-90de-42ea29ae316f.gif)  

### Check the **WorkItems Queue** in Storage Explorer  
![image](https://user-images.githubusercontent.com/43223084/214462511-c4a83150-2258-4504-bc16-11a360781470.png)  

### Uncheck the **Control Queue Fiddler Rule**  
![2023-01-24_19h49_42](https://user-images.githubusercontent.com/43223084/214462570-2d45f37c-c07d-4d39-aa2d-4366b3e82324.gif)  

### After unchecking the **WorkItems Queue** checkbox, the Function will complete execution

---  
<br/>

# Verbose Logging
- It is possible to get verbose logging from the Function App Host locally and in Azure
  - For verbose logging locally, open Visual Studio 2022 and complete the following
![2023-01-24_20h48_36](https://user-images.githubusercontent.com/43223084/214469518-dbd16952-e80e-4354-bf7f-197a55400815.gif)
![2023-01-24_20h50_34](https://user-images.githubusercontent.com/43223084/214469723-aab6ccbc-cdf0-4285-9950-2c78968b5808.gif)

  - <a href="google.com" target="_blank">Opens in new tab</a>
  - Check out [Azure Functions Verbose Logging](https://roccosmoderncode.wordpress.com/2022/09/22/functions-verboselogging/)
