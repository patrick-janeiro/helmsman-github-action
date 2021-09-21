# Helmsman Github Action

This action uses the popular [helmsman](https://github.com/Praqma/helmsman) tool to help manage and deploy multiple charts.

## Inputs

## `args`

**Optional** The path to the chart file. Default `""`.

## Example usage

uses: actions/helmsman-action@v1
with:
  args: '-f ./build/helm/charts.yaml -apply'