# ARM 

```
az deployment group create \
  --name addskuparameter \
  --resource-group myResourceGroup \
  --template-file $templateFile \
  --parameters storageName=azurearmtest2
```

https://docs.microsoft.com/ja-jp/azure/azure-resource-manager/templates/template-tutorial-create-first-template?tabs=azure-powershell
