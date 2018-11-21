# Google Kubernetes Engine

```
# Convert a string to base64
$ echo -n 'admin' | base 64

# Decode it
$ echo 'MWYyZDFlMmU2N2Rm' | base 64 --decode

# Delete pods
$ kubectl delete pod [podnames]

# Show a list of secrets
$ kubectl get secret

# Display a secret as a yaml format
$ kubectl get secret [name of secret] -o yaml

# Edit a secret
$ kubectl edit secret [name of secret]
```
