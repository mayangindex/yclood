# init project

## Create VM

```bash
az vm create\
   --resource-group marketplace \
   --name vm_$(openssl rand -hex 4) \
   --image elk-ubuntu-2204-lts-2023-11-19T20-03-38Z \
   --admin-username azureimage \
   --admin-password 123dggd-eraRTvac-dvsjjs
```
