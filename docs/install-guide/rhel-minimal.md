# RHEL Minimal

## Dockerfile
```
FROM registry.access.redhat.com/rhel7/rhel:latest
```

If the docker file is created then:

`docker build -t rhel-minimal:latest .`

Push that to your registry and this is used as a base image for all omar services.
