# problem statement
gets a secret string from azure keyvault

# example usage

> note: in examples, VERSION represents a version of the azure.keyvault.secret-string.get pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.keyvault.secret-string.get#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.keyvault.secret-string.get#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/azure.keyvault.secret-string.get#VERSION }
    inputs:
      subscriptionId:
      loginId:
      loginSecret:
      name:
      vault:
      # end optional args
      loginTenantId:
      loginType:
      # end optional args
    outputs:
      value:
```
