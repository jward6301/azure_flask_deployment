# azure_flask_deployment
HHA 504 Week 2 assignment - Azure Flask Deployment


# Steps for the assignment
To set up the application I followed these steps
1. Ensured that all of the template files and app.py files were created and typed correctly
2. Ran the app.py file in the terminal to ensure it was working by running python app.py
3. If it looks correct you can move onto the azure section 
4. From this link: https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-linux?pivots=apt you will copy the command code curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash and run it in the terminal 
5. Next you will run the command as
6. Then run az login --use-device-code and log into Microsoft/azure
7. Next run the following code but update to match your information az webapp up --resource-group <groupname> --name <app-name> --runtime <PYTHON:3.9> --sku <B1>. Mine was az webapp up --name Jessica-504-flask1 --runtime PYTHON:3.9 --sku B1
8. Open the azure website and open app services to view the status of your web app

# Link/URL
https://jessica-504-flask1.azurewebsites.net/
