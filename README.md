# springboot-crud-mysql-vuejs-helm
This is a helm-chart example for the [springboot-crud-mysql-vuejs-k8](https://github.com/ebd622/springboot-crud-mysql-vuejs-k8) project.

**1. Clone the repository**
```
git clone https://github.com/ebd622/springboot-crud-mysql-vuejs-helm.git
cd springboot-crud-mysql-vuejs-helm
```

**2. Install chart**

Run the following command just to see generated templates (no deployment):

```
helm install crud-app --dry-run .
```

Install the chart:
```
helm install crud-app .
```
A chart with the name crud-app will be deployed
 

**3. Get info about deployment**
List all the deployments:
```
helm ls
```
Get deployment history:
```
helm history crud-app
```

**4. Run tests**

```
helm test crud-app
```

**5. Uninstall the chart**
```
helm uninstall crud-app
```
