scp /home/dockerserver/.kube dockerserver@192.168.0.151:/home/dev-desktop

scp -r dockerserver@192.168.0.151:/home/dockerserver/.kube /home/dev-desktop

ssh -L 42085:localhost:42085 dockerserver@192.168.0.151

curl localhost/foo/hostname

curl 192.168.0.151/foo/hostname
curl 192.168.0.151/bar/hostname


kubectl exec --stdin --tty mongo-express-5bf4b56f47-w6mxw -- /bin/bash

f5ca9074-af46-4d95-a0a4-a5d8b5e3977e.cfargotunnel.com