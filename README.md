# Running ECK with Istio

_(WIP)_

## Steps to reproduce

- _istioctl install --set profile=demo -y_
- Install ECK operator
- Install ECK manifest / ES & Kibana
- Apply ingress (http, https still not working)
- Check the ingress IP (kubectl get svc -n istio-ingress) and ajust your DNS entry (in my case, eck.framsouza.co)
