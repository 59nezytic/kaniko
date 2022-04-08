# kaniko

```
k create secret docker-registry regcred --docker-server=https://index.docker.io/v1/ --docker-username={USER_ID} --docker-password={PASSWORD} --docker-email={EMAIL} -n {NAMESPACE}
```

```
k create -f kaniko-volume.yaml
```

```
k create -f pod.yaml
```
