# lldap

The randomly generated admin password can be found using the command below. It is recommended to change this after logging in or to create a new user in the lldap_admin group then delete the default admin account.
```
kubectl get secret lldap -o jsonpath='{.data.LLDAP_ADMIN_PASSWORD}' | base64 -d
```

Another option is using the included bootstrap option which runs a script to automatucally create inital accounts and change the admin password. You can retrieve the admin password or any initial user password below.
```
kubectl get secret lldap-bootstrap -o jsonpath='{.data.users}' | base64 -d | jq '. | select(.id=="admin")'
```
