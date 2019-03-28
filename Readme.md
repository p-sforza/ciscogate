# Ciscogate

Bla bla 

## Usage

Building and compiling on OpenShift (env value as default)

```bash
oc new-app docker.io/centos:latest~https://github.com/ugol/ciscogate.git \
  --env="CISCO_ADDRESS=localhost:8080" \
  --env="CISCO_APICURL=<APIC_HOST>" \
  --env="CISCO_APICUSERNAME=<APIC_USER>" \
  --env="CISCO_APICPASSWORD=<APIC_PASSWORD>" \
  --env="CISCO_OPENSHIFTTENANT=openshift39" \
  --env="CISCO_EPGTOBECREATED=prova18e26" \
  --env="CISCO_GRACEFULTIMEOUT=15s" \
  --env="CISCO_WRITETIMEOUT=15s" \
  --env="CISCO_READTIMEOUT=15s" \
  --env="CISCO_IDLETIMEOUT=1m0s"
```

