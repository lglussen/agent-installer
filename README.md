# Generate Openshift Agent Installer ISO using Helm Templates

Basic Helm templates introduction with a practical example of
generating an AgentInstaller ISO for installing OpenShift.

Generate an iso:
```shell

# generate a dev iso (values-dev.yaml)
./build-iso dev

# generate a sandbox iso (values-sandbox.yaml)
./build-iso sandbox

# generate a production iso (values-prod.yaml)
./build-iso prod

```
