# Installing

helm install mariantest1 ogc-pilot-ewps \
 --set persistence.storageClass=nfs-provisioner \
 --set ingress.host=wps.your-domain \
 --set image.repository=mneagul/ewps-pilot-ewps \
 --set image.tag=latest
