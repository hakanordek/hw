# Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `docker-challenge`

**Required** Say Hi to Hakan. Default `"World"`.

## Outputs

### `time`

The time we said hi.

## Example usage

uses: hakanordek/hw@v1
with:who-to-greet: 'someone'