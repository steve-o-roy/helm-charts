# Caktus Helm Charts

This repository contains Helm charts by [Caktus Group](https://www.caktusgroup.com/).

## Adding the Caktus Helm repository

To add the Caktus Helm repository, run the following command:

```bash
helm repo add caktus https://caktus.github.io/helm-charts
```

## Searching for a chart

To see the charts available to install and their versions, run:

```bash
helm search repo caktus
```

## Installing a chart

To install a chart, run:

```bash
helm install <release-name> caktus/<chart-name>
```

## Updating the Caktus Helm repository

To update the Caktus Helm repository, run:

```bash
helm repo update
```

## Chart documentation

For more information about a chart, run the following command:

```bash
helm show readme caktus/<chart-name>
```
