# Helmsman Github Action

This action uses the popular [helmsman](https://github.com/Praqma/helmsman) tool to help manage and deploy multiple charts.

## Inputs

## `chart-file`

**Required** The path to the chart file. Default `"./charts"`.

## `debug`

**Optional** Sets the --debug flag. Default `""`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'