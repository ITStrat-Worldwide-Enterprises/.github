## Welcome to the HSIN Code Challenge Demo Site
Our demo site is designed to showcase the functionalities across various departments including **IT**,**Accounting**, **HR**, and **Compliance**. Below you will find detailed instructions for accessing the site using the credentials provided. Please select the account that corresponds to the level of access and departmental interface you wish to review.

### How to access website? 
Reference implementation application can be accessed using https://hsin-gateway-dev.exor-dev.com/hsin-it

### Full Access Accounts
Individuals with full access credentials are granted unrestricted access to all available functionalities across each of the four departments. These accounts are particularly advantageous for those who seek to experience the system's complete capabilities.

|User Name|Password|
| ------------ | ------------ |
|jamesalton@it-strat.com|hsinUser2024!|
|jonathansmith@it-strat.com|hsinUser2024!|
|yusufghantiwala@it-strat.com|hsinUser2024!|

### Test Accounts with Partial Access
In order to simulate the standard user and administrator roles within a specific department, test accounts with limited access are established. Administrator accounts possess full access to all functionalities within their respective departmental domains, whereas user accounts are restricted to accessing only the data that is relevant to their roles. This segregation of roles ensures that access to sensitive information is restricted to authorized personnel only, thus enhancing the security of departmental assets.

|User Name|Password|Role Name|
| ------------ | ------------ | ------------ |
|it-admin@hisncodechallange.com|hsinTest2024!|IT Admin|
|it-user@hisncodechallange.com|hsinTest2024!|IT User|
|accounting-admin@hisncodechallange.com|hsinTest2024!|Accounting Admin|
|accounting-user@hisncodechallange.com|hsinTest2024!|Accounting User|
|hr-admin@hisncodechallange.com|hsinTest2024!|HR Admin|
|hr-user@hisncodechallange.com|hsinTest2024!|HR User|
|comp-admin@hisncodechallange.com|hsinTest2024!|Compliance Admin|
|comp-user@hisncodechallange.com|hsinTest2024!|Compliance User|

### How Demo Site code repository is organized?
Demo site uses Github code repository. For CI/CD pipeline it leverages Github Actions. Each repo as well as subfolder has associated README describing details. 
Demo site is defined as Github Organization and each department specific shared services are in its own department service repository. UX shared accross multiple department has its own repository. All other site related artifacts are combined together.

|Repository Name|Usage|
| ------------ | ------------ |
|hsin-it|Shared UX repository|
|hsin-it-api|IT Department service repository|
|hsin-hr-api|HR Department service repository|
|hsin-compliance-api|Compliance Department service repository|
|hsin-accounting-api|Accounting Department service repository|
