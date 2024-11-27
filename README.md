Use config to add environment variable needed for the order service.
First create config map file as config-order-map.yml, then add this reference to the pod deployment manifest
Then apply first configmap file by command
$ kubectl apply -f config-map-order.yml
Then apply that config running the deployment manifest
$ kubectl apply -f k8s-order-deployment.yml