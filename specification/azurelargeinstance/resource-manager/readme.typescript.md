## TypeScript

These settings apply only when `--typescript` is specified on the command line.
Please also specify `--typescript-sdks-folder=<path to root folder of your azure-sdk-for-js clone>`.

``` yaml $(typescript)
title: LargeInstanceManagementClient
typescript:
  azure-arm: true
  package-name: "@azure/arm-largeinstance"
  output-folder: "$(typescript-sdks-folder)/sdk/largeinstance/arm-largeinstance"
  payload-flattening-threshold: 1
  clear-output-folder: true
  generate-metadata: true
```
