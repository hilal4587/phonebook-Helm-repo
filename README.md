```bash
helm repo add phonebook-Helm-repo https://raw.githubusercontent.com/hilal4587/phonebook-Helm-repo/main
helm install phonebook-helm-repo phonebook-Helm-repo/phonebook-chart
```
- To use own images execute as below:
```bash
helm install phonebook-app phonebook-repo --set webserver_image=<image-name> --set resultserver_image=<image-name>
```