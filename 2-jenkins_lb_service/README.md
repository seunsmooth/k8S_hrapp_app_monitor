Requirement:  Deploy Jenkins on the cluster 
----------------------------------------------  
A.    Create a namespace called pipeline where it will be deployed.
       
       kubectl create ns pipeline

B. Create and expose Jenkin as a Load Balancer Service

        kubectl apply -f jenkins-service.yaml