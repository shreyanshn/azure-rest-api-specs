## AZ

These settings apply only when `--az` is specified on the command line.

``` yaml $(az)
az:
  extensions: customproviders
  namespace: azure.mgmt.customproviders
  package-name: azure-mgmt-customproviders
az-output-folder: $(azure-cli-extension-folder)/src/customproviders
python-sdk-output-folder: "$(az-output-folder)/azext_customproviders/vendored_sdks/customproviders"
  
#cli:
#    cli-directive:
#      directive on operationGroup
#       - select: 'operationGroup'
#         where:
#             operationGroup: 'operations'
#         hidden: true
#       - where:
#             parameter: location
#         required: true

```
