This project involved the development, deployment, and management of an investment group web application. The web app is based on Shiny and was designed to streamline transactions and group administration operations for an investment group. Key functionalities of the web app include:

- New member registration
- General emailing and communication features
- Scheduling of merry-go-round activities
- Member profile management
- Information management for member monthly contributions (merry-go-round, savings account, and welfare account)
- Member loan disbursements
- Miscellaneous member disbursements such as fines and registration fees
The project implementation included:

- Utilization of MongoDB database to manage user login details (authentication info) and transaction data (payments and disbursements)
- Implementation of SQL database to manage user login information logs
- Backup of user login, transactions, and system information on Google Cloud Platform (GCP)
- Development of the user interface using R Shiny app
- CSS styling
- Data analysis for Key performance indicators
Currently, the app is deployed on shinyapps.io but can also be deployed on GCP, AWS, Shiny Server, Shiny Live, or any other hosting platform.

Transactions are hosted on remote Excel files and Google Sheets. The app employs a Knearest neighbor approach to detect mismatch in transactions and suggest further audit by the admin.

Note: 
This project was developed for for a specific chama(i.e Investiment group) which I am a member of and is currently being redesigned to be used by general groups, with improvements such as:
- *use of r6 classes to manage user accounts,transaction etc*
- *Generalization of design to fit different models the current model has only the following modules, merry-go-round, savings,welfare,miscellaneous contribution*
  *the current design allows users to create custom modules/ contributions, and profiles*
- *The __source code__ to the current implementation will be witheld for privacy purposes but the remodelled version will be made public through this repo*

Here is a glimse of the current implementation:
![Financ2](https://github.com/user-attachments/assets/03611a13-5a53-4368-bac3-0e117f15f2e6)

![financ3](https://github.com/user-attachments/assets/8c107a24-0e9c-4694-9c60-a17100448524)

![finc4](https://github.com/user-attachments/assets/f8017ac1-cec7-403b-803c-fdab5b5bd772)

![finc5](https://github.com/user-attachments/assets/400909f8-4317-4738-bb39-eea8fbc83e71)


  
