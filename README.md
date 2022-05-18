# kube-flipstarter
Kubernetes configurations for for imageproxy.

## Deployment
1. Add a new blank disk on GCE called `imageproxy-data` with your preferred cache size.
2. Edit `kube/imageproxy-ingress.yml` with your preferred domain name.
3. Run `kubectl apply -f kube`.
4. Profit!
