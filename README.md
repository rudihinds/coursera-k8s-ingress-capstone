## Kubernetes Ingress activity notes

Project structure:

```
.
├── deploy-a.yml
├── deploy-b.yml
├── ingress.yml
├── README.md
|── service-a.yml
├── service-b.yml
```

## Create two app deployments task notes:
```
- container application image to use for both apps: gcr.io/google-samples/hello-app:1.0
- 3 replicas in each deployment
- One service for each replica set 

```

## Create ingress with two routes task notes:
```
1. the host can be anything you like (eg myhost.com)
2. Routes can be any (eg '/main' and '/blog')
3. once complete test using 'curl myhost.com/main' and 'curl myhost.com/blog'
```

