# A Flask Containerized app

the app is about orchesterizing  a flask app that has been dockerized

```
helm create flaskChart
```
cd into flaskChart**
```
helm template <chartname> .
```
or
```
helm tempate <chartname> > flask.yaml
```
to validate th helm chart
```
helm lint
```

to start/install the helm chart
```
helm install <flaskHelm> .
```
to delete
```
helm delete <flaskHelm> 
```

```
helm list -a
```

