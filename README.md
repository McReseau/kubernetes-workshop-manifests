# TASKS - Getting started with Kubernetes


 ## - TASK 1:
    Create 02 namespaces: Production and Development

 ## - TASK 2: 
    Create a pod called apps in the development namespace
    Create a deployment called sbom in the production namespace (pod should be called apps)

 ## - Task 3: 
    Create a service for Apps and sbom in their respective namespaces. Apps (apps-svc), sbom (sbom-svc)

 ## - Task 4: 
    Create a secret named login in both namespaces and mount them on the Apps (user=teligencia, pass=Teligencia) as environment variables.

 ## - Task 5: 
    Scan images named ubuntu:23.04 and nginx:1.15.0 with trivy to search vulnerabilities.

 ## - Task 6:
    Create a network policy called deny_all outcoming traffic
    Create a network policy called np-apps_dev-to-apps_prod which only allow traffic from apps in the development namespace to Apps in the Production namespace on any port.

#


# SOLUTION - Getting started with Kubernetes

#

## - TASK 1 - Solution :
    [solution in file create_ns.yaml]
 
## - TASK 2 - Solution :
    [Solution 1 in file pod-apps.yaml]
    [Solution 2: in file dep-apps.yaml]

## - TASK 3 - Solution :
    [Solution 1: in file svc_apps_test.yaml]
    [Solution 2: in file svc_apps_prod.yaml]

## - TASK 4 - Solution :
    [Solution in file login.yaml 

## - TASK 5 - Solution :
    [Solution in the file "Trivy commands"]

## - TASK 6 - Solution :
    [Solution 1 in the file np-deny_all.yaml]
    [Solution 2 in the file np-apps_dev_to-apps_prod.yaml]

### Any issue during this workhop?
### email me on delegueasr@gmail.com

