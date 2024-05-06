# java-helm

helm install ilc-app1 ilc-app-chart --set service.name=ilc-app1,env=production
helm install ilc-app2 ilc-app-chart --set service.name=ilc-app2,env=staging
