# AZ400Lab01 - Continuous deployment to Azure App Service

1. Open Microsoft Azure Portal
2. Log into your Azure account, select App Services in the Azure portal left navigation, and then select configure az400-9940427-func1.
3. On the app page, select Deployment Center in the left menu.
4. On the Build provider page, select Azure Pipelines (Preview), and then select Continue.
5. On the Configure page, in the Code section:
For GitHub, drop down and select the Organization, Repository, and Branch you want to deploy continuously.
6. Select Continue.
7. On the Test page, choose whether to enable load tests, and then select Continue.
8. Depending on your App Service plan pricing tier, you may see a Deploy to staging page. Choose whether to enable deployment slots, and then
select Continue.
9. After you configure the build provider, review the settings on the Summary page, and then select Finish.
References:
https://docs.microsoft.com/en-us/azure/app-service/deploy-continuous-deployment

(ET T3/54 Simulation)
