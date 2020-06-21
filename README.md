# springboot-crud-mysql-vuejs-helm
Helm example for the [springboot-crud-mysql-vuejs-k8](https://github.com/ebd622/springboot-crud-mysql-vuejs-k8) project.
## Step-by-step deployment
For better understanfing let's deploy the application step-by-step.

**1. Clone the repository**
```
git clone https://github.com/ebd622/springboot-crud-mysql-vuejs-helm.git
cd springboot-crud-mysql-vuejs-helm
```

**2. Install chart**

Run the following command just to see a generated templates (no deployment):

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
TODO

**5. Uninstall the chart**
```
helm uninstall crud-app
```
