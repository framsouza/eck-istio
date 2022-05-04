# Running ECK with Istio

_(WIP)_

## Steps to reproduce

1._istioctl install --set profile=demo -y_
2.Install ECK operator
3.Install ECK manifest / ES & Kibana
4. Apply ingress (http, https still not working)
5. Check the ingress IP (kubectl get svc -n istio-ingress) and ajust your DNS entry (in my case, eck.framsouza.co)
