# Usage
$ git clone https://github.com/qwqw1314/echo.git <br>
$ kubectl apply -f echo/postgresdb/ <br>
$ kubectl apply -f echo/ <br>
$ curl \`kubectl get services loadbalancer --output jsonpath='{.status.loadBalancer.ingress[0].ip}'\`
