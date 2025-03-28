Kubernetes commands overview under this session:
How to generate ssh keys: ssh-keygen

SMOKE TESTING
1. How to get Nodes - kubectl get nodes
2. How to get nodes without headers: kubectl get nodes --no-headers
3. cluster info: kubectl cluster-info
4. Namespace: kubectl get ns
5. How to get pods: kubectl get pods -> under default namesapce
6. How to get pods under kube-system namespace: kubectl get pods -n kube-system
7. get pods under kube-system in detail: ku get pods -n kube-system -o wide| grep -i <component-name>
Example: kubectl get pods -n kube-system -o wide|grep -i scheduler -> components like: controller,api,etcd

