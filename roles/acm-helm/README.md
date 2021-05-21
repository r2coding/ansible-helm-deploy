# Configuration

If you are running in your local machine you can use the following steps.

1. First log into ACM

```
oc login...
```

2. Run the following command to deploy

```
ansible-playbook -i inventory.yaml main.yaml
```

3. Run the following command to undeploy

```
ansible-playbook -i inventory.yaml main.yaml -e "undeploy=yes"
```