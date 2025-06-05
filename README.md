So, this might seem like a sample helm excersice but dont be mistaken - there is alot of meaning behind this task.

This task needs to be completed today for the evaluation(will be checked on sunday)

The requirement is:
1. fix the helm chart to include keda objects in the templates
2. import the new application manifest provieded by the developer and integrate into the existing structure
3. This new app needs some secret data to be retrieved from an external secret manager(vault for example)
secertName: new-super-secret-app-secrets
needs to contain the following:
DB_HOST: "127.0.0.1"
DB_USERNAME: "psql"
DB_PASSWORD: "superhardpassword"
for the sake of it dont go through all the trouble to fully integrate eso but do create the externalSecret object and integrate it into the charts and make it templateable.
3. test everything.
4. these applications need to be managed by argo, implement the installation of the umbrella into argo.

Make sure to use your envrionment in the lab as you need a running cluster for this.
your vm is up - 10.0.2.4
Cluster needs to have argo and keda installed.

