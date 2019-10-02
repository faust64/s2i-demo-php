# OpenShift S2I Demo

```
oc new-app php~https://github.com/faust64/s2i-demo-php
oc expose svc/s2i-demo-php
oc logs -f bc/s2i-demo-php
oc get routes
```
