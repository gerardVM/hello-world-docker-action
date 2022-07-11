# Docker action "Hola Mundo v2"

Esta action imprime "Hola Mundo" o "Hola" + el nombre de la persona al log.

## Inputs

### `who-to-greet`

**Requerido** El nombre de la persona a quien salidar. Por defecto `"Munso"`.

## Outputs

### `time`

La fecha en la que saludé.

## Example usage

```
uses: gerardVM/hello-world-docker-action@v1
with:
	who-to-greet: 'Pelades'
```
