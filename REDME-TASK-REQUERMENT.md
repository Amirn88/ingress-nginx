 1. Kubernetes cluster containing:
● One master
● One or more nodes
● Access to kubernetes API is restricted to specific IP addresses.
* Document creation of cluster and all needed access rights in git repository.
2. On the Kubernetes cluster:
● Deploy nginx ingress - https://github.com/kubernetes/ingress-nginx/.
● Deploy "Juice Shop" application, you can use the official docker image from
‘bkimminich/juice-shop’.
● Expose “Juice Shop” application inside the cluster using a service.
● Expose “Juice Shop” application to outside the cluster using the nginx ingress.
3. Use calico Network plugin
