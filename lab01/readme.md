
## To download the Code from the Git

[Lab Code](https://github.com/MicrosoftLearning/AZ-204-DevelopingSolutionsforMicrosoftAzure.git)

## To install the Azure CLI

- Open the CMD and run the following command

```
winget install --exact --id Microsoft.AzureCLI

```

## To find list of resources in the Azure 

- this will help us know our resource group

```
az webapp list --output table

```

## In task 6: 

- Change this ManagedPlatform with your own resource group

```
az webapp list --resource-group ManagedPlatform
```

```
az webapp list --resource-group <Your ReourceGroup>
```


## To delete the all the Resources we created in the Azure Portal

```
az group delete --name <resource-group-name>
```

