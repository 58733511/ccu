# ccu
ccu


docker login ccu.uni-konstanz.de:5000


make the docker-compose.yml and Dockerfile

docker-compose up --build

docker push ccu.uni-konstanz.de:5000/leichen.wang/pix2pix-pytorch


make the job-script.yaml

kubectl apply -f job-script-pvc.yaml

kubectl get pods

kubectl logs xxxxxx

kubectl describe pod xxxxx

kubectl exec -it xxxx /bin/bash

kubectl cp leichen-wang-pix2pixhd-pytorch-pvc-8jfvw:/mnt/pvc-pix2pix /home/leichen/images

kubectl delete -f job-script.yaml

leichen-wang-pix2pix-pytorch-pvc
/mnt/pvc-pix2pix
