# action-wait-for-it
Github action to wait for a service to listen on a particular port

## Inputs

## `host`

**Required** The hostname of the service to test.

## `port`

**Required** The port of the service to test.

## `timeout`

**Required** How long to wait in seconds for the host:port to respond.  Zero for no timeout 

## Outputs

status code

## Example usage

uses: vouched/action-wait-for-it
with:
  host: localhost
  port: 8000
  timeout: 60
